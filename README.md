# Union.ai

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

Union.ai is the commercial AI/ML orchestration platform built on the open-source Flyte project. It exposes the Flyte/Union control plane (the FlyteAdmin service) for registering and running strongly-typed workflows, tasks, and launch plans, plus Union Serverless, Actors, and Artifacts. The control plane is primarily a gRPC API (FlyteIDL AdminService) with an auto-generated HTTP/JSON gateway exposed under /api/v1/, driven by the union / pyflyte CLI and Flytekit / Union SDKs.

**Areas:** Artificial Intelligence · Machine Learning · Orchestration · Workflows · MLOps · Flyte · Serverless

## Union.ai on APIs.io

Everything profiled for Union.ai is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/unionai/](https://apis.io/providers/unionai/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Union CLI & SDK](https://apis.io/apis/unionai/union-cli-sdk/) — The union and pyflyte command-line tools plus the Flytekit and Union Python SDKs - the primary, fully-documented clients that register entities and drive…
- [Union.ai Domains API](https://apis.io/apis/unionai/unionai-domains-api/) — The Domains API from Union.ai — 1 operation(s) for domains.
- [Union.ai Executions API](https://apis.io/apis/unionai/unionai-executions-api/) — The Executions API from Union.ai — 6 operation(s) for executions.
- [Union.ai Launch Plans API](https://apis.io/apis/unionai/unionai-launch-plans-api/) — The Launch Plans API from Union.ai — 5 operation(s) for launch plans.
- [Union.ai Node Executions API](https://apis.io/apis/unionai/unionai-node-executions-api/) — The Node Executions API from Union.ai — 1 operation(s) for node executions.
- [Union.ai Projects API](https://apis.io/apis/unionai/unionai-projects-api/) — The Projects API from Union.ai — 2 operation(s) for projects.
- [Union.ai Tasks API](https://apis.io/apis/unionai/unionai-tasks-api/) — The Tasks API from Union.ai — 4 operation(s) for tasks.
- [Union.ai Version API](https://apis.io/apis/unionai/unionai-version-api/) — The Version API from Union.ai — 1 operation(s) for version.
- [Union.ai Workflows API](https://apis.io/apis/unionai/unionai-workflows-api/) — The Workflows API from Union.ai — 4 operation(s) for workflows.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Unionai Agentic Access](https://apis.io/agentic-access/unionai/unionai-agentic-access/)

#### Collections (9)

Postman and Open Collection request collections.

- [Union FlyteAdmin Control Plane API (HTTP/JSON Gateway)](https://apis.io/collections/unionai/open-unionai/)
- [Union FlyteAdmin Control Plane API (HTTP/JSON Gateway) Domains API](https://apis.io/collections/unionai/open-unionai-domains-api/)
- [Union FlyteAdmin Control Plane API (HTTP/JSON Gateway) Domains Executions API](https://apis.io/collections/unionai/open-unionai-executions-api/)
- [Union FlyteAdmin Control Plane API (HTTP/JSON Gateway) Domains Launch Plans API](https://apis.io/collections/unionai/open-unionai-launch-plans-api/)
- [Union FlyteAdmin Control Plane API (HTTP/JSON Gateway) Domains Node Executions API](https://apis.io/collections/unionai/open-unionai-node-executions-api/)
- [Union FlyteAdmin Control Plane API (HTTP/JSON Gateway) Domains Projects API](https://apis.io/collections/unionai/open-unionai-projects-api/)
- [Union FlyteAdmin Control Plane API (HTTP/JSON Gateway) Domains Tasks API](https://apis.io/collections/unionai/open-unionai-tasks-api/)
- [Union FlyteAdmin Control Plane API (HTTP/JSON Gateway) Domains Version API](https://apis.io/collections/unionai/open-unionai-version-api/)
- [Union FlyteAdmin Control Plane API (HTTP/JSON Gateway) Domains Workflows API](https://apis.io/collections/unionai/open-unionai-workflows-api/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Unionai Authentication](https://apis.io/security/unionai/unionai-authentication/)
- [Unionai Domain Security](https://apis.io/security/unionai/unionai-domain-security/)
- [Unionai Trust Center](https://apis.io/security/unionai/unionai-trust-center/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Unionai Scopes](https://apis.io/scopes/unionai/unionai-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Unionai Plans Pricing](https://apis.io/plans/unionai/unionai-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Unionai Rate Limits](https://apis.io/rate-limits/unionai/unionai-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Unionai Finops](https://apis.io/finops/unionai/unionai-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.union.ai)
- [Documentation](https://www.union.ai/docs)
- [Pricing](https://www.union.ai/pricing)
- [GitHub](https://github.com/unionai)

## API Evangelist rating

**Kin Score 35.0** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 45.6 |
| Contract governance | 0.0 |
| Operational transparency | 2.6 |
| Developer ergonomics | 29.8 |
| Access clarity | 50.0 |

**Agent readiness 24.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/unionai/](https://apis.io/providers/unionai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Union.ai: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/unionai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
