# Dynatrace (dynatrace)

Dynatrace is a software intelligence platform that provides application performance monitoring, artificial intelligence for operations, cloud infrastructure monitoring, and digital experience management.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI Operations
- Analytics
- APM
- Application Performance Monitoring
- Application Security
- Automation
- Cloud Monitoring
- Digital Experience Management
- Intelligence
- Observability

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-18

## APIs

### Dynatrace Environment API

The Dynatrace Environment API provides access to monitoring data and configuration settings for a specific Dynatrace environment. It includes endpoints for metrics, problems, events, logs, entities, settings, and synthetic monitoring, and is the primary API for interacting with observability data within a Dynatrace environment.

- **Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api](https://docs.dynatrace.com/docs/dynatrace-api/environment-api)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Analytics
- Automation
- Intelligence
- Monitoring
- Observability

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api)
- [Authentication](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/basics/dynatrace-api-authentication)
- [SDK](https://developer.dynatrace.com/develop/sdks/client-classic-environment-v2/)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Metrics API v2

The Dynatrace Metrics API v2 allows you to query, ingest, and manage time-series metric data within a Dynatrace environment. It supports retrieving metric descriptors, querying data points with flexible selectors, and ingesting custom metrics from external sources.

- **Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/metric-v2](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/metric-v2)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Metrics
- Monitoring
- Observability
- Time Series

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/metric-v2)
- [API Reference](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/metric-v2/best-practices)
- [OpenAPI](openapi/dynatrace-metrics-api-v2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/metrics-api-v2-constraint-violation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/metrics-api-v2-metric-data-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/metrics-api-v2-metric-default-aggregation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/metrics-api-v2-metric-descriptor-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/metrics-api-v2-metric-descriptor-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/metrics-api-v2-metric-dimension-definition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/metrics-api-v2-metric-series-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/metrics-api-v2-metric-series-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/metrics-api-v2-constraint-violation-structure.json)
- [JSON Structure](json-structure/metrics-api-v2-metric-data-structure.json)
- [JSON Structure](json-structure/metrics-api-v2-metric-default-aggregation-structure.json)
- [JSON Structure](json-structure/metrics-api-v2-metric-descriptor-collection-structure.json)
- [JSON Structure](json-structure/metrics-api-v2-metric-descriptor-structure.json)
- [JSON Structure](json-structure/metrics-api-v2-metric-dimension-definition-structure.json)
- [JSON Structure](json-structure/metrics-api-v2-metric-series-collection-structure.json)
- [JSON Structure](json-structure/metrics-api-v2-metric-series-structure.json)
- [Example](examples/metrics-api-v2-constraint-violation-example.json)
- [Example](examples/metrics-api-v2-metric-data-example.json)
- [Example](examples/metrics-api-v2-metric-default-aggregation-example.json)
- [Example](examples/metrics-api-v2-metric-descriptor-collection-example.json)
- [Example](examples/metrics-api-v2-metric-descriptor-example.json)
- [Example](examples/metrics-api-v2-metric-dimension-definition-example.json)
- [Example](examples/metrics-api-v2-metric-series-collection-example.json)
- [Example](examples/metrics-api-v2-metric-series-example.json)

### Dynatrace Log Monitoring API v2

The Dynatrace Log Monitoring API v2 enables ingestion, search, and export of log records within a Dynatrace environment. It allows you to stream log data to the Grail data lakehouse and retrieve logs programmatically for analysis and integration purposes.

