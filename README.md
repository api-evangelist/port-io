# Port

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

Port is an Internal Developer Portal built around an API-first software catalog, customizable blueprints and entities, self-service actions, and scorecards. Platform teams model their own domain (services, environments, pipelines, AI agents, cloud resources) as blueprints, ingest data from integrations (GitHub, GitLab, AWS, Azure, GCP, Kubernetes, Datadog, PagerDuty, Snyk, ServiceNow), and expose developer workflows as self-service actions backed by GitHub Actions, GitLab pipelines, Jenkins, Argo, or webhooks. Everything in Port - blueprints, entities, actions, runs, scorecards, integrations, pages, webhooks, AI agents - is reachable via the public REST API.

**Areas:** Internal Developer Portal · Service Catalog · Self-Service Actions · Platform Engineering · Scorecards · Developer Experience · Developer Portal

## Port on APIs.io

Everything profiled for Port is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/port-io/](https://apis.io/providers/port-io/)** — or go straight to one of the APIs or properties below.

### APIs (32)

- [Port REST API](https://apis.io/apis/port-io/rest-api/) — Public REST API for the Port platform. Bearer-token authenticated (3-hour tokens minted from Port credentials), with regional base URLs for EU and US…
- [Port Blueprints API](https://apis.io/apis/port-io/blueprints/) — Endpoints to create, read, update, and delete blueprints - the schemas that define an organization's data model in the Port catalog (services, environments,…
- [Port Entities API](https://apis.io/apis/port-io/entities/) — Endpoints to create, search, update, and delete entities (instances of a blueprint) in the Port catalog, plus bulk operations and relations.
- [Port Actions API](https://apis.io/apis/port-io/actions/) — Endpoints to manage self-service actions on blueprints and entities - day-2 operations, scaffolding, and workflows that developers run from the Port UI or…
- [Port Action Runs API](https://apis.io/apis/port-io/action-runs/) — Endpoints to trigger action runs, fetch their status and logs, post progress updates from external runners, and approve or reject pending runs.
- [Port Workflows API](https://apis.io/apis/port-io/workflows/) — Endpoints to define and orchestrate multi-step workflows that chain Port actions, integration runs, and approvals.
- [Port Scorecards API](https://apis.io/apis/port-io/scorecards/) — Endpoints to manage scorecards (production readiness, security, SLO compliance, etc.) and query scores per entity.
- [Port Integrations API](https://apis.io/apis/port-io/integrations/) — Endpoints to register, configure, and ingest data from Port integrations (Ocean), including resync, mapping configuration, and integration lifecycle.
- [Port Webhooks API](https://apis.io/apis/port-io/webhooks/) — Endpoints to register webhook subscriptions and to receive inbound webhook events from upstream systems for ingestion into the Port catalog.
- [Port Teams and Users API](https://apis.io/apis/port-io/teams-users/) — Endpoints to manage teams, users, roles, and team-membership for the Port organization.
- [Port Audit API](https://apis.io/apis/port-io/audit/) — Endpoints to query Port audit logs for catalog, action, integration, and administrative events.
- [Port AI and LLM Management API](https://apis.io/apis/port-io/ai-agents/) — Endpoints to manage AI agents, prompts, memory, and LLM-driven capabilities embedded in the Port platform.
- [Port Pages, Apps, and Plugins API](https://apis.io/apis/port-io/pages/) — Endpoints to manage portal pages, apps, and plugin extensions that compose the developer-facing surface of the Port IDP.
- [Port Ocean Integration Framework](https://apis.io/apis/port-io/ocean/) — Open-source framework used to build Port integrations that ingest data from third-party systems into the catalog. Maintained at github.com/port-labs/ocean.
- [Port Blueprints API](https://apis.io/apis/port-io/port-io-blueprints-api/) — Manage blueprint definitions in the software catalog.
- [Port Entities API](https://apis.io/apis/port-io/port-io-entities-api/) — Manage catalog entities created from blueprints.
- [Port Action Runs API](https://apis.io/apis/port-io/port-io-action-runs-api/) — The Action Runs API from Port — 6 operation(s) for action runs.
- [Port Actions API](https://apis.io/apis/port-io/port-io-actions-api/) — The Actions API from Port — 5 operation(s) for actions.
- [Port AI API](https://apis.io/apis/port-io/port-io-ai-api/) — The AI API from Port — 1 operation(s) for ai.
- [Port Apps API](https://apis.io/apis/port-io/port-io-apps-api/) — The Apps API from Port — 3 operation(s) for apps.
- [Port Audit API](https://apis.io/apis/port-io/port-io-audit-api/) — The Audit API from Port — 1 operation(s) for audit.
- [Port Authentication / Authorization API](https://apis.io/apis/port-io/port-io-authentication-authorization-api/) — The Authentication / Authorization API from Port — 2 operation(s) for authentication / authorization.
- [Port Folders API](https://apis.io/apis/port-io/port-io-folders-api/) — The Folders API from Port — 2 operation(s) for folders.
- [Port Integrations API](https://apis.io/apis/port-io/port-io-integrations-api/) — The Integrations API from Port — 4 operation(s) for integrations.
- [Port Migrations API](https://apis.io/apis/port-io/port-io-migrations-api/) — The Migrations API from Port — 3 operation(s) for migrations.
- [Port Organization API](https://apis.io/apis/port-io/port-io-organization-api/) — The Organization API from Port — 3 operation(s) for organization.
- [Port Pages API](https://apis.io/apis/port-io/port-io-pages-api/) — The Pages API from Port — 8 operation(s) for pages.
- [Port Scorecard Groups API](https://apis.io/apis/port-io/port-io-scorecard-groups-api/) — The Scorecard Groups API from Port — 3 operation(s) for scorecard groups.
- [Port Scorecards API](https://apis.io/apis/port-io/port-io-scorecards-api/) — The Scorecards API from Port — 3 operation(s) for scorecards.
- [Port Teams API](https://apis.io/apis/port-io/port-io-teams-api/) — The Teams API from Port — 2 operation(s) for teams.
- [Port Users API](https://apis.io/apis/port-io/port-io-users-api/) — The Users API from Port — 5 operation(s) for users.
- [Port Webhook API](https://apis.io/apis/port-io/port-io-webhook-api/) — The Webhook API from Port — 3 operation(s) for webhook.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Port Io Agentic Access](https://apis.io/agentic-access/port-io/port-io-agentic-access/)

#### Collections (3)

Postman and Open Collection request collections.

- [Port REST API](https://apis.io/collections/port-io/open-port-io/)
- [Port REST Blueprints API](https://apis.io/collections/port-io/open-port-io-blueprints-api/)
- [Port REST Blueprints Entities API](https://apis.io/collections/port-io/open-port-io-entities-api/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Port Io Authentication](https://apis.io/security/port-io/port-io-authentication/)
- [Port Io Domain Security](https://apis.io/security/port-io/port-io-domain-security/)
- [Port Io Trust Center](https://apis.io/security/port-io/port-io-trust-center/)
- [Port Io Vulnerability Disclosure](https://apis.io/security/port-io/port-io-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Port Io Plans Pricing](https://apis.io/plans/port-io/port-io-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Port Io Rate Limits](https://apis.io/rate-limits/port-io/port-io-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Port Io Finops](https://apis.io/finops/port-io/port-io-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.port.io/)
- [Documentation](https://docs.port.io/)

## API Evangelist rating

**Kin Score 26.0** — emerging · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 36.8 |
| Developer ergonomics | 21.4 |
| Access clarity | 13.2 |

**Agent readiness 19.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 22.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/port-io/](https://apis.io/providers/port-io/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Port: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/port-io/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
