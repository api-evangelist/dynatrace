---
name: dynatrace-triage-problem
description: Triage a Davis problem over the Dynatrace Problems API v2 — find open problems, read one, record findings on its comment thread, and close it. Use when an agent must work a Dynatrace incident through REST rather than DQL.
api: Dynatrace Problems API v2
operations:
  - listProblems
  - getProblem
  - listProblemComments
  - createProblemComment
  - getProblemComment
  - updateProblemComment
  - deleteProblemComment
  - closeProblem
generated: '2026-08-29'
method: generated
source: openapi/dynatrace-problems-api-openapi.yml
license: CC-BY-NC-SA-4.0
---

# Triage a Dynatrace problem

Base URL: `https://{environmentId}.live.dynatrace.com/api/v2`
Auth: `Authorization: Api-Token <dt0s01 token>`

Dynatrace requires **both the user identity and the token** to carry a permission scope. A token
that holds the scope while the user does not still returns `403`.

## 1. Find the problems worth working

`listProblems` — `GET /problems`

- Narrow with `problemSelector` (for example open problems only) and `entitySelector`.
- Paginate with `nextPageKey`. **When `nextPageKey` is set, every other query parameter except
  `pageSize` is ignored** — re-sending your filters alongside the cursor silently changes the
  result set. Carry only the cursor and `pageSize`.
- Stop when the response has no `nextPageKey`.

## 2. Read the one you picked

`getProblem` — `GET /problems/{problemId}`

Returns the Davis problem: root cause entity, impacted entities, severity, timing. Resolve any
entity ID against the Entities API (`getEntity`) — Dynatrace entity IDs carry their type as a
prefix (`HOST-…`, `SERVICE-…`), so you can read the type without a lookup.

## 3. Record what you found

`listProblemComments` — `GET /problems/{problemId}/comments`
`createProblemComment` — `POST /problems/{problemId}/comments`

Write the finding as a comment before you act on it. A comment is the only reversible artifact in
this flow: `updateProblemComment` edits it and `deleteProblemComment` removes it. There is **no
idempotency key on this API** — a retried `createProblemComment` after a timeout posts a second
comment. Read the thread back with `listProblemComments` before retrying.

## 4. Close it — this one is one-way

`closeProblem` — `POST /problems/{problemId}/close`

**The captured contract declares no re-open operation.** Treat `closeProblem` as irreversible and
confirm with a human before calling it on a problem you did not open.

## Errors and limits

- `400` bad request, `401` token authentication failed, `403` scope missing on the user or the
  token, `404` not found in this environment.
- The Environment API v2 declares these codes with **no response body schema**, so parse
  defensively — see `errors/dynatrace-problem-types.yml`.
- `429` means the environment thread pool and its queue are full (10-second queue timeout). It is
  documented but declared on no operation, and **no `Retry-After` or `RateLimit-*` header is
  published** — back off exponentially rather than reading a header that will not be there.