- **Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/log-monitoring-v2](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/log-monitoring-v2)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Log Management
- Logs
- Monitoring
- Observability

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/log-monitoring-v2)
- [OpenAPI](openapi/dynatrace-log-monitoring-api-v2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/log-monitoring-api-v2-constraint-violation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/log-monitoring-api-v2-log-aggregate-group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/log-monitoring-api-v2-log-aggregate-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/log-monitoring-api-v2-log-export-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/log-monitoring-api-v2-log-ingest-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/log-monitoring-api-v2-log-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/log-monitoring-api-v2-log-record-search-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/log-monitoring-api-v2-constraint-violation-structure.json)
- [JSON Structure](json-structure/log-monitoring-api-v2-log-aggregate-group-structure.json)
- [JSON Structure](json-structure/log-monitoring-api-v2-log-aggregate-result-structure.json)
- [JSON Structure](json-structure/log-monitoring-api-v2-log-export-result-structure.json)
- [JSON Structure](json-structure/log-monitoring-api-v2-log-ingest-record-structure.json)
- [JSON Structure](json-structure/log-monitoring-api-v2-log-record-search-result-structure.json)
- [JSON Structure](json-structure/log-monitoring-api-v2-log-record-structure.json)
- [Example](examples/log-monitoring-api-v2-constraint-violation-example.json)
- [Example](examples/log-monitoring-api-v2-log-aggregate-group-example.json)
- [Example](examples/log-monitoring-api-v2-log-aggregate-result-example.json)
- [Example](examples/log-monitoring-api-v2-log-export-result-example.json)
- [Example](examples/log-monitoring-api-v2-log-ingest-record-example.json)
- [Example](examples/log-monitoring-api-v2-log-record-example.json)
- [Example](examples/log-monitoring-api-v2-log-record-search-result-example.json)

### Dynatrace Synthetic API v2

The Dynatrace Synthetic API v2 provides programmatic access to synthetic monitoring resources including browser monitors, HTTP monitors, and clickpaths. It allows you to create, update, delete, and retrieve synthetic monitors and their execution results.

- **Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/synthetic-v2](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/synthetic-v2)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Digital Experience
- Observability
- Synthetic Monitoring
- Testing

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/synthetic-v2)
- [API Reference](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/synthetic-v2/synthetic-monitor-execution)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Configuration API

The Dynatrace Configuration API provides access to environment-level configuration settings including alerting profiles, anomaly detection rules, application detection rules, and data privacy settings. It supports GET, POST, PUT, and DELETE operations for managing Dynatrace environment configuration programmatically.

- **Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/configuration-api](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/configuration-api)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/config/v1`

#### Tags

- Configuration
- Management
- Monitoring
- Observability

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/configuration-api)
- [Authentication](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/basics/dynatrace-api-authentication)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Account Management API

The Dynatrace Account Management API allows you to manage your Dynatrace account including users, groups, permissions, environments, and service users. It uses OAuth 2.0 authentication and enables programmatic management of identity and access controls across a Dynatrace account.

- **Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/account-management-api](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/account-management-api)
- **Base URL:** `https://api.dynatrace.com/iam/v1`

#### Tags

