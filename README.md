# Dynatrace (dynatrace)
Dynatrace is a software intelligence platform that provides application performance monitoring, artificial intelligence for operations, cloud infrastructure monitoring, and digital experience management.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AI Operations, Analytics, APM, Application Performance Monitoring, Application Security, Automation, Cloud Monitoring, Digital Experience Management, Intelligence, Observability

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-18

## APIs

### Dynatrace Environment API
The Dynatrace Environment API provides access to monitoring data and configuration settings for a specific Dynatrace environment. It includes endpoints for metrics, problems, events, logs, entities, settings, and synthetic monitoring, and is the primary API for interacting with observability data within a Dynatrace environment.

**Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api](https://docs.dynatrace.com/docs/dynatrace-api/environment-api)

#### Tags:

 - Analytics, Automation, Intelligence, Monitoring, Observability

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api)
- [Authentication](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/basics/dynatrace-api-authentication)
- [SDK](https://developer.dynatrace.com/develop/sdks/client-classic-environment-v2/)

### Dynatrace Metrics API v2
The Dynatrace Metrics API v2 allows you to query, ingest, and manage time-series metric data within a Dynatrace environment. It supports retrieving metric descriptors, querying data points with flexible selectors, and ingesting custom metrics from external sources.

**Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/metric-v2](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/metric-v2)

#### Tags:

 - Metrics, Monitoring, Observability, Time Series

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/metric-v2)
- [APIReference](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/metric-v2/best-practices)
- [OpenAPI](openapi/dynatrace-metrics-api-v2-openapi.yml)
- [JSONSchema](json-schema/metrics-api-v2-constraint-violation-schema.json)
- [JSONSchema](json-schema/metrics-api-v2-metric-data-schema.json)
- [JSONSchema](json-schema/metrics-api-v2-metric-default-aggregation-schema.json)
- [JSONSchema](json-schema/metrics-api-v2-metric-descriptor-collection-schema.json)
- [JSONSchema](json-schema/metrics-api-v2-metric-descriptor-schema.json)
- [JSONSchema](json-schema/metrics-api-v2-metric-dimension-definition-schema.json)
- [JSONSchema](json-schema/metrics-api-v2-metric-series-collection-schema.json)
- [JSONSchema](json-schema/metrics-api-v2-metric-series-schema.json)
- [JSONStructure](json-structure/metrics-api-v2-constraint-violation-structure.json)
- [JSONStructure](json-structure/metrics-api-v2-metric-data-structure.json)
- [JSONStructure](json-structure/metrics-api-v2-metric-default-aggregation-structure.json)
- [JSONStructure](json-structure/metrics-api-v2-metric-descriptor-collection-structure.json)
- [JSONStructure](json-structure/metrics-api-v2-metric-descriptor-structure.json)
- [JSONStructure](json-structure/metrics-api-v2-metric-dimension-definition-structure.json)
- [JSONStructure](json-structure/metrics-api-v2-metric-series-collection-structure.json)
- [JSONStructure](json-structure/metrics-api-v2-metric-series-structure.json)
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

**Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/log-monitoring-v2](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/log-monitoring-v2)

#### Tags:

 - Log Management, Logs, Monitoring, Observability

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/log-monitoring-v2)
- [OpenAPI](openapi/dynatrace-log-monitoring-api-v2-openapi.yml)
- [JSONSchema](json-schema/log-monitoring-api-v2-constraint-violation-schema.json)
- [JSONSchema](json-schema/log-monitoring-api-v2-log-aggregate-group-schema.json)
- [JSONSchema](json-schema/log-monitoring-api-v2-log-aggregate-result-schema.json)
- [JSONSchema](json-schema/log-monitoring-api-v2-log-export-result-schema.json)
- [JSONSchema](json-schema/log-monitoring-api-v2-log-ingest-record-schema.json)
- [JSONSchema](json-schema/log-monitoring-api-v2-log-record-schema.json)
- [JSONSchema](json-schema/log-monitoring-api-v2-log-record-search-result-schema.json)
- [JSONStructure](json-structure/log-monitoring-api-v2-constraint-violation-structure.json)
- [JSONStructure](json-structure/log-monitoring-api-v2-log-aggregate-group-structure.json)
- [JSONStructure](json-structure/log-monitoring-api-v2-log-aggregate-result-structure.json)
- [JSONStructure](json-structure/log-monitoring-api-v2-log-export-result-structure.json)
- [JSONStructure](json-structure/log-monitoring-api-v2-log-ingest-record-structure.json)
- [JSONStructure](json-structure/log-monitoring-api-v2-log-record-search-result-structure.json)
- [JSONStructure](json-structure/log-monitoring-api-v2-log-record-structure.json)
- [Example](examples/log-monitoring-api-v2-constraint-violation-example.json)
- [Example](examples/log-monitoring-api-v2-log-aggregate-group-example.json)
- [Example](examples/log-monitoring-api-v2-log-aggregate-result-example.json)
- [Example](examples/log-monitoring-api-v2-log-export-result-example.json)
- [Example](examples/log-monitoring-api-v2-log-ingest-record-example.json)
- [Example](examples/log-monitoring-api-v2-log-record-example.json)
- [Example](examples/log-monitoring-api-v2-log-record-search-result-example.json)

### Dynatrace Synthetic API v2
The Dynatrace Synthetic API v2 provides programmatic access to synthetic monitoring resources including browser monitors, HTTP monitors, and clickpaths. It allows you to create, update, delete, and retrieve synthetic monitors and their execution results.

**Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/synthetic-v2](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/synthetic-v2)

#### Tags:

 - Digital Experience, Observability, Synthetic Monitoring, Testing

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/synthetic-v2)
- [APIReference](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/synthetic-v2/synthetic-monitor-execution)

### Dynatrace Configuration API
The Dynatrace Configuration API provides access to environment-level configuration settings including alerting profiles, anomaly detection rules, application detection rules, and data privacy settings. It supports GET, POST, PUT, and DELETE operations for managing Dynatrace environment configuration programmatically.

**Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/configuration-api](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/configuration-api)

#### Tags:

 - Configuration, Management, Monitoring, Observability

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/configuration-api)
- [Authentication](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/basics/dynatrace-api-authentication)

### Dynatrace Account Management API
The Dynatrace Account Management API allows you to manage your Dynatrace account including users, groups, permissions, environments, and service users. It uses OAuth 2.0 authentication and enables programmatic management of identity and access controls across a Dynatrace account.

**Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/account-management-api](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/account-management-api)

