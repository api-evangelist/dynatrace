---
name: dynatrace-manage-account-access
description: Manage Dynatrace account users, groups, permissions and environments over the global Account Management API. Use when an agent must provision or audit access — a different host, a different auth model and a different error shape from the Environment API.
api: Dynatrace Account Management API
operations:
  - listUsers
  - createUser
  - getUser
  - updateUser
  - deleteUser
  - listGroups
  - createGroup
  - getGroup
  - updateGroup
  - deleteGroup
  - listPermissions
  - listEnvironments
generated: '2026-08-29'
method: generated
source: openapi/dynatrace-users-api-openapi.yml, openapi/dynatrace-groups-api-openapi.yml, openapi/dynatrace-permissions-api-openapi.yml, openapi/dynatrace-environments-api-openapi.yml
license: CC-BY-NC-SA-4.0
---

# Manage Dynatrace account access

Base URL: **`https://api.dynatrace.com`** — a global host, not your tenant. This is the single
most common mistake on this API: the Account Management API does **not** live on
`{environmentId}.live.dynatrace.com`.

Auth: OAuth 2.0 **client credentials** against
`https://sso.dynatrace.com/sso/oauth2/token`, then `Authorization: Bearer <jwt>`.
Scopes: `account-idm-read` for reads, `account-idm-write` for writes.
Everything is scoped by an `account-uuid` path parameter.

Dynatrace requires **both the user identity and the token** to carry a permission. Granting the
token alone returns `403`.

## Audit first

- `listEnvironments` — which tenants this account owns. This is the only structural bridge between
  the account world and the observed world; the environment IDs it returns are the
  `{environmentId}` you use against the Environment API.
- `listUsers`, `listGroups`, `listPermissions` — the current state.
- Paginate with `nextPageKey` + `pageSize`; the cursor voids every other query parameter.

## Provision

1. `createGroup` before `createUser` where possible — a user without a group has no effective
   permission.
2. `createUser`, then bind them: `getUser` confirms the user exists and which groups they hold.
3. `updateGroup` to adjust a group's permissions.

Each create has a matching delete — `deleteUser`, `deleteGroup` — so this surface **is**
reversible, unlike telemetry ingest. No time window is published for any of these reversals, so do
not assume one exists.

## Errors on this API differ from the Environment API

Two vendor JSON envelopes, both documented in `errors/dynatrace-problem-types.yml`:

- `{"error": true, "message": "...", "payload": null}` — general.
- `{"code": <n>, "message": "...", "errorsMap": {...}}` — IAM policy and binding endpoints;
  `errorsMap` carries the per-field validation detail on `400` and `422`.

Watch for **`410 Gone`**. Nine Account Management operations have been removed and say so in the
contract, several naming their successor: `getEnvironmentUsage` → `getEnvironmentUsageV3`,
`getEnvironmentCost` → `getEnvironmentCostV3`, `listNotifications` → `listNotificationsV2`. The
policy-validation endpoints (`validateLevelPolicy`, `validateNewLevelPolicy`) are also `410` — the
dry-run affordance on this API has been withdrawn with no replacement named, so a policy change
cannot be rehearsed before it is applied.
