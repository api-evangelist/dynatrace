# Dynatrace GraphQL Schema

## Overview

This conceptual GraphQL schema models the Dynatrace observability and AIOps platform, covering the full surface of the Dynatrace Environment API v2 and related platform APIs. Dynatrace provides full-stack observability across applications, infrastructure, cloud, and digital experience, powered by the Davis AI engine and the Grail data lakehouse.

- **Provider:** Dynatrace
- **Docs:** https://docs.dynatrace.com/docs/dynatrace-api
- **GitHub:** https://github.com/Dynatrace
- **Base URL:** https://mySampleEnv.live.dynatrace.com/api/v2

## Schema Source

Conceptual schema derived from:

- Dynatrace Environment API v2 (entities, metrics, problems, events, logs, SLOs, traces)
- Dynatrace Configuration API v1
- Dynatrace Account Management API
- Dynatrace Synthetic API v2
- Dynatrace DQL/Grail Query API
- Dynatrace Automation API
- Dynatrace Application Security API
- Dynatrace Davis AI API
- Dynatrace Document API

## Type Summary

| Domain | Types |
|---|---|
| Environments & Zones | Environment, EnvironmentDetails, ManagementZone, Unit, NetworkZone |
| Entities | Entity, EntityDetails, EntityType, EntityTag, EntityProperty, EntityRelationship |
| Services | Service, ServiceDetails, ServiceMetrics, ServiceDependency |
| Applications | Application, ApplicationDetails, ApplicationMetrics, ApplicationDetection |
| Processes | Process, ProcessDetails, ProcessGroup, ProcessGroupDetails |
| Metrics | Metric, MetricDescriptor, MetricExpression, MetricSeries, MetricDataPoint, DataPoint, Dimension, DimensionValue |
| Traces & Spans | Trace, TraceDetails, TraceSegment, Span, SpanDetails, SpanEvent, SpanLink |
| Problems & Alerts | Problem, ProblemDetails, ProblemStatus, ProblemSeverity, ProblemImpact, RootCause, RootCauseEvent, Evidence, Alert, AlertCondition, AlertStatus |
| SLOs | SLO, SLODetails, SLOTarget, SLOBudget, ErrorBudget |
| Tags | Tag, TagOverride |
| Dashboards | Dashboard, DashboardDetails, Tile |
| Synthetic | Synthetic, SyntheticMonitor, Test, TestResult, StepResult |
| Automation | AutoTag, APIToken |
| Events & Logs | Event, LogRecord, AuditLog, BusinessEvent |
| Security | Vulnerability, Attack, SecurityAdvice |
| AI & Analytics | DavisAnalysis, Forecast, Anomaly |
| Platform | Workflow, WorkflowExecution, Extension, Credential, Bucket, Document |

## Queries

- `environment(id: ID!)` — fetch environment details
- `environments` — list all environments
- `managementZones` — list management zones
- `entity(entityId: ID!)` — fetch a single monitored entity
- `entities(selector: String, type: String, tags: [String])` — query entities
- `entityTypes` — list all entity types
- `service(entityId: ID!)` — fetch service entity
- `services(selector: String)` — list services
- `application(entityId: ID!)` — fetch application entity
- `applications(selector: String)` — list applications
- `processGroup(entityId: ID!)` — fetch process group
- `metricDescriptor(metricKey: String!)` — fetch metric descriptor
- `metricDescriptors(selector: String)` — list metric descriptors
- `metricData(metricSelector: String!, resolution: String, from: String, to: String)` — query metric time series
- `trace(traceId: ID!)` — fetch distributed trace
- `problem(problemId: ID!)` — fetch problem details
- `problems(from: String, to: String, status: ProblemStatus, entitySelector: String)` — list problems
- `slo(id: ID!)` — fetch SLO
- `slos` — list SLOs
- `dashboard(id: ID!)` — fetch dashboard
- `dashboards` — list dashboards
- `syntheticMonitor(monitorId: ID!)` — fetch synthetic monitor
- `syntheticMonitors` — list synthetic monitors
- `apiToken(id: ID!)` — fetch API token metadata
- `apiTokens` — list API tokens
- `events(from: String, to: String, entitySelector: String, eventType: String)` — query events
- `logRecords(query: String, from: String, to: String, limit: Int)` — search log records
- `auditLogs(from: String, to: String, filter: String)` — list audit log entries
- `vulnerability(id: ID!)` — fetch security vulnerability
- `vulnerabilities(riskLevel: String, status: String)` — list vulnerabilities
- `workflow(id: ID!)` — fetch workflow definition
- `workflows` — list workflows
- `extensions` — list available extensions
- `bucket(id: ID!)` — fetch Grail bucket

## Mutations

- `createEvent(input: EventInput!)` — ingest custom event
- `closeProblem(problemId: ID!, comment: String)` — close a problem
- `addProblemComment(problemId: ID!, comment: String!)` — add comment to problem
- `createSLO(input: SLOInput!)` — create SLO
- `updateSLO(id: ID!, input: SLOInput!)` — update SLO
- `deleteSLO(id: ID!)` — delete SLO
- `createSyntheticMonitor(input: SyntheticMonitorInput!)` — create synthetic monitor
- `updateSyntheticMonitor(id: ID!, input: SyntheticMonitorInput!)` — update synthetic monitor
- `deleteSyntheticMonitor(id: ID!)` — delete synthetic monitor
- `createAPIToken(input: APITokenInput!)` — create API token
- `revokeAPIToken(id: ID!)` — revoke API token
- `tagEntity(entityId: ID!, tags: [TagInput!]!)` — add tags to entity
- `untagEntity(entityId: ID!, tags: [String!]!)` — remove tags from entity
- `ingestLogRecords(records: [LogRecordInput!]!)` — push log records to Grail
- `ingestMetric(lines: String!)` — push metric via MINT protocol
- `ingestBusinessEvent(event: BusinessEventInput!)` — push business event
- `createWorkflow(input: WorkflowInput!)` — create automation workflow
- `executeWorkflow(id: ID!)` — trigger workflow execution
- `createBucket(input: BucketInput!)` — create Grail storage bucket
- `deleteBucket(id: ID!)` — delete Grail storage bucket
- `createCredential(input: CredentialInput!)` — store credential in vault
- `deleteCredential(id: ID!)` — delete stored credential