#### Tags:

 - Access Management, Account Management, Administration, Identity

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/account-management-api)
- [Authentication](https://docs.dynatrace.com/docs/dynatrace-api/basics/dynatrace-api-authentication/account-api-authentication)
- [APIReference](https://docs.dynatrace.com/docs/dynatrace-api/account-management-api/user-management-api)
- [OpenAPI](openapi/dynatrace-account-management-api-openapi.yml)
- [GettingStarted](https://docs.dynatrace.com/docs/dynatrace-api/account-management-api/environment-management-api)
- [JSONSchema](json-schema/account-management-api-environment-collection-schema.json)
- [JSONSchema](json-schema/account-management-api-environment-schema.json)
- [JSONSchema](json-schema/account-management-api-group-collection-schema.json)
- [JSONSchema](json-schema/account-management-api-group-create-request-schema.json)
- [JSONSchema](json-schema/account-management-api-group-schema.json)
- [JSONSchema](json-schema/account-management-api-permission-collection-schema.json)
- [JSONSchema](json-schema/account-management-api-permission-schema.json)
- [JSONSchema](json-schema/account-management-api-user-collection-schema.json)
- [JSONSchema](json-schema/account-management-api-user-create-request-schema.json)
- [JSONSchema](json-schema/account-management-api-user-schema.json)
- [JSONStructure](json-structure/account-management-api-environment-collection-structure.json)
- [JSONStructure](json-structure/account-management-api-environment-structure.json)
- [JSONStructure](json-structure/account-management-api-group-collection-structure.json)
- [JSONStructure](json-structure/account-management-api-group-create-request-structure.json)
- [JSONStructure](json-structure/account-management-api-group-structure.json)
- [JSONStructure](json-structure/account-management-api-permission-collection-structure.json)
- [JSONStructure](json-structure/account-management-api-permission-structure.json)
- [JSONStructure](json-structure/account-management-api-user-collection-structure.json)
- [JSONStructure](json-structure/account-management-api-user-create-request-structure.json)
- [JSONStructure](json-structure/account-management-api-user-structure.json)
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

**Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/platform/openpipeline/reference/openpipeline-api](https://docs.dynatrace.com/docs/discover-dynatrace/platform/openpipeline/reference/openpipeline-api)

#### Tags:

 - Data Ingestion, Data Pipelines, Observability, Platform

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/platform/openpipeline/reference/openpipeline-api)
- [APIReference](https://docs.dynatrace.com/docs/discover-dynatrace/platform/openpipeline)

### Dynatrace Automation API
The Dynatrace Automation API provides access to the Workflows automation engine, allowing you to create, manage, and execute automated workflows within Dynatrace. It supports orchestrating remediation actions, alert responses, and multi-step automation tasks through the REST API.

**Human URL:** [https://docs.dynatrace.com/docs/analyze-explore-automate/workflows](https://docs.dynatrace.com/docs/analyze-explore-automate/workflows)

#### Tags:

 - Automation, Orchestration, Platform, Workflows

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/analyze-explore-automate/workflows)
- [APIReference](https://developer.dynatrace.com/develop/workflows/)
- [SDK](https://developer.dynatrace.com/develop/sdks/client-automation/)

### Dynatrace Events API v2
The Dynatrace Events API v2 enables you to push custom events into Dynatrace and retrieve event data from your monitored environment. It supports creating deployment events, custom annotations, and information events targeting multiple entities in a single POST request, and events sent via v2 are subject to DDU licensing.

**Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/events-v2](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/events-v2)

#### Tags:

 - Alerting, Events, Monitoring, Observability

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/events-v2)
- [ReleaseNotes](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/basics/deprecation-migration-guides/events-v1-to-v2)
- [OpenAPI](openapi/dynatrace-events-api-v2-openapi.yml)
- [JSONSchema](json-schema/events-api-v2-constraint-violation-schema.json)
- [JSONSchema](json-schema/events-api-v2-entity-stub-schema.json)
- [JSONSchema](json-schema/events-api-v2-event-collection-schema.json)
- [JSONSchema](json-schema/events-api-v2-event-ingest-payload-schema.json)
- [JSONSchema](json-schema/events-api-v2-event-ingest-result-item-schema.json)
- [JSONSchema](json-schema/events-api-v2-event-ingest-result-schema.json)
- [JSONSchema](json-schema/events-api-v2-event-schema.json)
- [JSONStructure](json-structure/events-api-v2-constraint-violation-structure.json)
- [JSONStructure](json-structure/events-api-v2-entity-stub-structure.json)
- [JSONStructure](json-structure/events-api-v2-event-collection-structure.json)
- [JSONStructure](json-structure/events-api-v2-event-ingest-payload-structure.json)
- [JSONStructure](json-structure/events-api-v2-event-ingest-result-item-structure.json)
- [JSONStructure](json-structure/events-api-v2-event-ingest-result-structure.json)
- [JSONStructure](json-structure/events-api-v2-event-structure.json)
- [Example](examples/events-api-v2-constraint-violation-example.json)
- [Example](examples/events-api-v2-entity-stub-example.json)
- [Example](examples/events-api-v2-event-collection-example.json)
- [Example](examples/events-api-v2-event-example.json)
- [Example](examples/events-api-v2-event-ingest-payload-example.json)
- [Example](examples/events-api-v2-event-ingest-result-example.json)
- [Example](examples/events-api-v2-event-ingest-result-item-example.json)

### Dynatrace Problems API v2
The Dynatrace Problems API v2 allows you to query and manage detected problems within a Dynatrace environment. It provides endpoints for listing open and closed problems, retrieving problem details including root cause analysis, and closing problems programmatically. It improves on v1 by supporting entity selectors for multi-entity targeting.

**Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/problems-v2](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/problems-v2)

#### Tags:

 - Alerting, Monitoring, Observability, Problems

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/problems-v2)
- [ReleaseNotes](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/basics/deprecation-migration-guides/problems-v1-to-v2)
- [OpenAPI](openapi/dynatrace-problems-api-v2-openapi.yml)
- [AsyncAPI](asyncapi/dynatrace-problems-asyncapi.yml)
- [JSONSchema](json-schema/problems-api-v2-alerting-profile-stub-schema.json)
- [JSONSchema](json-schema/problems-api-v2-comment-collection-schema.json)
- [JSONSchema](json-schema/problems-api-v2-comment-request-body-schema.json)
- [JSONSchema](json-schema/problems-api-v2-comment-schema.json)
- [JSONSchema](json-schema/problems-api-v2-constraint-violation-schema.json)
- [JSONSchema](json-schema/problems-api-v2-entity-stub-schema.json)
- [JSONSchema](json-schema/problems-api-v2-management-zone-schema.json)
- [JSONSchema](json-schema/problems-api-v2-problem-close-request-schema.json)
- [JSONSchema](json-schema/problems-api-v2-problem-close-result-schema.json)
- [JSONSchema](json-schema/problems-api-v2-problem-collection-schema.json)
- [JSONSchema](json-schema/problems-api-v2-problem-schema.json)
- [JSONStructure](json-structure/problems-api-v2-alerting-profile-stub-structure.json)
- [JSONStructure](json-structure/problems-api-v2-comment-collection-structure.json)
- [JSONStructure](json-structure/problems-api-v2-comment-request-body-structure.json)
- [JSONStructure](json-structure/problems-api-v2-comment-structure.json)
- [JSONStructure](json-structure/problems-api-v2-constraint-violation-structure.json)
- [JSONStructure](json-structure/problems-api-v2-entity-stub-structure.json)
- [JSONStructure](json-structure/problems-api-v2-management-zone-structure.json)
- [JSONStructure](json-structure/problems-api-v2-problem-close-request-structure.json)
- [JSONStructure](json-structure/problems-api-v2-problem-close-result-structure.json)
- [JSONStructure](json-structure/problems-api-v2-problem-collection-structure.json)
- [JSONStructure](json-structure/problems-api-v2-problem-structure.json)
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

**Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/entity-v2](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/entity-v2)

