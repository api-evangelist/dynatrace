---
name: dynatrace-ingest-telemetry
description: Push logs, events and custom metrics into Dynatrace over the Environment API v2 and read them back. Use when an agent must write telemetry into Dynatrace — and needs to know that ingest is neither idempotent nor reversible.
api: Dynatrace Logs, Events and Metrics APIs v2
operations:
  - ingestLogs
  - searchLogs
  - aggregateLogs
  - exportLogs
  - ingestEvent
  - listEvents
  - getEvent
  - ingestCustomMetrics
  - queryMetricData
  - listMetrics
  - getMetricDescriptor
  - deleteCustomMetric
generated: '2026-08-29'
method: generated
source: openapi/dynatrace-logs-api-openapi.yml, openapi/dynatrace-events-api-openapi.yml, openapi/dynatrace-metrics-api-openapi.yml
license: CC-BY-NC-SA-4.0
---

# Ingest telemetry into Dynatrace

Base URL: `https://{environmentId}.live.dynatrace.com/api/v2`
Auth: `Authorization: Api-Token <dt0s01 token>` with the ingest scope the operation names.

## Read this before you write anything

Ingest into Dynatrace is **not idempotent and not reversible**.

- There is no idempotency key anywhere in this API. A retried `ingestLogs`, `ingestEvent` or
  `ingestCustomMetrics` after a timeout or a `429` writes the datapoint **twice**.
- There is no delete for an ingested log line, event or metric datapoint. `deleteCustomMetric`
  removes the whole metric and its history, not one bad point. Ingested data ages out on Grail
  bucket retention; it does not come back out on request.
- Pushing **new custom metrics is billed** per metric per month, and read access is free only on a
  fair-use basis. An agent can incur cost here without touching configuration.

So: validate the payload before the first call, and on a failure whose outcome you cannot
determine, **read back before you retry**.

## Logs

- `ingestLogs` — `POST /logs/ingest`. Max payload **10 MB** per request for this API (the estate
  default is 1 MB).
- `searchLogs` / `aggregateLogs` / `exportLogs` — read back what you wrote.
  **These three are deprecated as of SaaS 1.331** in favour of the Logs on Grail API, end of life
  end of 2027. Prefer DQL against Grail for new work.

## Events

- `ingestEvent` — `POST /events/ingest`. Returns an `eventIngestResults[]` with one `eventId` per
  accepted event; keep them, they are your only handle on what was written.
- `listEvents` / `getEvent` — read back.

## Metrics

- `ingestCustomMetrics` — `POST /metrics/ingest`, line-protocol payload. Ingest payload ceilings
  are 8 MB, 4 MB or 2 MB depending on the ingest endpoint.
- `listMetrics`, `getMetricDescriptor`, `queryMetricData` — discover and read.
- `deleteCustomMetric` — the only reversal in this skill, and it is coarse: it deletes the metric,
  not the mistake.

## Paging back through what you wrote

`nextPageKey` + `pageSize`. **When `nextPageKey` is set, all other query parameters except
`pageSize` are ignored.** Send the cursor alone.

## Prefer OTLP where you can

Dynatrace serves native OTLP ingest at
`https://{environmentId}.live.dynatrace.com/api/v2/otlp` with the standard OpenTelemetry paths
`/v1/traces`, `/v1/metrics`, `/v1/logs`. If the source is already OpenTelemetry-instrumented,
point the exporter there instead of writing against these vendor endpoints — but note
**gRPC is not supported**, only OTLP/HTTP.