- Access Management
- Account Management
- Administration
- Identity

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/account-management-api)
- [Authentication](https://docs.dynatrace.com/docs/dynatrace-api/basics/dynatrace-api-authentication/account-api-authentication)
- [API Reference](https://docs.dynatrace.com/docs/dynatrace-api/account-management-api/user-management-api)
- [OpenAPI](openapi/dynatrace-account-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://docs.dynatrace.com/docs/dynatrace-api/account-management-api/environment-management-api)
- [JSON Schema](json-schema/account-management-api-environment-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/account-management-api-environment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/account-management-api-group-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/account-management-api-group-create-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/account-management-api-group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/account-management-api-permission-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/account-management-api-permission-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/account-management-api-user-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/account-management-api-user-create-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/account-management-api-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/account-management-api-environment-collection-structure.json)
- [JSON Structure](json-structure/account-management-api-environment-structure.json)
- [JSON Structure](json-structure/account-management-api-group-collection-structure.json)
- [JSON Structure](json-structure/account-management-api-group-create-request-structure.json)
- [JSON Structure](json-structure/account-management-api-group-structure.json)
- [JSON Structure](json-structure/account-management-api-permission-collection-structure.json)
- [JSON Structure](json-structure/account-management-api-permission-structure.json)
- [JSON Structure](json-structure/account-management-api-user-collection-structure.json)
- [JSON Structure](json-structure/account-management-api-user-create-request-structure.json)
- [JSON Structure](json-structure/account-management-api-user-structure.json)
- [Example](examples/account-management-api-environment-collection-example.json)
- [Example](examples/account-management-api-environment-example.json)
- [Example](examples/account-management-api-group-collection-example.json)
- [Example](examples/account-management-api-group-create-request-example.json)
- [Example](examples/account-management-api-group-example.json)
- [Example](examples/account-management-api-permission-collection-example.json)
- [Example](examples/account-management-api-permission-example.json)
- [Example](examples/account-management-api-user-collection-example.json)
- [Example](examples/account-management-api-user-create-request-example.json)
- [Example](examples/account-management-api-user-example.json)

### Dynatrace OpenPipeline API

The Dynatrace OpenPipeline API enables configuration of data ingestion pipelines that handle observability, security, and business data from any source or format. It provides endpoints for managing pipeline configurations, ingest sources, routing rules, and processing stages that feed data into the Grail data lakehouse.

- **Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/platform/openpipeline/reference/openpipeline-api](https://docs.dynatrace.com/docs/discover-dynatrace/platform/openpipeline/reference/openpipeline-api)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/platform`

#### Tags

- Data Ingestion
- Data Pipelines
- Observability
- Platform

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/platform/openpipeline/reference/openpipeline-api)
- [API Reference](https://docs.dynatrace.com/docs/discover-dynatrace/platform/openpipeline)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Automation API

The Dynatrace Automation API provides access to the Workflows automation engine, allowing you to create, manage, and execute automated workflows within Dynatrace. It supports orchestrating remediation actions, alert responses, and multi-step automation tasks through the REST API.

- **Human URL:** [https://docs.dynatrace.com/docs/analyze-explore-automate/workflows](https://docs.dynatrace.com/docs/analyze-explore-automate/workflows)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/platform`

#### Tags

- Automation
- Orchestration
- Platform
- Workflows

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/analyze-explore-automate/workflows)
- [API Reference](https://developer.dynatrace.com/develop/workflows/)
- [SDK](https://developer.dynatrace.com/develop/sdks/client-automation/)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Events API v2

The Dynatrace Events API v2 enables you to push custom events into Dynatrace and retrieve event data from your monitored environment. It supports creating deployment events, custom annotations, and information events targeting multiple entities in a single POST request, and events sent via v2 are subject to DDU licensing.

- **Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/events-v2](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/events-v2)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Alerting
- Events
- Monitoring
- Observability

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/events-v2)
- [Release Notes](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/basics/deprecation-migration-guides/events-v1-to-v2)
- [OpenAPI](openapi/dynatrace-events-api-v2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/events-api-v2-constraint-violation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/events-api-v2-entity-stub-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/events-api-v2-event-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/events-api-v2-event-ingest-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/events-api-v2-event-ingest-result-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/events-api-v2-event-ingest-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/events-api-v2-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/events-api-v2-constraint-violation-structure.json)
- [JSON Structure](json-structure/events-api-v2-entity-stub-structure.json)
- [JSON Structure](json-structure/events-api-v2-event-collection-structure.json)
- [JSON Structure](json-structure/events-api-v2-event-ingest-payload-structure.json)
- [JSON Structure](json-structure/events-api-v2-event-ingest-result-item-structure.json)
- [JSON Structure](json-structure/events-api-v2-event-ingest-result-structure.json)
- [JSON Structure](json-structure/events-api-v2-event-structure.json)
- [Example](examples/events-api-v2-constraint-violation-example.json)
- [Example](examples/events-api-v2-entity-stub-example.json)
- [Example](examples/events-api-v2-event-collection-example.json)
- [Example](examples/events-api-v2-event-example.json)
- [Example](examples/events-api-v2-event-ingest-payload-example.json)
- [Example](examples/events-api-v2-event-ingest-result-example.json)
- [Example](examples/events-api-v2-event-ingest-result-item-example.json)

### Dynatrace Problems API v2

The Dynatrace Problems API v2 allows you to query and manage detected problems within a Dynatrace environment. It provides endpoints for listing open and closed problems, retrieving problem details including root cause analysis, and closing problems programmatically. It improves on v1 by supporting entity selectors for multi-entity targeting.

- **Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/problems-v2](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/problems-v2)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Alerting
- Monitoring
- Observability
- Problems

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/problems-v2)
- [Release Notes](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/basics/deprecation-migration-guides/problems-v1-to-v2)
- [OpenAPI](openapi/dynatrace-problems-api-v2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/dynatrace-problems-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/problems-api-v2-alerting-profile-stub-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/problems-api-v2-comment-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/problems-api-v2-comment-request-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/problems-api-v2-comment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/problems-api-v2-constraint-violation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/problems-api-v2-entity-stub-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/problems-api-v2-management-zone-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/problems-api-v2-problem-close-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/problems-api-v2-problem-close-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/problems-api-v2-problem-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/problems-api-v2-problem-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/problems-api-v2-alerting-profile-stub-structure.json)
- [JSON Structure](json-structure/problems-api-v2-comment-collection-structure.json)
- [JSON Structure](json-structure/problems-api-v2-comment-request-body-structure.json)
- [JSON Structure](json-structure/problems-api-v2-comment-structure.json)
- [JSON Structure](json-structure/problems-api-v2-constraint-violation-structure.json)
- [JSON Structure](json-structure/problems-api-v2-entity-stub-structure.json)
- [JSON Structure](json-structure/problems-api-v2-management-zone-structure.json)
- [JSON Structure](json-structure/problems-api-v2-problem-close-request-structure.json)
- [JSON Structure](json-structure/problems-api-v2-problem-close-result-structure.json)
- [JSON Structure](json-structure/problems-api-v2-problem-collection-structure.json)
- [JSON Structure](json-structure/problems-api-v2-problem-structure.json)
- [Example](examples/problems-api-v2-alerting-profile-stub-example.json)
- [Example](examples/problems-api-v2-comment-collection-example.json)
- [Example](examples/problems-api-v2-comment-example.json)
- [Example](examples/problems-api-v2-comment-request-body-example.json)
- [Example](examples/problems-api-v2-constraint-violation-example.json)
- [Example](examples/problems-api-v2-entity-stub-example.json)
- [Example](examples/problems-api-v2-management-zone-example.json)
- [Example](examples/problems-api-v2-problem-close-request-example.json)
- [Example](examples/problems-api-v2-problem-close-result-example.json)
- [Example](examples/problems-api-v2-problem-collection-example.json)
- [Example](examples/problems-api-v2-problem-example.json)

### Dynatrace Entities API v2

The Dynatrace Entities API v2 enables querying of monitored entities such as services, hosts, processes, and applications within a Dynatrace environment. It supports filtering entities by type, tags, and management zones, and returns entity relationships and properties for topology analysis and dependency mapping.

- **Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/entity-v2](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/entity-v2)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Entities
- Monitoring
- Observability
- Topology

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/entity-v2)
- [OpenAPI](openapi/dynatrace-entities-api-v2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/entities-api-v2-constraint-violation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/entities-api-v2-entity-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/entities-api-v2-entity-lookup-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/entities-api-v2-entity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/entities-api-v2-entity-tag-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/entities-api-v2-entity-type-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/entities-api-v2-entity-type-property-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/entities-api-v2-entity-type-relationship-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/entities-api-v2-entity-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/entities-api-v2-management-zone-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/entities-api-v2-constraint-violation-structure.json)
- [JSON Structure](json-structure/entities-api-v2-entity-collection-structure.json)
- [JSON Structure](json-structure/entities-api-v2-entity-lookup-request-structure.json)
- [JSON Structure](json-structure/entities-api-v2-entity-structure.json)
- [JSON Structure](json-structure/entities-api-v2-entity-tag-structure.json)
- [JSON Structure](json-structure/entities-api-v2-entity-type-collection-structure.json)
- [JSON Structure](json-structure/entities-api-v2-entity-type-property-structure.json)
- [JSON Structure](json-structure/entities-api-v2-entity-type-relationship-structure.json)
- [JSON Structure](json-structure/entities-api-v2-entity-type-structure.json)
- [JSON Structure](json-structure/entities-api-v2-management-zone-structure.json)
- [Example](examples/entities-api-v2-constraint-violation-example.json)
- [Example](examples/entities-api-v2-entity-collection-example.json)
- [Example](examples/entities-api-v2-entity-example.json)
- [Example](examples/entities-api-v2-entity-lookup-request-example.json)
- [Example](examples/entities-api-v2-entity-tag-example.json)
- [Example](examples/entities-api-v2-entity-type-collection-example.json)
- [Example](examples/entities-api-v2-entity-type-example.json)
- [Example](examples/entities-api-v2-entity-type-property-example.json)
- [Example](examples/entities-api-v2-entity-type-relationship-example.json)
- [Example](examples/entities-api-v2-management-zone-example.json)

