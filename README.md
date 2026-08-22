# Union.ai (unionai)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/unionai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/unionai/refs/heads/main/apis.yml)

## Tags

- AI
- ML
- Orchestration
- Workflows
- MLOps
- Flyte
- Serverless

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Union FlyteAdmin Projects API

Create, update, list, and get Projects and the Domains scoped within them - the top-level logical grouping for workflows, tasks, launch plans, and executions. gRPC (FlyteIDL AdminService) with an HTTP/JSON gateway under /api/v1/projects.

- **Human URL:** [https://www.union.ai/docs/flyte/api-reference/](https://www.union.ai/docs/flyte/api-reference/)
- **Base URL:** `https://<your-org>.app.union.ai/api/v1`

#### Tags

- Projects
- Domains
- Control Plane

#### Properties

- [Documentation](https://www.union.ai/docs/flyte/user-guide/core-concepts/projects-and-domains/)
- [API Reference](https://www.union.ai/docs/flyte/api-reference/)
- [OpenAPI](openapi/unionai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/unionai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/unionai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/unionai)

### Union FlyteAdmin Workflows API

Register, list, and retrieve versioned Workflows - the compiled DAGs of tasks. Served over gRPC with an HTTP/JSON gateway under /api/v1/workflows and /api/v1/workflow_ids.

- **Human URL:** [https://www.union.ai/docs/flyte/api-reference/](https://www.union.ai/docs/flyte/api-reference/)
- **Base URL:** `https://<your-org>.app.union.ai/api/v1`

#### Tags

- Workflows
- Registration
- Control Plane

#### Properties

- [Documentation](https://www.union.ai/docs/flyte/user-guide/core-concepts/workflows/)
- [API Reference](https://www.union.ai/docs/flyte/api-reference/)
- [OpenAPI](openapi/unionai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/unionai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/unionai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/unionai)

### Union FlyteAdmin Tasks API

Register, list, and retrieve versioned Tasks - the strongly-typed units of work that compose workflows. gRPC AdminService with an HTTP/JSON gateway under /api/v1/tasks and /api/v1/task_ids.

- **Human URL:** [https://www.union.ai/docs/flyte/api-reference/](https://www.union.ai/docs/flyte/api-reference/)
- **Base URL:** `https://<your-org>.app.union.ai/api/v1`

#### Tags

- Tasks
- Registration
- Control Plane

#### Properties

- [Documentation](https://www.union.ai/docs/flyte/user-guide/core-concepts/tasks/)
- [API Reference](https://www.union.ai/docs/flyte/api-reference/)
- [OpenAPI](openapi/unionai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/unionai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/unionai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/unionai)

### Union FlyteAdmin Launch Plans API

Create, list, retrieve, and activate/deactivate Launch Plans - the bindable, schedulable entry points that wrap a workflow with inputs, schedules, and notifications. HTTP/JSON gateway under /api/v1/launch_plans and /api/v1/active_launch_plans.

- **Human URL:** [https://www.union.ai/docs/flyte/api-reference/](https://www.union.ai/docs/flyte/api-reference/)
- **Base URL:** `https://<your-org>.app.union.ai/api/v1`

#### Tags

- Launch Plans
- Schedules
- Control Plane

#### Properties

- [Documentation](https://www.union.ai/docs/flyte/user-guide/core-concepts/launch-plans/)
- [API Reference](https://www.union.ai/docs/flyte/api-reference/)
- [OpenAPI](openapi/unionai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/unionai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/unionai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/unionai)

### Union FlyteAdmin Executions API

Launch, relaunch, recover, list, get, terminate, and inspect Workflow Executions, plus their Node Executions and Task Executions and associated I/O data. HTTP/JSON gateway under /api/v1/executions, /api/v1/node_executions, and /api/v1/task_executions.

- **Human URL:** [https://www.union.ai/docs/flyte/api-reference/](https://www.union.ai/docs/flyte/api-reference/)
- **Base URL:** `https://<your-org>.app.union.ai/api/v1`

#### Tags

- Executions
- Runs
- Control Plane

#### Properties

- [Documentation](https://www.union.ai/docs/flyte/user-guide/development-cycle/remote-management/remote-examples/)
- [API Reference](https://www.union.ai/docs/flyte/api-reference/)
- [OpenAPI](openapi/unionai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/unionai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/unionai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/unionai)

### Union Serverless

The fully-managed, pay-as-you-go Union control plane and compute. Same FlyteAdmin control-plane surface (gRPC + HTTP/JSON gateway) accessed through the union CLI and Union SDK, billed per action and per second of allocated CPU / Memory / GPU.

- **Human URL:** [https://www.union.ai/docs/serverless/](https://www.union.ai/docs/serverless/)
- **Base URL:** `https://serverless.union.ai/api/v1`

#### Tags

- Serverless
- Compute
- Pay-as-you-go

#### Properties

- [Documentation](https://www.union.ai/blog-post/introducing-union-serverless)
- [API Reference](https://www.union.ai/docs/serverless/api-reference/union-sdk/)
- [OpenAPI](openapi/unionai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GitHub](https://github.com/unionai)

### Union CLI & SDK

The union and pyflyte command-line tools plus the Flytekit and Union Python SDKs - the primary, fully-documented clients that register entities and drive the FlyteAdmin control plane (including Actors and Artifacts) over gRPC.

- **Human URL:** [https://www.union.ai/docs/flyte/api-reference/](https://www.union.ai/docs/flyte/api-reference/)
- **Base URL:** `https://<your-org>.app.union.ai/api/v1`

#### Tags

- CLI
- SDK
- Flytekit
- pyflyte

#### Properties

- [Documentation](https://www.union.ai/docs/serverless/api-reference/union-sdk/)
- [API Reference](https://www.union.ai/docs/flyte/api-reference/pyflyte-cli/)
- [API Reference](https://www.union.ai/docs/byoc/api-reference/union-cli/)
- [GitHub](https://github.com/unionai)

## Common Properties

- [GitHub Organization](https://github.com/unionai)
- [GitHub Organization](https://github.com/flyteorg)
- [LinkedIn](https://www.linkedin.com/company/unionai)
- [Website](https://www.union.ai)
- [Documentation](https://www.union.ai/docs)
- [Plans](plans/unionai-plans-pricing.yml)
- [Rate Limits](rate-limits/unionai-rate-limits.yml)
- [Fin Ops](finops/unionai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
