# Union.ai (unionai)

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
