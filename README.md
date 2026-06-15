# Vector (vector)

Vector is an open source high-performance observability data pipeline from Datadog for collecting, transforming, and routing logs, metrics, and traces. Built in Rust for performance and reliability, Vector supports 50+ sources, 20+ transforms, and 80+ sinks. It provides a built-in API for health monitoring and component inspection, plus Vector Remap Language (VRL) for powerful data transformation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vector/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vector/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Data Pipeline
- Logs
- Metrics
- Observability
- Open Source
- Rust
- Traces

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-05-19

## APIs

### Vector Observability API

The Vector Observability API provides HTTP endpoints for health monitoring of running Vector instances and gRPC endpoints for component inspection and event streaming. Enable via api.enabled: true in Vector configuration. Binds to 127.0.0.1:8686 by default. Note: the API does not support authentication and should only be used in isolated environments.

- **Human URL:** [https://vector.dev/docs/reference/api/](https://vector.dev/docs/reference/api/)
- **Base URL:** `http://127.0.0.1:8686`

#### Tags

- Health Monitoring
- Observability
- Pipeline Management

#### Properties

- [Documentation](https://vector.dev/docs/reference/api/)
- [OpenAPI](openapi/vector-observability-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vector-observability-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vector-observability-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/vector-observability-api-health-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/vector-observability-api-health-response-structure.json)
- [Example](examples/vector-observability-api-health-response-example.json)
- [JSON-LD](json-ld/vector-observability-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Vector Remap Language (VRL)

Vector Remap Language (VRL) is a purpose-built expression language for transforming observability data in Vector. Provides 100+ built-in functions for parsing, filtering, enriching, and transforming logs, metrics, and traces without leaving the Vector pipeline.

- **Human URL:** [https://vector.dev/docs/reference/vrl/](https://vector.dev/docs/reference/vrl/)

#### Tags

- Data Transformation
- Expression Language
- VRL

#### Properties

- [Documentation](https://vector.dev/docs/reference/vrl/)
- [GitHub Repository](https://github.com/vectordotdev/vrl)
- [Postman Collection](collections/vector-observability-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vector-observability-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vector Helm Charts

Official Helm charts for deploying Vector on Kubernetes as a DaemonSet (agent mode) or Deployment (aggregator mode).

- **Human URL:** [https://vector.dev/docs/setup/installation/package-managers/helm/](https://vector.dev/docs/setup/installation/package-managers/helm/)

#### Tags

- Helm
- Kubernetes
- Deployment

#### Properties

- [Documentation](https://vector.dev/docs/setup/installation/package-managers/helm/)
- [GitHub Repository](https://github.com/vectordotdev/helm-charts)
- [Postman Collection](collections/vector-observability-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vector-observability-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://vector.dev)
- [Documentation](https://vector.dev/docs/)
- [GitHub Organization](https://github.com/vectordotdev)
- [GitHub Repository](https://github.com/vectordotdev/vector)
- [Release Notes](https://vector.dev/releases/)
- [Blog](https://vector.dev/blog/)
- [Forum](https://discord.com/invite/n2yjjZR)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/vector-dev)
- [Spectral Rules](rules/vector-spectral-rules.yml)
- [Vocabulary](vocabulary/vector-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