#### Tags:

 - Entities, Monitoring, Observability, Topology

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/entity-v2)
- [OpenAPI](openapi/dynatrace-entities-api-v2-openapi.yml)
- [JSONSchema](json-schema/entities-api-v2-constraint-violation-schema.json)
- [JSONSchema](json-schema/entities-api-v2-entity-collection-schema.json)
- [JSONSchema](json-schema/entities-api-v2-entity-lookup-request-schema.json)
- [JSONSchema](json-schema/entities-api-v2-entity-schema.json)
- [JSONSchema](json-schema/entities-api-v2-entity-tag-schema.json)
- [JSONSchema](json-schema/entities-api-v2-entity-type-collection-schema.json)
- [JSONSchema](json-schema/entities-api-v2-entity-type-property-schema.json)
- [JSONSchema](json-schema/entities-api-v2-entity-type-relationship-schema.json)
- [JSONSchema](json-schema/entities-api-v2-entity-type-schema.json)
- [JSONSchema](json-schema/entities-api-v2-management-zone-schema.json)
- [JSONStructure](json-structure/entities-api-v2-constraint-violation-structure.json)
- [JSONStructure](json-structure/entities-api-v2-entity-collection-structure.json)
- [JSONStructure](json-structure/entities-api-v2-entity-lookup-request-structure.json)
- [JSONStructure](json-structure/entities-api-v2-entity-structure.json)
- [JSONStructure](json-structure/entities-api-v2-entity-tag-structure.json)
- [JSONStructure](json-structure/entities-api-v2-entity-type-collection-structure.json)
- [JSONStructure](json-structure/entities-api-v2-entity-type-property-structure.json)
- [JSONStructure](json-structure/entities-api-v2-entity-type-relationship-structure.json)
- [JSONStructure](json-structure/entities-api-v2-entity-type-structure.json)
- [JSONStructure](json-structure/entities-api-v2-management-zone-structure.json)
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

**Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/settings-v2](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/settings-v2)

#### Tags:

 - Configuration, Management, Observability, Settings

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/settings-v2)

### Dynatrace Extensions API 2.0
The Dynatrace Extensions API 2.0 provides endpoints for managing monitoring extensions including uploading, activating, configuring, and removing extensions within a Dynatrace environment. It supports the Extensions 2.0 framework used for custom data collection and integration with third-party systems and technologies.

**Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/extensions-v2](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/extensions-v2)

#### Tags:

 - Extensions, Integrations, Monitoring, Observability

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/extensions-v2)
- [APIReference](https://docs.dynatrace.com/docs/ingest-from/extensions/manage-extensions)

### Dynatrace DQL/Grail Query API
The Dynatrace DQL/Grail Query API enables execution of DQL (Dynatrace Query Language) queries against the Grail data lakehouse via REST. Queries execute asynchronously using a POST to initiate and GET to poll for results, providing programmatic access to unified observability, security, and business data stored in Grail for custom analytics and automated workflows.

**Human URL:** [https://docs.dynatrace.com/docs/platform/grail/dynatrace-query-language/api](https://docs.dynatrace.com/docs/platform/grail/dynatrace-query-language/api)

#### Tags:

 - Analytics, DQL, Grail, Observability, Query

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/platform/grail/dynatrace-query-language/api)
- [APIReference](https://docs.dynatrace.com/docs/platform/grail/dynatrace-query-language)
- [SDK](https://developer.dynatrace.com/develop/sdks/client-query/)

### Dynatrace Access Tokens API v2
The Dynatrace Access Tokens API v2 allows you to create, list, update, and delete API access tokens and ActiveGate tokens within a Dynatrace environment. It provides fine-grained scope management for controlling access to specific product functionality, and supports both environment-level API tokens and ActiveGate connection tokens.

**Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/tokens-v2](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/tokens-v2)

#### Tags:

 - Access Management, Authentication, Security, Tokens

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/tokens-v2)
- [APIReference](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/tokens-v2/api-tokens)
- [GettingStarted](https://docs.dynatrace.com/docs/manage/identity-access-management/access-tokens-and-oauth-clients/access-tokens)

### Dynatrace Service-Level Objectives API
The Dynatrace Service-Level Objectives API is a management API for creating, editing, listing, deleting, and evaluating SLOs and SLO templates within a Dynatrace environment. It enables programmatic definition of reliability targets and automated evaluation of service-level compliance based on Dynatrace monitoring data.

**Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/service-level-objectives](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/service-level-objectives)

#### Tags:

 - Observability, Reliability, Service Level Objectives, SLO

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/service-level-objectives)
- [APIReference](https://docs.dynatrace.com/docs/deliver/service-level-objectives)

### Dynatrace Releases API
The Dynatrace Releases API provides an overview of releases deployed in your monitored environment. It allows you to retrieve information about software releases, deployment versions, and release stages, enabling automated tracking of deployment activity and version management across monitored entities.

**Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/releaseapi](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/releaseapi)

#### Tags:

 - Deployment, Observability, Releases, Version Management

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/releaseapi)

### Dynatrace Network Zones API
The Dynatrace Network Zones API enables you to manage network zones within a Dynatrace environment. It provides endpoints for listing all network zones, retrieving zone details including OneAgent counts, creating and updating zone configurations, deleting zones, and getting global network zone configuration settings.

**Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/network-zones](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/network-zones)

#### Tags:

 - Infrastructure, Monitoring, Network Zones, Networking

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/network-zones)
- [APIReference](https://docs.dynatrace.com/docs/manage/network-zones/network-zones-basic-info)

### Dynatrace Deployment API
The Dynatrace Deployment API provides endpoints for downloading OneAgent and ActiveGate installers, listing available installer versions, and retrieving ActiveGate endpoint information. It enables automated deployment and upgrade of monitoring agents across your infrastructure using the InstallerDownload token scope.

**Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/deployment](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/deployment)

#### Tags:

 - ActiveGate, Deployment, Installation, OneAgent

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/deployment)
- [APIReference](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/deployment/oneagent)

### Dynatrace Audit Logs API
The Dynatrace Audit Logs API provides access to audit-related events within a Dynatrace environment including logins, logouts, configuration changes, and API token modifications. Audit logs are retained for 30 days and support filtering by event type, user, and time range for security monitoring and compliance purposes.

**Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/audit-logs](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/audit-logs)

#### Tags:

 - Audit Logs, Compliance, Governance, Security

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/audit-logs)
- [APIReference](https://docs.dynatrace.com/docs/manage/data-privacy-and-security/configuration/audit-logs-api)

### Dynatrace Business Events API v2
The Dynatrace Business Events API v2 enables ingestion of business event data in JSON format into Dynatrace via the bizevents/ingest endpoint. It supports business-grade reporting and analytics through the Grail data lakehouse with lossless data prioritization, deep data capture from in-flight payloads, and powerful ad-hoc queries for business observability use cases.

**Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/business-analytics-v2](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/business-analytics-v2)

#### Tags:

 - Business Analytics, Business Events, Business Intelligence, Observability

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/business-analytics-v2)
- [APIReference](https://docs.dynatrace.com/docs/observe/business-observability/bo-api-ingest)

### Dynatrace Application Security API
The Dynatrace Application Security API provides endpoints for querying vulnerabilities, vulnerability details, remediation items, vulnerable functions, and security attacks within a Dynatrace environment. It includes the Vulnerabilities API, Attacks API, and Davis Security Advisor API for comprehensive runtime application security analysis and threat detection.

**Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/application-security/vulnerabilities](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/application-security/vulnerabilities)

#### Tags:

 - Application Security, Runtime Protection, Security, Vulnerabilities

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/application-security/vulnerabilities)
- [APIReference](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/application-security/attacks)
- [APIReference](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/application-security/davis-security-advice)

### Dynatrace Custom Tags API
The Dynatrace Custom Tags API allows you to manage custom tags on monitored entities within a Dynatrace environment. It provides endpoints for reading, adding, and removing tags from entities such as hosts, services, processes, and applications, enabling automated organization and categorization of monitored resources.

**Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/custom-tags](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/custom-tags)

#### Tags:

 - Entities, Metadata, Monitoring

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/custom-tags)

### Dynatrace ActiveGate API
The Dynatrace ActiveGate API enables you to view and manage ActiveGate configurations within a Dynatrace environment. It provides endpoints for listing ActiveGates, retrieving ActiveGate details, managing auto-update configurations, and monitoring auto-update job status for Environment ActiveGates.

**Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/activegates](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/activegates)

#### Tags:

 - ActiveGate, Deployment, Infrastructure, Monitoring

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/activegates)
- [APIReference](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/tokens-v2/activegate-tokens)

### Dynatrace Credential Vault API
The Dynatrace Credential Vault API enables management of credentials used for synthetic browser and HTTP monitors within a Dynatrace environment. It supports creating, listing, updating, and deleting credential sets of type certificate, public certificate, token, and username/password for use in synthetic monitoring configurations.

**Human URL:** [https://docs.dynatrace.com/docs/dynatrace-api/environment-api/credential-vault](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/credential-vault)

#### Tags:

 - Credentials, Secrets, Security, Synthetic Monitoring

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api/environment-api/credential-vault)
- [APIReference](https://docs.dynatrace.com/docs/manage/credential-vault)

### Dynatrace Document API
The Dynatrace Document API provides a platform service for creating, managing, and sharing documents such as dashboards, notebooks, and launchpads within Dynatrace. It persists content-agnostic documents with metadata and supports querying by document type, enabling programmatic management of analytical and visualization assets.

**Human URL:** [https://docs.dynatrace.com/docs/analyze-explore-automate/dashboards-and-notebooks/document-api](https://docs.dynatrace.com/docs/analyze-explore-automate/dashboards-and-notebooks/document-api)

#### Tags:

 - Dashboards, Documents, Notebooks, Platform

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/analyze-explore-automate/dashboards-and-notebooks/document-api)
- [SDK](https://developer.dynatrace.com/develop/sdks/client-document/)
- [APIReference](https://developer.dynatrace.com/plan/platform-services/document-service/)

### Dynatrace Grail Bucket Management API
The Dynatrace Grail Bucket Management API provides a public API for managing storage buckets within the Grail data lakehouse. It supports creating, updating, deleting, and truncating buckets for organizing logs, events, and business events data with configurable retention periods between 1 and 3657 days.

**Human URL:** [https://developer.dynatrace.com/develop/sdks/client-bucket-management/](https://developer.dynatrace.com/develop/sdks/client-bucket-management/)

#### Tags:

 - Data Management, Grail, Platform, Storage

#### Properties

- [Documentation](https://developer.dynatrace.com/develop/sdks/client-bucket-management/)
- [APIReference](https://docs.dynatrace.com/docs/platform/grail/organize-data)

### Dynatrace Davis AI API
The Dynatrace Davis AI API provides access to the Davis predictive and causal AI platform service for customized AI/ML analysis. It delivers time series forecasting, anomaly detection model training, and automated monitoring of metric behavior changes, enabling application creators to build intelligent automation and analytics within Dynatrace Apps.

**Human URL:** [https://developer.dynatrace.com/develop/sdks/client-davis-analyzers/](https://developer.dynatrace.com/develop/sdks/client-davis-analyzers/)

#### Tags:

 - Causal Analysis, Davis AI, Machine Learning, Platform, Predictive Analytics

#### Properties

- [Documentation](https://developer.dynatrace.com/develop/sdks/client-davis-analyzers/)
- [GettingStarted](https://developer.dynatrace.com/develop/forecast-with-davis-ai/)
- [APIReference](https://docs.dynatrace.com/docs/discover-dynatrace/platform/davis-ai)

### Dynatrace Hub API
The Dynatrace Hub API provides programmatic access to the Dynatrace Hub catalog content including apps, extensions, and technologies in the context of the current environment. It supports listing and retrieving details for apps, extensions, technologies, and Hub categories for building custom catalog integrations and discovery experiences.

**Human URL:** [https://developer.dynatrace.com/develop/sdks/client-hub/](https://developer.dynatrace.com/develop/sdks/client-hub/)

#### Tags:

 - Apps, Catalog, Extensions, Hub, Platform

#### Properties

- [Documentation](https://developer.dynatrace.com/develop/sdks/client-hub/)
- [APIReference](https://docs.dynatrace.com/docs/manage/hub)

### Dynatrace OneAgent on a Host API
The Dynatrace OneAgent on a Host API enables you to check the configuration and status of OneAgent instances deployed on your hosts. It provides endpoints for listing hosts with OneAgent details, retrieving agent version information, and monitoring agent health and connectivity within a Dynatrace environment.

**Human URL:** [https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/oneagent-on-host](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/oneagent-on-host)

#### Tags:

 - Deployment, Host Monitoring, Infrastructure, OneAgent

#### Properties

- [Documentation](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/environment-api/oneagent-on-host)

### Dynatrace Platform Management API
The Dynatrace Platform Management API provides basic read-only information about the currently logged-in environment including environment settings, license information, and permissions. It is a core platform service used for querying environment metadata and configuration context within Dynatrace Apps and automation workflows.

**Human URL:** [https://developer.dynatrace.com/develop/sdks/client-platform-management-service/](https://developer.dynatrace.com/develop/sdks/client-platform-management-service/)

#### Tags:

 - Administration, Environment Management, Platform, Settings

#### Properties

- [Documentation](https://developer.dynatrace.com/develop/sdks/client-platform-management-service/)
- [APIReference](https://developer.dynatrace.com/plan/platform-services/platform-management-service/)

## Common Properties

- [Portal](https://www.dynatrace.com/support/help/dynatrace-api)
- [Documentation](https://docs.dynatrace.com/docs/dynatrace-api)
- [Authentication](https://www.dynatrace.com/support/help/dynatrace-api/basics/dynatrace-api-authentication)
- [GettingStarted](https://www.dynatrace.com/support/help/dynatrace-api/basics)
- [APIReference](https://www.dynatrace.com/support/help/dynatrace-api/basics/dynatrace-api-response-codes)
- [ChangeLog](https://docs.dynatrace.com/docs/whats-new/dynatrace-api)
- [TermsOfService](https://www.dynatrace.com/company/trust-center/terms/)
- [PrivacyPolicy](https://www.dynatrace.com/company/trust-center/privacy/)
- [Support](https://www.dynatrace.com/support/)
- [Pricing](https://www.dynatrace.com/pricing/)
- [SignUp](https://www.dynatrace.com/signup/)
- [Support](https://community.dynatrace.com/)
- [Blog](https://community.dynatrace.com/t5/Developer-Blog/bg-p/dev_blog)
- [StatusPage](https://dynatrace.status.io/)
- [GitHubOrganization](https://github.com/Dynatrace)
- [DeveloperPortal](https://developer.dynatrace.com/)
- [StackOverflow](https://stackoverflow.com/questions/tagged/dynatrace)
- [YouTube](https://www.youtube.com/c/dynatrace)
- [JSONSchema](json-schema/dynatrace-metric-series-schema.json)
- [JSONSchema](json-schema/dynatrace-problem-schema.json)
- [JSONLD](json-ld/dynatrace-context.jsonld)
- [SDK](https://developer.dynatrace.com/develop/sdks/)
- [Authentication](https://developer.dynatrace.com/develop/access-platform-apis-from-outside/)
- [Security](https://docs.dynatrace.com/docs/manage/identity-access-management)
- [GitHubRepository](https://github.com/Dynatrace/dynatrace-api)
- [Marketplace](https://www.dynatrace.com/hub/)
- [ReleaseNotes](https://docs.dynatrace.com/docs/discover-dynatrace/references/dynatrace-api/basics/deprecation-migration-guides)
- [Documentation](https://developer.dynatrace.com/plan/platform-services/)
- [CLI: Configuration as Code CLI](https://github.com/Dynatrace/dynatrace-configuration-as-code)
- [SDK: Java OneAgent SDK](https://github.com/Dynatrace/OneAgent-SDK-for-Java)
- [SDK: Python OneAgent SDK](https://github.com/Dynatrace/OneAgent-SDK-for-Python)
- [SDK: Node.js OneAgent SDK](https://github.com/Dynatrace/OneAgent-SDK-for-NodeJs)
- [SDK: .NET OneAgent SDK](https://github.com/Dynatrace/OneAgent-SDK-for-dotnet)
- [SDK: C OneAgent SDK](https://github.com/Dynatrace/OneAgent-SDK-for-C)
- [SDK: Swift Mobile SDK](https://github.com/Dynatrace/swift-mobile-sdk)
- [CodeExamples: Workflow Samples](https://github.com/Dynatrace/Dynatrace-workflow-samples)
- [CodeExamples: Code Snippets](https://github.com/Dynatrace/snippets)
- [CodeExamples: Community Examples](https://github.com/Dynatrace/community-examples)
- [Tutorials: Tutorials](https://github.com/Dynatrace/Dynatrace-Tutorial)
- [SpectralRules](rules/dynatrace-spectral-rules.yml)
- [Vocabulary](vocabulary/dynatrace-vocabulary.yaml)
- [NaftikoCapability](capabilities/identity-and-access.yaml)
- [NaftikoCapability](capabilities/log-analytics.yaml)
- [NaftikoCapability](capabilities/observability-monitoring.yaml)
- [JSONLD](json-ld/dynatrace-account-management-api-context.jsonld)
- [JSONLD](json-ld/dynatrace-dynatrace-metric-series-context.jsonld)
- [JSONLD](json-ld/dynatrace-dynatrace-problem-context.jsonld)
- [JSONLD](json-ld/dynatrace-entities-api-v2-context.jsonld)
- [JSONLD](json-ld/dynatrace-events-api-v2-context.jsonld)
- [JSONLD](json-ld/dynatrace-log-monitoring-api-v2-context.jsonld)
- [JSONLD](json-ld/dynatrace-metrics-api-v2-context.jsonld)
- [JSONLD](json-ld/dynatrace-problems-api-v2-context.jsonld)
- [JSONLD](json-ld/dynatrace-problems-entity-ref-context.jsonld)
- [JSONLD](json-ld/dynatrace-problems-impacted-entity-context.jsonld)
- [JSONLD](json-ld/dynatrace-problems-problem-details-context.jsonld)
- [JSONLD](json-ld/dynatrace-problems-problem-notification-payload-context.jsonld)
- [JSONLD](json-ld/dynatrace-problems-webhook-header-context.jsonld)
- [JSONLD](json-ld/dynatrace-problems-webhook-notification-config-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Full-Stack Observability | End-to-end monitoring of applications, infrastructure, and digital experiences with automatic discovery and AI-powered root cause analysis. |
| Davis AI Engine | Deterministic AI engine that automatically detects anomalies, identifies root causes, and provides precise answers about performance issues without manual configuration. |
| Grail Data Lakehouse | Unified data store that combines logs, metrics, traces, events, and business data in a single analytics platform with unlimited retention and DQL query language. |
| Software Intelligence | Real-time topology mapping and dependency analysis across distributed systems with automatic baselining and smart alerting. |
| Cloud Automation | Automated workflows, remediation, and orchestration capabilities that integrate with CI/CD pipelines and IT service management tools. |
| Application Security | Runtime application security with vulnerability detection, attack protection, and security analytics built into the observability platform. |
| Digital Experience Monitoring | Real user monitoring, session replay, and synthetic monitoring for web and mobile applications to optimize user experience. |
| OpenPipeline Data Ingestion | Flexible data ingestion framework supporting any data source and format with configurable routing, processing, and enrichment pipelines. |
| Extensions Framework | Extensible monitoring platform with 600+ out-of-the-box integrations and a framework for building custom data collection extensions. |
| Service Level Objectives | Automated SLO tracking and evaluation with burn rate alerting and reliability scoring based on real monitoring data. |

## Use Cases

| Name | Description |
|------|-------------|
| Infrastructure Monitoring | Monitor hosts, containers, and cloud infrastructure with automatic discovery, health metrics, and capacity planning across hybrid and multi-cloud environments. |
| Application Performance Management | Trace distributed transactions end-to-end, identify bottlenecks, and optimize application performance with code-level visibility and AI-powered insights. |
| Log Analytics and Management | Ingest, search, and analyze log data at scale using the Grail data lakehouse with DQL queries for troubleshooting and compliance. |
| Cloud Migration Monitoring | Track application health and performance during cloud migration with automatic dependency mapping and impact analysis. |
| DevOps and SRE Automation | Integrate observability into CI/CD pipelines with automated quality gates, deployment validation, and incident response workflows. |
| Business Analytics | Correlate business events with technical performance data to measure revenue impact and optimize digital business outcomes. |
| Security Posture Management | Detect runtime vulnerabilities, monitor attack attempts, and assess application security posture with integrated security analytics. |
| Synthetic Testing | Proactively monitor application availability and performance with browser-based and HTTP synthetic tests from global locations. |

## Integrations

| Name | Description |
|------|-------------|
| AWS CloudWatch | Native integration with AWS services for monitoring EC2, Lambda, RDS, and other AWS resources with automatic tagging and topology mapping. |
| Azure Monitor | Deep integration with Microsoft Azure for monitoring Azure App Services, AKS, Functions, and other Azure platform services. |
| Google Cloud Platform | Integration with GCP services including GKE, Cloud Run, Cloud Functions, and BigQuery for comprehensive cloud monitoring. |
| Kubernetes | Full-stack Kubernetes monitoring with automatic pod, node, and cluster discovery, resource utilization tracking, and workload health analysis. |
| ServiceNow | Bidirectional integration with ServiceNow for automated incident creation, enrichment, and resolution based on Dynatrace problem detection. |
| PagerDuty | Integration with PagerDuty for intelligent alert routing, incident management, and on-call notification based on Dynatrace AI-detected problems. |
| Slack | Notification integration with Slack channels for real-time alerts on performance issues, deployments, and problem resolution updates. |
| Jira | Integration with Atlassian Jira for automated issue creation and tracking based on detected performance problems and vulnerabilities. |
| Terraform | Terraform provider for infrastructure-as-code management of Dynatrace monitoring configuration, dashboards, and alerting profiles. |
| Ansible | Ansible collection for automated deployment and configuration of Dynatrace OneAgent and environment settings across infrastructure. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Dynatrace Account Management Api Openapi](openapi/dynatrace-account-management-api-openapi.yml)
- [Dynatrace Entities Api V2 Openapi](openapi/dynatrace-entities-api-v2-openapi.yml)
- [Dynatrace Events Api V2 Openapi](openapi/dynatrace-events-api-v2-openapi.yml)
- [Dynatrace Log Monitoring Api V2 Openapi](openapi/dynatrace-log-monitoring-api-v2-openapi.yml)
- [Dynatrace Metrics Api V2 Openapi](openapi/dynatrace-metrics-api-v2-openapi.yml)
- [Dynatrace Problems Api V2 Openapi](openapi/dynatrace-problems-api-v2-openapi.yml)

### AsyncAPI

- [Dynatrace Problems Asyncapi](asyncapi/dynatrace-problems-asyncapi.yml)

### JSON Schema

- [Account Management Api Environment Collection Schema](json-schema/account-management-api-environment-collection-schema.json)
- [Account Management Api Environment Schema](json-schema/account-management-api-environment-schema.json)
- [Account Management Api Group Collection Schema](json-schema/account-management-api-group-collection-schema.json)
- [Account Management Api Group Create Request Schema](json-schema/account-management-api-group-create-request-schema.json)
- [Account Management Api Group Schema](json-schema/account-management-api-group-schema.json)
- [Account Management Api Permission Collection Schema](json-schema/account-management-api-permission-collection-schema.json)
- [Account Management Api Permission Schema](json-schema/account-management-api-permission-schema.json)
- [Account Management Api User Collection Schema](json-schema/account-management-api-user-collection-schema.json)
- [Account Management Api User Create Request Schema](json-schema/account-management-api-user-create-request-schema.json)
- [Account Management Api User Schema](json-schema/account-management-api-user-schema.json)
- [Dynatrace Metric Series Schema](json-schema/dynatrace-metric-series-schema.json)
- [Dynatrace Problem Schema](json-schema/dynatrace-problem-schema.json)
- [Entities Api V2 Constraint Violation Schema](json-schema/entities-api-v2-constraint-violation-schema.json)
- [Entities Api V2 Entity Collection Schema](json-schema/entities-api-v2-entity-collection-schema.json)
- [Entities Api V2 Entity Lookup Request Schema](json-schema/entities-api-v2-entity-lookup-request-schema.json)
- [Entities Api V2 Entity Schema](json-schema/entities-api-v2-entity-schema.json)
- [Entities Api V2 Entity Tag Schema](json-schema/entities-api-v2-entity-tag-schema.json)
- [Entities Api V2 Entity Type Collection Schema](json-schema/entities-api-v2-entity-type-collection-schema.json)
- [Entities Api V2 Entity Type Property Schema](json-schema/entities-api-v2-entity-type-property-schema.json)
- [Entities Api V2 Entity Type Relationship Schema](json-schema/entities-api-v2-entity-type-relationship-schema.json)
- [Entities Api V2 Entity Type Schema](json-schema/entities-api-v2-entity-type-schema.json)
- [Entities Api V2 Management Zone Schema](json-schema/entities-api-v2-management-zone-schema.json)
- [Events Api V2 Constraint Violation Schema](json-schema/events-api-v2-constraint-violation-schema.json)
- [Events Api V2 Entity Stub Schema](json-schema/events-api-v2-entity-stub-schema.json)
- [Events Api V2 Event Collection Schema](json-schema/events-api-v2-event-collection-schema.json)
- [Events Api V2 Event Ingest Payload Schema](json-schema/events-api-v2-event-ingest-payload-schema.json)
- [Events Api V2 Event Ingest Result Item Schema](json-schema/events-api-v2-event-ingest-result-item-schema.json)
- [Events Api V2 Event Ingest Result Schema](json-schema/events-api-v2-event-ingest-result-schema.json)
- [Events Api V2 Event Schema](json-schema/events-api-v2-event-schema.json)
- [Log Monitoring Api V2 Constraint Violation Schema](json-schema/log-monitoring-api-v2-constraint-violation-schema.json)
- [Log Monitoring Api V2 Log Aggregate Group Schema](json-schema/log-monitoring-api-v2-log-aggregate-group-schema.json)
- [Log Monitoring Api V2 Log Aggregate Result Schema](json-schema/log-monitoring-api-v2-log-aggregate-result-schema.json)
- [Log Monitoring Api V2 Log Export Result Schema](json-schema/log-monitoring-api-v2-log-export-result-schema.json)
- [Log Monitoring Api V2 Log Ingest Record Schema](json-schema/log-monitoring-api-v2-log-ingest-record-schema.json)
- [Log Monitoring Api V2 Log Record Schema](json-schema/log-monitoring-api-v2-log-record-schema.json)
- [Log Monitoring Api V2 Log Record Search Result Schema](json-schema/log-monitoring-api-v2-log-record-search-result-schema.json)
- [Metrics Api V2 Constraint Violation Schema](json-schema/metrics-api-v2-constraint-violation-schema.json)
- [Metrics Api V2 Metric Data Schema](json-schema/metrics-api-v2-metric-data-schema.json)
- [Metrics Api V2 Metric Default Aggregation Schema](json-schema/metrics-api-v2-metric-default-aggregation-schema.json)
- [Metrics Api V2 Metric Descriptor Collection Schema](json-schema/metrics-api-v2-metric-descriptor-collection-schema.json)
- [Metrics Api V2 Metric Descriptor Schema](json-schema/metrics-api-v2-metric-descriptor-schema.json)
- [Metrics Api V2 Metric Dimension Definition Schema](json-schema/metrics-api-v2-metric-dimension-definition-schema.json)
- [Metrics Api V2 Metric Series Collection Schema](json-schema/metrics-api-v2-metric-series-collection-schema.json)
- [Metrics Api V2 Metric Series Schema](json-schema/metrics-api-v2-metric-series-schema.json)
- [Problems Api V2 Alerting Profile Stub Schema](json-schema/problems-api-v2-alerting-profile-stub-schema.json)
- [Problems Api V2 Comment Collection Schema](json-schema/problems-api-v2-comment-collection-schema.json)
- [Problems Api V2 Comment Request Body Schema](json-schema/problems-api-v2-comment-request-body-schema.json)
- [Problems Api V2 Comment Schema](json-schema/problems-api-v2-comment-schema.json)
- [Problems Api V2 Constraint Violation Schema](json-schema/problems-api-v2-constraint-violation-schema.json)
- [Problems Api V2 Entity Stub Schema](json-schema/problems-api-v2-entity-stub-schema.json)
- [Problems Api V2 Management Zone Schema](json-schema/problems-api-v2-management-zone-schema.json)
- [Problems Api V2 Problem Close Request Schema](json-schema/problems-api-v2-problem-close-request-schema.json)
- [Problems Api V2 Problem Close Result Schema](json-schema/problems-api-v2-problem-close-result-schema.json)
- [Problems Api V2 Problem Collection Schema](json-schema/problems-api-v2-problem-collection-schema.json)
- [Problems Api V2 Problem Schema](json-schema/problems-api-v2-problem-schema.json)
- [Problems Entity Ref Schema](json-schema/problems-entity-ref-schema.json)
- [Problems Impacted Entity Schema](json-schema/problems-impacted-entity-schema.json)
- [Problems Problem Details Schema](json-schema/problems-problem-details-schema.json)
- [Problems Problem Notification Payload Schema](json-schema/problems-problem-notification-payload-schema.json)
- [Problems Webhook Header Schema](json-schema/problems-webhook-header-schema.json)
- [Problems Webhook Notification Config Schema](json-schema/problems-webhook-notification-config-schema.json)

### JSON Structure

- [Account Management Api Environment Collection Structure](json-structure/account-management-api-environment-collection-structure.json)
- [Account Management Api Environment Structure](json-structure/account-management-api-environment-structure.json)
- [Account Management Api Group Collection Structure](json-structure/account-management-api-group-collection-structure.json)
- [Account Management Api Group Create Request Structure](json-structure/account-management-api-group-create-request-structure.json)
- [Account Management Api Group Structure](json-structure/account-management-api-group-structure.json)
- [Account Management Api Permission Collection Structure](json-structure/account-management-api-permission-collection-structure.json)
- [Account Management Api Permission Structure](json-structure/account-management-api-permission-structure.json)
- [Account Management Api User Collection Structure](json-structure/account-management-api-user-collection-structure.json)
- [Account Management Api User Create Request Structure](json-structure/account-management-api-user-create-request-structure.json)
- [Account Management Api User Structure](json-structure/account-management-api-user-structure.json)
- [Dynatrace Metric Series Structure](json-structure/dynatrace-metric-series-structure.json)
- [Dynatrace Problem Structure](json-structure/dynatrace-problem-structure.json)
- [Entities Api V2 Constraint Violation Structure](json-structure/entities-api-v2-constraint-violation-structure.json)
- [Entities Api V2 Entity Collection Structure](json-structure/entities-api-v2-entity-collection-structure.json)
- [Entities Api V2 Entity Lookup Request Structure](json-structure/entities-api-v2-entity-lookup-request-structure.json)
- [Entities Api V2 Entity Structure](json-structure/entities-api-v2-entity-structure.json)
- [Entities Api V2 Entity Tag Structure](json-structure/entities-api-v2-entity-tag-structure.json)
- [Entities Api V2 Entity Type Collection Structure](json-structure/entities-api-v2-entity-type-collection-structure.json)
- [Entities Api V2 Entity Type Property Structure](json-structure/entities-api-v2-entity-type-property-structure.json)
- [Entities Api V2 Entity Type Relationship Structure](json-structure/entities-api-v2-entity-type-relationship-structure.json)
- [Entities Api V2 Entity Type Structure](json-structure/entities-api-v2-entity-type-structure.json)
- [Entities Api V2 Management Zone Structure](json-structure/entities-api-v2-management-zone-structure.json)
- [Events Api V2 Constraint Violation Structure](json-structure/events-api-v2-constraint-violation-structure.json)
- [Events Api V2 Entity Stub Structure](json-structure/events-api-v2-entity-stub-structure.json)
- [Events Api V2 Event Collection Structure](json-structure/events-api-v2-event-collection-structure.json)
- [Events Api V2 Event Ingest Payload Structure](json-structure/events-api-v2-event-ingest-payload-structure.json)
- [Events Api V2 Event Ingest Result Item Structure](json-structure/events-api-v2-event-ingest-result-item-structure.json)
- [Events Api V2 Event Ingest Result Structure](json-structure/events-api-v2-event-ingest-result-structure.json)
- [Events Api V2 Event Structure](json-structure/events-api-v2-event-structure.json)
- [Log Monitoring Api V2 Constraint Violation Structure](json-structure/log-monitoring-api-v2-constraint-violation-structure.json)
- [Log Monitoring Api V2 Log Aggregate Group Structure](json-structure/log-monitoring-api-v2-log-aggregate-group-structure.json)
- [Log Monitoring Api V2 Log Aggregate Result Structure](json-structure/log-monitoring-api-v2-log-aggregate-result-structure.json)
- [Log Monitoring Api V2 Log Export Result Structure](json-structure/log-monitoring-api-v2-log-export-result-structure.json)
- [Log Monitoring Api V2 Log Ingest Record Structure](json-structure/log-monitoring-api-v2-log-ingest-record-structure.json)
- [Log Monitoring Api V2 Log Record Search Result Structure](json-structure/log-monitoring-api-v2-log-record-search-result-structure.json)
- [Log Monitoring Api V2 Log Record Structure](json-structure/log-monitoring-api-v2-log-record-structure.json)
- [Metrics Api V2 Constraint Violation Structure](json-structure/metrics-api-v2-constraint-violation-structure.json)
- [Metrics Api V2 Metric Data Structure](json-structure/metrics-api-v2-metric-data-structure.json)
- [Metrics Api V2 Metric Default Aggregation Structure](json-structure/metrics-api-v2-metric-default-aggregation-structure.json)
- [Metrics Api V2 Metric Descriptor Collection Structure](json-structure/metrics-api-v2-metric-descriptor-collection-structure.json)
- [Metrics Api V2 Metric Descriptor Structure](json-structure/metrics-api-v2-metric-descriptor-structure.json)
- [Metrics Api V2 Metric Dimension Definition Structure](json-structure/metrics-api-v2-metric-dimension-definition-structure.json)
- [Metrics Api V2 Metric Series Collection Structure](json-structure/metrics-api-v2-metric-series-collection-structure.json)
- [Metrics Api V2 Metric Series Structure](json-structure/metrics-api-v2-metric-series-structure.json)
- [Problems Api V2 Alerting Profile Stub Structure](json-structure/problems-api-v2-alerting-profile-stub-structure.json)
- [Problems Api V2 Comment Collection Structure](json-structure/problems-api-v2-comment-collection-structure.json)
- [Problems Api V2 Comment Request Body Structure](json-structure/problems-api-v2-comment-request-body-structure.json)
- [Problems Api V2 Comment Structure](json-structure/problems-api-v2-comment-structure.json)
- [Problems Api V2 Constraint Violation Structure](json-structure/problems-api-v2-constraint-violation-structure.json)
- [Problems Api V2 Entity Stub Structure](json-structure/problems-api-v2-entity-stub-structure.json)
- [Problems Api V2 Management Zone Structure](json-structure/problems-api-v2-management-zone-structure.json)
- [Problems Api V2 Problem Close Request Structure](json-structure/problems-api-v2-problem-close-request-structure.json)
- [Problems Api V2 Problem Close Result Structure](json-structure/problems-api-v2-problem-close-result-structure.json)
- [Problems Api V2 Problem Collection Structure](json-structure/problems-api-v2-problem-collection-structure.json)
- [Problems Api V2 Problem Structure](json-structure/problems-api-v2-problem-structure.json)
- [Problems Entity Ref Structure](json-structure/problems-entity-ref-structure.json)
- [Problems Impacted Entity Structure](json-structure/problems-impacted-entity-structure.json)
- [Problems Problem Details Structure](json-structure/problems-problem-details-structure.json)
- [Problems Problem Notification Payload Structure](json-structure/problems-problem-notification-payload-structure.json)
- [Problems Webhook Header Structure](json-structure/problems-webhook-header-structure.json)
- [Problems Webhook Notification Config Structure](json-structure/problems-webhook-notification-config-structure.json)

### JSON-LD

- [Dynatrace Account Management Api Contextld](json-ld/dynatrace-account-management-api-context.jsonld)
- [Dynatrace Contextld](json-ld/dynatrace-context.jsonld)
- [Dynatrace Dynatrace Metric Series Contextld](json-ld/dynatrace-dynatrace-metric-series-context.jsonld)
- [Dynatrace Dynatrace Problem Contextld](json-ld/dynatrace-dynatrace-problem-context.jsonld)
- [Dynatrace Entities Api V2 Contextld](json-ld/dynatrace-entities-api-v2-context.jsonld)
- [Dynatrace Events Api V2 Contextld](json-ld/dynatrace-events-api-v2-context.jsonld)
- [Dynatrace Log Monitoring Api V2 Contextld](json-ld/dynatrace-log-monitoring-api-v2-context.jsonld)
- [Dynatrace Metrics Api V2 Contextld](json-ld/dynatrace-metrics-api-v2-context.jsonld)
- [Dynatrace Problems Api V2 Contextld](json-ld/dynatrace-problems-api-v2-context.jsonld)
- [Dynatrace Problems Entity Ref Contextld](json-ld/dynatrace-problems-entity-ref-context.jsonld)
- [Dynatrace Problems Impacted Entity Contextld](json-ld/dynatrace-problems-impacted-entity-context.jsonld)
- [Dynatrace Problems Problem Details Contextld](json-ld/dynatrace-problems-problem-details-context.jsonld)
- [Dynatrace Problems Problem Notification Payload Contextld](json-ld/dynatrace-problems-problem-notification-payload-context.jsonld)
- [Dynatrace Problems Webhook Header Contextld](json-ld/dynatrace-problems-webhook-header-context.jsonld)
- [Dynatrace Problems Webhook Notification Config Contextld](json-ld/dynatrace-problems-webhook-notification-config-context.jsonld)

### Examples

- [Account Management Api Environment Collection Example](examples/account-management-api-environment-collection-example.json)
- [Account Management Api Environment Example](examples/account-management-api-environment-example.json)
- [Account Management Api Group Collection Example](examples/account-management-api-group-collection-example.json)
- [Account Management Api Group Create Request Example](examples/account-management-api-group-create-request-example.json)
- [Account Management Api Group Example](examples/account-management-api-group-example.json)
- [Account Management Api Permission Collection Example](examples/account-management-api-permission-collection-example.json)
- [Account Management Api Permission Example](examples/account-management-api-permission-example.json)
- [Account Management Api User Collection Example](examples/account-management-api-user-collection-example.json)
- [Account Management Api User Create Request Example](examples/account-management-api-user-create-request-example.json)
- [Account Management Api User Example](examples/account-management-api-user-example.json)
- [Dynatrace Metric Series Example](examples/dynatrace-metric-series-example.json)
- [Dynatrace Problem Example](examples/dynatrace-problem-example.json)
- [Entities Api V2 Constraint Violation Example](examples/entities-api-v2-constraint-violation-example.json)
- [Entities Api V2 Entity Collection Example](examples/entities-api-v2-entity-collection-example.json)
- [Entities Api V2 Entity Example](examples/entities-api-v2-entity-example.json)
- [Entities Api V2 Entity Lookup Request Example](examples/entities-api-v2-entity-lookup-request-example.json)
- [Entities Api V2 Entity Tag Example](examples/entities-api-v2-entity-tag-example.json)
- [Entities Api V2 Entity Type Collection Example](examples/entities-api-v2-entity-type-collection-example.json)
- [Entities Api V2 Entity Type Example](examples/entities-api-v2-entity-type-example.json)
- [Entities Api V2 Entity Type Property Example](examples/entities-api-v2-entity-type-property-example.json)
- [Entities Api V2 Entity Type Relationship Example](examples/entities-api-v2-entity-type-relationship-example.json)
- [Entities Api V2 Management Zone Example](examples/entities-api-v2-management-zone-example.json)
- [Events Api V2 Constraint Violation Example](examples/events-api-v2-constraint-violation-example.json)
- [Events Api V2 Entity Stub Example](examples/events-api-v2-entity-stub-example.json)
- [Events Api V2 Event Collection Example](examples/events-api-v2-event-collection-example.json)
- [Events Api V2 Event Example](examples/events-api-v2-event-example.json)
- [Events Api V2 Event Ingest Payload Example](examples/events-api-v2-event-ingest-payload-example.json)
- [Events Api V2 Event Ingest Result Example](examples/events-api-v2-event-ingest-result-example.json)
- [Events Api V2 Event Ingest Result Item Example](examples/events-api-v2-event-ingest-result-item-example.json)
- [Log Monitoring Api V2 Constraint Violation Example](examples/log-monitoring-api-v2-constraint-violation-example.json)
- [Log Monitoring Api V2 Log Aggregate Group Example](examples/log-monitoring-api-v2-log-aggregate-group-example.json)
- [Log Monitoring Api V2 Log Aggregate Result Example](examples/log-monitoring-api-v2-log-aggregate-result-example.json)
- [Log Monitoring Api V2 Log Export Result Example](examples/log-monitoring-api-v2-log-export-result-example.json)
- [Log Monitoring Api V2 Log Ingest Record Example](examples/log-monitoring-api-v2-log-ingest-record-example.json)
- [Log Monitoring Api V2 Log Record Example](examples/log-monitoring-api-v2-log-record-example.json)
- [Log Monitoring Api V2 Log Record Search Result Example](examples/log-monitoring-api-v2-log-record-search-result-example.json)
- [Metrics Api V2 Constraint Violation Example](examples/metrics-api-v2-constraint-violation-example.json)
- [Metrics Api V2 Metric Data Example](examples/metrics-api-v2-metric-data-example.json)
- [Metrics Api V2 Metric Default Aggregation Example](examples/metrics-api-v2-metric-default-aggregation-example.json)
- [Metrics Api V2 Metric Descriptor Collection Example](examples/metrics-api-v2-metric-descriptor-collection-example.json)
- [Metrics Api V2 Metric Descriptor Example](examples/metrics-api-v2-metric-descriptor-example.json)
- [Metrics Api V2 Metric Dimension Definition Example](examples/metrics-api-v2-metric-dimension-definition-example.json)
- [Metrics Api V2 Metric Series Collection Example](examples/metrics-api-v2-metric-series-collection-example.json)
- [Metrics Api V2 Metric Series Example](examples/metrics-api-v2-metric-series-example.json)
- [Problems Api V2 Alerting Profile Stub Example](examples/problems-api-v2-alerting-profile-stub-example.json)
- [Problems Api V2 Comment Collection Example](examples/problems-api-v2-comment-collection-example.json)
- [Problems Api V2 Comment Example](examples/problems-api-v2-comment-example.json)
- [Problems Api V2 Comment Request Body Example](examples/problems-api-v2-comment-request-body-example.json)
- [Problems Api V2 Constraint Violation Example](examples/problems-api-v2-constraint-violation-example.json)
- [Problems Api V2 Entity Stub Example](examples/problems-api-v2-entity-stub-example.json)
- [Problems Api V2 Management Zone Example](examples/problems-api-v2-management-zone-example.json)
- [Problems Api V2 Problem Close Request Example](examples/problems-api-v2-problem-close-request-example.json)
- [Problems Api V2 Problem Close Result Example](examples/problems-api-v2-problem-close-result-example.json)
- [Problems Api V2 Problem Collection Example](examples/problems-api-v2-problem-collection-example.json)
- [Problems Api V2 Problem Example](examples/problems-api-v2-problem-example.json)
- [Problems Entity Ref Example](examples/problems-entity-ref-example.json)
- [Problems Impacted Entity Example](examples/problems-impacted-entity-example.json)
- [Problems Problem Details Example](examples/problems-problem-details-example.json)
- [Problems Problem Notification Payload Example](examples/problems-problem-notification-payload-example.json)
- [Problems Webhook Header Example](examples/problems-webhook-header-example.json)
- [Problems Webhook Notification Config Example](examples/problems-webhook-notification-config-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Dynatrace Account Management API](capabilities/shared/account-management-api.yaml) -- 12 operations
- [Dynatrace Entities API v2](capabilities/shared/entities-api-v2.yaml) -- 5 operations
- [Dynatrace Events API v2](capabilities/shared/events-api-v2.yaml) -- 3 operations
- [Dynatrace Log Monitoring API v2](capabilities/shared/log-monitoring-api-v2.yaml) -- 4 operations
- [Dynatrace Metrics API v2](capabilities/shared/metrics-api-v2.yaml) -- 5 operations
- [Dynatrace Problems API v2](capabilities/shared/problems-api-v2.yaml) -- 8 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Dynatrace Identity and Access Management](capabilities/identity-and-access.yaml) | account-management-api | 12 | Platform Admin |
| [Dynatrace Log Analytics](capabilities/log-analytics.yaml) | log-monitoring-api-v2, events-api-v2 | 7 | SRE Engineer |
| [Dynatrace Observability and Monitoring](capabilities/observability-monitoring.yaml) | metrics-api-v2, entities-api-v2, events-api-v2, problems-api-v2 | 20 | SRE Engineer |

## Vocabulary

- [Dynatrace Vocabulary](vocabulary/dynatrace-vocabulary.yaml)

## Rules

- [Dynatrace Spectral Rules](rules/dynatrace-spectral-rules.yml) -- 49 rules

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