### Dynatrace Settings API 2.0

The Dynatrace Settings API 2.0 is the modern, schema-driven configuration API for managing Dynatrace environment settings objects. It replaces portions of the Configuration API v1 and provides a unified approach to reading and writing anomaly detection, alerting, and platform settings through versioned schema definitions.

- **Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/settings-v2](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/settings-v2)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Configuration
- Management
- Observability
- Settings

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/settings-v2)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Extensions API 2.0

The Dynatrace Extensions API 2.0 provides endpoints for managing monitoring extensions including uploading, activating, configuring, and removing extensions within a Dynatrace environment. It supports the Extensions 2.0 framework used for custom data collection and integration with third-party systems and technologies.

- **Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/extensions-v2](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/extensions-v2)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Extensions
- Integrations
- Monitoring
- Observability

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/extensions-v2)
- [API Reference](https://docs.dynatrace.com/docs/ingest-from/extensions/manage-extensions)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace DQL/Grail Query API

The Dynatrace DQL/Grail Query API enables execution of DQL (Dynatrace Query Language) queries against the Grail data lakehouse via REST. Queries execute asynchronously using a POST to initiate and GET to poll for results, providing programmatic access to unified observability, security, and business data stored in Grail for custom analytics and automated workflows.

- **Human URL:** [https://docs.dynatrace.com/docs/platform/grail/dynatrace-query-language/api](https://docs.dynatrace.com/docs/platform/grail/dynatrace-query-language/api)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/platform`

#### Tags

- Analytics
- DQL
- Grail
- Observability
- Query

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/platform/grail/dynatrace-query-language/api)
- [API Reference](https://docs.dynatrace.com/docs/platform/grail/dynatrace-query-language)
- [SDK](https://developer.dynatrace.com/develop/sdks/client-query/)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Access Tokens API v2

The Dynatrace Access Tokens API v2 allows you to create, list, update, and delete API access tokens and ActiveGate tokens within a Dynatrace environment. It provides fine-grained scope management for controlling access to specific product functionality, and supports both environment-level API tokens and ActiveGate connection tokens.

- **Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/tokens-v2](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/tokens-v2)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Access Management
- Authentication
- Security
- Tokens

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/tokens-v2)
- [API Reference](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/tokens-v2/api-tokens)
- [Getting Started](https://docs.dynatrace.com/docs/manage/identity-access-management/access-tokens-and-oauth-clients/access-tokens)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Service-Level Objectives API

The Dynatrace Service-Level Objectives API is a management API for creating, editing, listing, deleting, and evaluating SLOs and SLO templates within a Dynatrace environment. It enables programmatic definition of reliability targets and automated evaluation of service-level compliance based on Dynatrace monitoring data.

- **Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/service-level-objectives](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/service-level-objectives)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Observability
- Reliability
- Service Level Objectives
- SLO

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/service-level-objectives)
- [API Reference](https://docs.dynatrace.com/docs/deliver/service-level-objectives)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Releases API

The Dynatrace Releases API provides an overview of releases deployed in your monitored environment. It allows you to retrieve information about software releases, deployment versions, and release stages, enabling automated tracking of deployment activity and version management across monitored entities.

- **Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/releaseapi](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/releaseapi)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Deployment
- Observability
- Releases
- Version Management

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/releaseapi)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Network Zones API

