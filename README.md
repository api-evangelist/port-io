# Port (port-io)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Port is an Internal Developer Portal built around an API-first software catalog, customizable blueprints and entities, self-service actions, and scorecards. Platform teams model their own domain (services, environments, pipelines, AI agents, cloud resources) as blueprints, ingest data from integrations (GitHub, GitLab, AWS, Azure, GCP, Kubernetes, Datadog, PagerDuty, Snyk, ServiceNow), and expose developer workflows as self-service actions backed by GitHub Actions, GitLab pipelines, Jenkins, Argo, or webhooks. Everything in Port - blueprints, entities, actions, runs, scorecards, integrations, pages, webhooks, AI agents - is reachable via the public REST API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/port-io/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/port-io/refs/heads/main/apis.yml)

## Tags

- Internal Developer Portal
- Service Catalog
- Self-Service Actions
- Platform Engineering
- Scorecards
- Developer Experience

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Port REST API

Public REST API for the Port platform. Bearer-token authenticated (3-hour tokens minted from Port credentials), with regional base URLs for EU and US tenants. Body size capped at 1 MiB and every response carries an X-Trace-Id header for support.

- **Human URL:** [https://docs.port.io/api-reference/port-api](https://docs.port.io/api-reference/port-api)
- **Base URL:** `https://api.port.io`

#### Tags

- REST API
- Platform

#### Properties

- [Documentation](https://docs.port.io/api-reference/port-api)
- [Base U R L](https://api.us.port.io)
- [Postman Collection](collections/port-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/port-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Port Blueprints API

Endpoints to create, read, update, and delete blueprints - the schemas that define an organization's data model in the Port catalog (services, environments, AI agents, cloud resources, etc.).

- **Human URL:** [https://docs.port.io/api-reference/port-api](https://docs.port.io/api-reference/port-api)
- **Base URL:** `https://api.port.io`

#### Tags

- Blueprints
- Schema
- Catalog

#### Properties

- [Documentation](https://docs.port.io/api-reference/port-api)
- [Postman Collection](collections/port-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/port-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Port Entities API

Endpoints to create, search, update, and delete entities (instances of a blueprint) in the Port catalog, plus bulk operations and relations.

- **Human URL:** [https://docs.port.io/api-reference/port-api](https://docs.port.io/api-reference/port-api)
- **Base URL:** `https://api.port.io`

#### Tags

- Entities
- Catalog

#### Properties

- [Documentation](https://docs.port.io/api-reference/port-api)
- [Postman Collection](collections/port-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/port-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Port Actions API

Endpoints to manage self-service actions on blueprints and entities - day-2 operations, scaffolding, and workflows that developers run from the Port UI or programmatically.

- **Human URL:** [https://docs.port.io/api-reference/port-api](https://docs.port.io/api-reference/port-api)
- **Base URL:** `https://api.port.io`

#### Tags

- Actions
- Self-Service

#### Properties

- [Documentation](https://docs.port.io/api-reference/port-api)
- [Postman Collection](collections/port-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/port-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Port Action Runs API

Endpoints to trigger action runs, fetch their status and logs, post progress updates from external runners, and approve or reject pending runs.

- **Human URL:** [https://docs.port.io/api-reference/port-api](https://docs.port.io/api-reference/port-api)
- **Base URL:** `https://api.port.io`

#### Tags

- Action Runs
- Workflows

#### Properties

- [Documentation](https://docs.port.io/api-reference/port-api)
- [Postman Collection](collections/port-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/port-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Port Workflows API

Endpoints to define and orchestrate multi-step workflows that chain Port actions, integration runs, and approvals.

- **Human URL:** [https://docs.port.io/api-reference/port-api](https://docs.port.io/api-reference/port-api)
- **Base URL:** `https://api.port.io`

#### Tags

- Workflows
- Orchestration

#### Properties

- [Documentation](https://docs.port.io/api-reference/port-api)
- [Postman Collection](collections/port-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/port-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Port Scorecards API

Endpoints to manage scorecards (production readiness, security, SLO compliance, etc.) and query scores per entity.

- **Human URL:** [https://docs.port.io/api-reference/port-api](https://docs.port.io/api-reference/port-api)
- **Base URL:** `https://api.port.io`

#### Tags

- Scorecards
- Quality

#### Properties

- [Documentation](https://docs.port.io/api-reference/port-api)
- [Postman Collection](collections/port-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/port-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Port Integrations API

Endpoints to register, configure, and ingest data from Port integrations (Ocean), including resync, mapping configuration, and integration lifecycle.

- **Human URL:** [https://docs.port.io/api-reference/port-api](https://docs.port.io/api-reference/port-api)
- **Base URL:** `https://api.port.io`

#### Tags

- Integrations
- Ocean
- Ingestion

#### Properties

- [Documentation](https://docs.port.io/api-reference/port-api)
- [Postman Collection](collections/port-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/port-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Port Webhooks API

Endpoints to register webhook subscriptions and to receive inbound webhook events from upstream systems for ingestion into the Port catalog.

- **Human URL:** [https://docs.port.io/api-reference/port-api](https://docs.port.io/api-reference/port-api)
- **Base URL:** `https://api.port.io`

#### Tags

- Webhooks
- Events

#### Properties

- [Documentation](https://docs.port.io/api-reference/port-api)
- [Postman Collection](collections/port-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/port-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Port Teams and Users API

Endpoints to manage teams, users, roles, and team-membership for the Port organization.

- **Human URL:** [https://docs.port.io/api-reference/port-api](https://docs.port.io/api-reference/port-api)
- **Base URL:** `https://api.port.io`

#### Tags

- Teams
- Users
- RBAC

#### Properties

- [Documentation](https://docs.port.io/api-reference/port-api)
- [Postman Collection](collections/port-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/port-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Port Audit API

Endpoints to query Port audit logs for catalog, action, integration, and administrative events.

- **Human URL:** [https://docs.port.io/api-reference/port-api](https://docs.port.io/api-reference/port-api)
- **Base URL:** `https://api.port.io`

#### Tags

- Audit
- Compliance

#### Properties

- [Documentation](https://docs.port.io/api-reference/port-api)
- [Postman Collection](collections/port-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/port-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Port AI and LLM Management API

Endpoints to manage AI agents, prompts, memory, and LLM-driven capabilities embedded in the Port platform.

- **Human URL:** [https://docs.port.io/api-reference/port-api](https://docs.port.io/api-reference/port-api)
- **Base URL:** `https://api.port.io`

#### Tags

- AI
- LLM
- Agents

#### Properties

- [Documentation](https://docs.port.io/api-reference/port-api)
- [Postman Collection](collections/port-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/port-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Port Pages, Apps, and Plugins API

Endpoints to manage portal pages, apps, and plugin extensions that compose the developer-facing surface of the Port IDP.

- **Human URL:** [https://docs.port.io/api-reference/port-api](https://docs.port.io/api-reference/port-api)
- **Base URL:** `https://api.port.io`

#### Tags

- Pages
- Apps
- Plugins

#### Properties

- [Documentation](https://docs.port.io/api-reference/port-api)
- [Postman Collection](collections/port-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/port-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Port Ocean Integration Framework

Open-source framework used to build Port integrations that ingest data from third-party systems into the catalog. Maintained at github.com/port-labs/ocean.

- **Human URL:** [https://github.com/port-labs/ocean](https://github.com/port-labs/ocean)
- **Base URL:** `https://github.com/port-labs/ocean`

#### Tags

- Open Source
- Integrations
- Framework

#### Properties

- [Repository](https://github.com/port-labs/ocean)
- [Postman Collection](collections/port-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/port-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/getport)
- [Website](https://www.port.io/)
- [Documentation](https://docs.port.io/)
- [Git Hub](https://github.com/port-labs)
- [Plans](plans/port-io-plans-pricing.yml)
- [Rate Limits](rate-limits/port-io-rate-limits.yml)
- [Fin Ops](finops/port-io-finops.yml)
- [Integrations](https://docs.port.io/build-your-software-catalog/sync-data-to-catalog/)
- [L L Ms Txt](https://docs.port.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
