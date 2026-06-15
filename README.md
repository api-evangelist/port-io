# Port (port-io)

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