The Dynatrace Network Zones API enables you to manage network zones within a Dynatrace environment. It provides endpoints for listing all network zones, retrieving zone details including OneAgent counts, creating and updating zone configurations, deleting zones, and getting global network zone configuration settings.

- **Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/network-zones](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/network-zones)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Infrastructure
- Monitoring
- Network Zones
- Networking

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/network-zones)
- [API Reference](https://docs.dynatrace.com/docs/manage/network-zones/network-zones-basic-info)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Deployment API

The Dynatrace Deployment API provides endpoints for downloading OneAgent and ActiveGate installers, listing available installer versions, and retrieving ActiveGate endpoint information. It enables automated deployment and upgrade of monitoring agents across your infrastructure using the InstallerDownload token scope.

- **Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/deployment](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/deployment)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- ActiveGate
- Deployment
- Installation
- OneAgent

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/deployment)
- [API Reference](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/deployment/oneagent)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Audit Logs API

The Dynatrace Audit Logs API provides access to audit-related events within a Dynatrace environment including logins, logouts, configuration changes, and API token modifications. Audit logs are retained for 30 days and support filtering by event type, user, and time range for security monitoring and compliance purposes.

- **Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/audit-logs](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/audit-logs)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Audit Logs
- Compliance
- Governance
- Security

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/audit-logs)
- [API Reference](https://docs.dynatrace.com/docs/manage/data-privacy-and-security/configuration/audit-logs-api)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Business Events API v2

The Dynatrace Business Events API v2 enables ingestion of business event data in JSON format into Dynatrace via the bizevents/ingest endpoint. It supports business-grade reporting and analytics through the Grail data lakehouse with lossless data prioritization, deep data capture from in-flight payloads, and powerful ad-hoc queries for business observability use cases.

- **Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/business-analytics-v2](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/business-analytics-v2)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Business Analytics
- Business Events
- Business Intelligence
- Observability

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/business-analytics-v2)
- [API Reference](https://docs.dynatrace.com/docs/observe/business-observability/bo-api-ingest)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Application Security API

The Dynatrace Application Security API provides endpoints for querying vulnerabilities, vulnerability details, remediation items, vulnerable functions, and security attacks within a Dynatrace environment. It includes the Vulnerabilities API, Attacks API, and Davis Security Advisor API for comprehensive runtime application security analysis and threat detection.

- **Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/application-security/vulnerabilities](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/application-security/vulnerabilities)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Application Security
- Runtime Protection
- Security
- Vulnerabilities

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/application-security/vulnerabilities)
- [API Reference](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/application-security/attacks)
- [API Reference](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/application-security/davis-security-advice)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Custom Tags API

