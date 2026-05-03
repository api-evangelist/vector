# Vector (vector)
Vector is an open source high-performance observability data pipeline from Datadog for collecting, transforming, and routing logs, metrics, and traces. Built in Rust for performance and reliability, Vector supports 50+ sources, 20+ transforms, and 80+ sinks. It provides a built-in API for health monitoring and component inspection, plus Vector Remap Language (VRL) for powerful data transformation.

**URL:** [https://vector.dev](https://vector.dev)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Data Pipeline, Logs, Metrics, Observability, Open Source, Rust, Traces

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-05-03

## APIs

### Vector Observability API
The Vector Observability API provides HTTP endpoints for health monitoring of running Vector instances and gRPC endpoints for component inspection and event streaming.

**Human URL:** [https://vector.dev/docs/reference/api/](https://vector.dev/docs/reference/api/)

#### Tags:

 - Health Monitoring, Observability, Pipeline Management

#### Properties

- [Documentation](https://vector.dev/docs/reference/api/)
- [OpenAPI](openapi/vector-observability-api-openapi.yml)
- [JSONSchema - Health Response Schema](json-schema/vector-observability-api-health-response-schema.json)
- [JSONStructure - Health Response Structure](json-structure/vector-observability-api-health-response-structure.json)
- [Example - Health Response](examples/vector-observability-api-health-response-example.json)
- [JSON-LD](json-ld/vector-observability-api-context.jsonld)

### Vector Remap Language (VRL)
Vector Remap Language (VRL) is a purpose-built expression language for transforming observability data in Vector with 100+ built-in functions.

**Human URL:** [https://vector.dev/docs/reference/vrl/](https://vector.dev/docs/reference/vrl/)

#### Tags:

 - Data Transformation, Expression Language, VRL

#### Properties

- [Documentation](https://vector.dev/docs/reference/vrl/)
- [GitHub Repository](https://github.com/vectordotdev/vrl)

### Vector Helm Charts
Official Helm charts for deploying Vector on Kubernetes as a DaemonSet or Deployment.

**Human URL:** [https://vector.dev/docs/setup/installation/package-managers/helm/](https://vector.dev/docs/setup/installation/package-managers/helm/)

#### Tags:

 - Helm, Kubernetes, Deployment

#### Properties

- [Documentation](https://vector.dev/docs/setup/installation/package-managers/helm/)
- [GitHub Repository](https://github.com/vectordotdev/helm-charts)

## Common Properties

- [Website](https://vector.dev)
- [Documentation](https://vector.dev/docs/)
- [GitHubOrganization](https://github.com/vectordotdev)
- [GitHubRepository](https://github.com/vectordotdev/vector)
- [ReleaseNotes](https://vector.dev/releases/)
- [Blog](https://vector.dev/blog/)
- [Forum](https://discord.com/invite/n2yjjZR)
- [StackOverflow](https://stackoverflow.com/questions/tagged/vector-dev)

## Features

| Name | Description |
|------|-------------|
| High-Performance Pipeline | Built in Rust with benchmarks showing 86+ MiB/s throughput for log pipeline workloads. |
| Unified Data Plane | Single binary handles logs, metrics, and traces from collection through routing. |
| 50+ Sources | Native integrations for files, Kafka, Kubernetes, AWS S3/CloudWatch, Splunk, and more. |
| 80+ Sinks | Route data to Elasticsearch, Datadog, S3, BigQuery, Splunk, Loki, and many more destinations. |
| Vector Remap Language (VRL) | Purpose-built expression language with 100+ functions for transforming observability data. |
| Observability API | Built-in HTTP/gRPC API for health checks and component inspection (must be explicitly enabled). |
| Kubernetes Native | Deploy as DaemonSet (agent) or Deployment (aggregator) with official Helm charts. |
| Agent and Aggregator Modes | Run as a lightweight agent on each node or as a centralized aggregator for fan-in routing. |

## Use Cases

| Name | Description |
|------|-------------|
| Log Pipeline Unification | Replace multiple log shippers with a single Vector pipeline for all log collection and routing. |
| Observability Cost Reduction | Filter, sample, and transform data before sending to expensive SaaS observability platforms. |
| Vendor Switching | Route observability data to multiple backends simultaneously to facilitate migration. |
| Kubernetes Log Collection | Deploy Vector as a DaemonSet to collect container logs from all Kubernetes nodes. |
| Log Enrichment | Parse, enrich, and normalize log events using VRL before routing to downstream systems. |
| Metrics Collection | Collect host and service metrics using Vector's built-in sources and forward to Prometheus or DataDog. |
| Splunk Cost Reduction | Use Vector to filter and route Splunk data to reduce indexing volume and licensing costs. |

## Integrations

| Name | Description |
|------|-------------|
| Datadog | Native Datadog logs and metrics sink; Vector was created and is maintained by Datadog. |
| Elasticsearch | Elasticsearch sink for forwarding logs and metrics to Elasticsearch clusters. |
| Splunk HEC | Splunk HTTP Event Collector sink for sending data to Splunk Enterprise and Cloud. |
| Kafka | Kafka source and sink for consuming and producing observability data streams. |
| AWS S3 | S3 sink for archiving logs and metrics to Amazon S3 for long-term storage. |
| Grafana Loki | Loki sink for forwarding logs to Grafana's log aggregation system. |
| Prometheus | Prometheus remote write sink and scrape source for metrics pipelines. |
| Kubernetes | Kubernetes source for collecting container logs, pod metadata, and events. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Vector Observability API](openapi/vector-observability-api-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Vector Observability API](capabilities/shared/observability-api.yaml) — 1 operation for health monitoring

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Pipeline Monitoring](capabilities/pipeline-monitoring.yaml) | Vector API | 1 | DevOps Engineer |

## Vocabulary

- [Vector Vocabulary](vocabulary/vector-vocabulary.yaml) — Unified taxonomy mapping 1 resource, 1 action, 1 workflow, and 1 persona across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Vector Spectral Rules](rules/vector-spectral-rules.yml) — 17 rules across 7 categories enforcing Vector API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
