# Langfuse (langfuse)

Langfuse is an open-source LLM engineering platform offering tracing, evaluations, prompt management, datasets, and metrics. The Langfuse API supports both self-hosted and multi-region cloud deployments (US, EU, Japan, HIPAA-compliant US) and integrates with LangChain, LlamaIndex, OpenTelemetry, and any LLM stack.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/langfuse/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/langfuse/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Observability
- Open Source
- Evaluations

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-19

## APIs

### Langfuse Tracing API

Ingest traces, observations (spans, generations, events), and scores into Langfuse. Recommended path is the OpenTelemetry endpoint; legacy ingestion API is also supported. Traces are the unit of usage billing.

- **Human URL:** [https://langfuse.com/docs/tracing](https://langfuse.com/docs/tracing)
- **Base URL:** `https://cloud.langfuse.com/api/public`

#### Tags

- Tracing
- OpenTelemetry
- Ingestion

#### Properties

- [Documentation](https://langfuse.com/docs/tracing)
- [API Reference](https://api.reference.langfuse.com/)
- [OpenAPI](openapi/langfuse-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langfuse.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langfuse.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Langfuse Observations API

Read and query observations (spans, generations, events) attached to traces. Supports filtering by trace, time range, name, and metadata.

- **Human URL:** [https://langfuse.com/docs/api](https://langfuse.com/docs/api)
- **Base URL:** `https://cloud.langfuse.com/api/public`

#### Tags

- Observations
- Spans
- Generations

#### Properties

- [Documentation](https://langfuse.com/docs/api)
- [OpenAPI](openapi/langfuse-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langfuse.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langfuse.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Langfuse Metrics API

Aggregated metrics across traces, observations, scores, and costs. Supports custom dimensions, time series, and project-scoped queries for dashboarding.

- **Human URL:** [https://langfuse.com/docs/analytics](https://langfuse.com/docs/analytics)
- **Base URL:** `https://cloud.langfuse.com/api/public`

#### Tags

- Metrics
- Analytics
- Reporting

#### Properties

- [Documentation](https://langfuse.com/docs/analytics)
- [OpenAPI](openapi/langfuse-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langfuse.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langfuse.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Langfuse Prompt Management API

Create, version, label, and retrieve prompts with client-side caching. Supports text and chat prompt types, configuration variables, and label-based deployment (e.g. production, staging).

- **Human URL:** [https://langfuse.com/docs/prompts](https://langfuse.com/docs/prompts)
- **Base URL:** `https://cloud.langfuse.com/api/public`

#### Tags

- Prompts
- Versioning
- Prompt Management

#### Properties

- [Documentation](https://langfuse.com/docs/prompts)
- [OpenAPI](openapi/langfuse-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langfuse.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langfuse.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Langfuse Datasets API

Manage datasets and dataset items (input/expected-output pairs) for offline evaluation runs and regression testing.

- **Human URL:** [https://langfuse.com/docs/datasets](https://langfuse.com/docs/datasets)
- **Base URL:** `https://cloud.langfuse.com/api/public`

#### Tags

- Datasets
- Test Data
- Evaluations

#### Properties

- [Documentation](https://langfuse.com/docs/datasets)
- [OpenAPI](openapi/langfuse-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langfuse.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langfuse.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Langfuse Evaluations API

CRUD operations for evals: define evaluators (LLM-as-judge, code, human), trigger evaluations on traces or dataset runs, and read back scores and reasoning.

- **Human URL:** [https://langfuse.com/docs/evaluation](https://langfuse.com/docs/evaluation)
- **Base URL:** `https://cloud.langfuse.com/api/public`

#### Tags

- Evaluations
- Scoring
- LLM-as-Judge

#### Properties

- [Documentation](https://langfuse.com/docs/evaluation)
- [OpenAPI](openapi/langfuse-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langfuse.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langfuse.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Langfuse Scores API

Attach numeric, categorical, or boolean scores to traces, observations, or sessions. Supports user feedback, model-graded scores, and custom-defined score schemas.

- **Human URL:** [https://langfuse.com/docs/scores](https://langfuse.com/docs/scores)
- **Base URL:** `https://cloud.langfuse.com/api/public`

#### Tags

- Scores
- Feedback
- Quality

#### Properties

- [Documentation](https://langfuse.com/docs/scores)
- [OpenAPI](openapi/langfuse-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langfuse.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langfuse.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Langfuse Organizations & Projects API

Organization-level provisioning APIs to create projects, manage users, and configure project membership programmatically.

- **Human URL:** [https://langfuse.com/docs/api](https://langfuse.com/docs/api)
- **Base URL:** `https://cloud.langfuse.com/api/public`

#### Tags

- Organizations
- Projects
- Provisioning

#### Properties

- [Documentation](https://langfuse.com/docs/api)
- [OpenAPI](openapi/langfuse-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langfuse.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langfuse.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Langfuse Instance Management API

Instance-management endpoints for self-hosted Langfuse deployments. Used to administer organizations, license, and platform-wide configuration.

- **Human URL:** [https://langfuse.com/self-hosting](https://langfuse.com/self-hosting)
- **Base URL:** `https://cloud.langfuse.com/api/public`

#### Tags

- Self-Hosted
- Administration
- Instance

#### Properties

- [Documentation](https://langfuse.com/self-hosting)
- [OpenAPI](openapi/langfuse-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langfuse.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langfuse.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/langfuse)
- [Website](https://langfuse.com/)
- [Documentation](https://langfuse.com/docs)
- [API Reference](https://api.reference.langfuse.com/)
- [Pricing](https://langfuse.com/pricing)
- [Git Hub](https://github.com/langfuse/langfuse)
- [Plans](plans/langfuse-plans-pricing.yml)
- [Rate Limits](rate-limits/langfuse-rate-limits.yml)
- [Fin Ops](finops/langfuse-finops.yml)
- [Integrations](https://langfuse.com/integrations)
- [L L Ms Txt](https://api.reference.langfuse.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