The Dynatrace Custom Tags API allows you to manage custom tags on monitored entities within a Dynatrace environment. It provides endpoints for reading, adding, and removing tags from entities such as hosts, services, processes, and applications, enabling automated organization and categorization of monitored resources.

- **Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/custom-tags](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/custom-tags)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Entities
- Metadata
- Monitoring

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/custom-tags)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace ActiveGate API

The Dynatrace ActiveGate API enables you to view and manage ActiveGate configurations within a Dynatrace environment. It provides endpoints for listing ActiveGates, retrieving ActiveGate details, managing auto-update configurations, and monitoring auto-update job status for Environment ActiveGates.

- **Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/activegates](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/activegates)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- ActiveGate
- Deployment
- Infrastructure
- Monitoring

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/activegates)
- [API Reference](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/tokens-v2/activegate-tokens)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Credential Vault API

The Dynatrace Credential Vault API enables management of credentials used for synthetic browser and HTTP monitors within a Dynatrace environment. It supports creating, listing, updating, and deleting credential sets of type certificate, public certificate, token, and username/password for use in synthetic monitoring configurations.

- **Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/credential-vault](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/credential-vault)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Credentials
- Secrets
- Security
- Synthetic Monitoring

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/credential-vault)
- [API Reference](https://docs.dynatrace.com/docs/manage/credential-vault)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Document API

The Dynatrace Document API provides a platform service for creating, managing, and sharing documents such as dashboards, notebooks, and launchpads within Dynatrace. It persists content-agnostic documents with metadata and supports querying by document type, enabling programmatic management of analytical and visualization assets.

- **Human URL:** [https://docs.dynatrace.com/docs/analyze-explore-automate/dashboards-and-notebooks/document-api](https://docs.dynatrace.com/docs/analyze-explore-automate/dashboards-and-notebooks/document-api)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/platform/document/v1`

#### Tags

- Dashboards
- Documents
- Notebooks
- Platform

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/analyze-explore-automate/dashboards-and-notebooks/document-api)
- [SDK](https://developer.dynatrace.com/develop/sdks/client-document/)
- [API Reference](https://developer.dynatrace.com/plan/platform-services/document-service/)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Grail Bucket Management API

The Dynatrace Grail Bucket Management API provides a public API for managing storage buckets within the Grail data lakehouse. It supports creating, updating, deleting, and truncating buckets for organizing logs, events, and business events data with configurable retention periods between 1 and 3657 days.

- **Human URL:** [https://developer.dynatrace.com/develop/sdks/client-bucket-management/](https://developer.dynatrace.com/develop/sdks/client-bucket-management/)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/platform`

#### Tags

- Data Management
- Grail
- Platform
- Storage

#### Properties

- [Documentation](https://developer.dynatrace.com/develop/sdks/client-bucket-management/)
- [API Reference](https://docs.dynatrace.com/docs/platform/grail/organize-data)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Davis AI API

The Dynatrace Davis AI API provides access to the Davis predictive and causal AI platform service for customized AI/ML analysis. It delivers time series forecasting, anomaly detection model training, and automated monitoring of metric behavior changes, enabling application creators to build intelligent automation and analytics within Dynatrace Apps.

- **Human URL:** [https://developer.dynatrace.com/develop/sdks/client-davis-analyzers/](https://developer.dynatrace.com/develop/sdks/client-davis-analyzers/)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/platform`

#### Tags

- Causal Analysis
- Davis AI
- Machine Learning
- Platform
- Predictive Analytics

#### Properties

- [Documentation](https://developer.dynatrace.com/develop/sdks/client-davis-analyzers/)
- [Getting Started](https://developer.dynatrace.com/develop/forecast-with-davis-ai/)
- [API Reference](https://docs.dynatrace.com/docs/discover-dynatrace/platform/davis-ai)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Hub API

The Dynatrace Hub API provides programmatic access to the Dynatrace Hub catalog content including apps, extensions, and technologies in the context of the current environment. It supports listing and retrieving details for apps, extensions, technologies, and Hub categories for building custom catalog integrations and discovery experiences.

- **Human URL:** [https://developer.dynatrace.com/develop/sdks/client-hub/](https://developer.dynatrace.com/develop/sdks/client-hub/)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/platform`

#### Tags

- Apps
- Catalog
- Extensions
- Hub
- Platform

#### Properties

- [Documentation](https://developer.dynatrace.com/develop/sdks/client-hub/)
- [API Reference](https://docs.dynatrace.com/docs/manage/hub)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace OneAgent on a Host API

The Dynatrace OneAgent on a Host API enables you to check the configuration and status of OneAgent instances deployed on your hosts. It provides endpoints for listing hosts with OneAgent details, retrieving agent version information, and monitoring agent health and connectivity within a Dynatrace environment.

- **Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/oneagent-on-host](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/oneagent-on-host)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/api/v2`

#### Tags

- Deployment
- Host Monitoring
- Infrastructure
- OneAgent

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/oneagent-on-host)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynatrace Platform Management API

The Dynatrace Platform Management API provides basic read-only information about the currently logged-in environment including environment settings, license information, and permissions. It is a core platform service used for querying environment metadata and configuration context within Dynatrace Apps and automation workflows.

- **Human URL:** [https://developer.dynatrace.com/develop/sdks/client-platform-management-service/](https://developer.dynatrace.com/develop/sdks/client-platform-management-service/)
- **Base URL:** `https://mySampleEnv.live.dynatrace.com/platform`

#### Tags

- Administration
- Environment Management
- Platform
- Settings

#### Properties

- [Documentation](https://developer.dynatrace.com/develop/sdks/client-platform-management-service/)
- [API Reference](https://developer.dynatrace.com/plan/platform-services/platform-management-service/)
- [Postman Collection](collections/dynatrace-account-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-account-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-entities-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-entities-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-events-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-events-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-log-monitoring-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-log-monitoring-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-metrics-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-metrics-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dynatrace-problems-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynatrace-problems-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/dynatrace)
- [Portal](https://www.dynatrace.com/support/help/dynatrace-api)
- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api)
- [Authentication](https://www.dynatrace.com/support/help/dynatrace-api/basics/dynatrace-api-authentication)
- [Getting Started](https://www.dynatrace.com/support/help/dynatrace-api/basics)
- [API Reference](https://www.dynatrace.com/support/help/dynatrace-api/basics/dynatrace-api-response-codes)
- [Changelog](https://docs.dynatrace.com/docs/whats-new/dynatrace-api)
- [Terms of Service](https://www.dynatrace.com/company/trust-center/terms/)
- [Privacy Policy](https://www.dynatrace.com/company/trust-center/privacy/)
- [Support](https://www.dynatrace.com/support/)
- [Pricing](https://www.dynatrace.com/pricing/)
- [Sign Up](https://www.dynatrace.com/signup/)
- [Support](https://community.dynatrace.com/)
- [Blog](https://community.dynatrace.com/t5/Developer-Blog/bg-p/dev_blog)
- [Status Page](https://dynatrace.status.io/)
- [GitHub Organization](https://github.com/Dynatrace)
- [Developer Portal](https://developer.dynatrace.com/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/dynatrace)
- [YouTube](https://www.youtube.com/c/dynatrace)
- [JSON Schema](json-schema/dynatrace-metric-series-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/dynatrace-problem-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/dynatrace-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [SDK](https://developer.dynatrace.com/develop/sdks/)
- [Authentication](https://developer.dynatrace.com/develop/access-platform-apis-from-outside/)
- [Security](https://docs.dynatrace.com/docs/manage/identity-access-management)
- [GitHub Repository](https://github.com/Dynatrace/dynatrace-api)
- [Marketplace](https://www.dynatrace.com/hub/)
- [Release Notes](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/basics/deprecation-migration-guides)
- [Documentation](https://developer.dynatrace.com/plan/platform-services/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [C L I](https://github.com/Dynatrace/dynatrace-configuration-as-code)
- [SDK](https://github.com/Dynatrace/OneAgent-SDK-for-Java)
- [SDK](https://github.com/Dynatrace/OneAgent-SDK-for-Python)
- [SDK](https://github.com/Dynatrace/OneAgent-SDK-for-NodeJs)
- [SDK](https://github.com/Dynatrace/OneAgent-SDK-for-dotnet)
- [SDK](https://github.com/Dynatrace/OneAgent-SDK-for-C)
- [SDK](https://github.com/Dynatrace/swift-mobile-sdk)
- [Code Examples](https://github.com/Dynatrace/Dynatrace-workflow-samples)
- [Code Examples](https://github.com/Dynatrace/snippets)
- [Code Examples](https://github.com/Dynatrace/community-examples)
- [Tutorials](https://github.com/Dynatrace/Dynatrace-Tutorial)
- [Spectral Rules](rules/dynatrace-spectral-rules.yml)
- [Vocabulary](vocabulary/dynatrace-vocabulary.yaml)
- [JSON-LD](json-ld/dynatrace-account-management-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/dynatrace-dynatrace-metric-series-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/dynatrace-dynatrace-problem-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/dynatrace-entities-api-v2-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/dynatrace-events-api-v2-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/dynatrace-log-monitoring-api-v2-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/dynatrace-metrics-api-v2-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/dynatrace-problems-api-v2-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/dynatrace-problems-entity-ref-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/dynatrace-problems-impacted-entity-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/dynatrace-problems-problem-details-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/dynatrace-problems-problem-notification-payload-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/dynatrace-problems-webhook-header-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/dynatrace-problems-webhook-notification-config-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
