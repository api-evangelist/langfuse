# Langfuse (langfuse)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
