# hypesiege-test

Independent acceptance organization for **hypesiege**.

Buffer-style clients, API/websocket, Flutter/web, providers, scheduler, media, sync, CLI, and MCP acceptance.

## Portfolio

| Repository | Class | Readiness | Primary dependency path |
|---|---|---|---|
| `clients-consumer-matrix` | SDK consumer | `ready` | `matrix` |
| `api-websocket-contract` | API contract | `ready` | `matrix` |
| `flutter-app-e2e` | mobile/emulator | `ready` | `matrix` |
| `web-framework-variants` | browser E2E | `ready` | `matrix` |
| `social-provider-adapters` | provider adapter | `ready` | `matrix` |
| `scheduler-idempotency` | scheduler/failover | `ready` | `matrix` |
| `media-upload-transcoding` | media pipeline | `ready` | `matrix` |
| `opto-sync-integration` | synchronization | `ready` | `matrix` |
| `cli-mcp-contract` | MCP contract | `ready` | `matrix` |

Pull requests run deterministic harness checks. Emulators, desktop matrices, live APIs/providers, databases, chaos, scale, and soaks are scheduled/manual. Missing upstreams or credentials are blocked readiness—not false passes or product regressions.

<!-- org-project-routing:start -->
## Planning and delivery

- [GitHub Project: hypesiege-test-project](https://github.com/orgs/hypesiege-test/projects/1)
- [Linear planning project](https://linear.app/denman/project/githubcomhypesiege-test-0a9c57b67742)
- [Detailed project-routing contract](../docs/PROJECTS.md)

GitHub owns code and delivery evidence; Linear owns planning and dependencies. The linked organization Project provides the cross-repository execution view.
<!-- org-project-routing:end -->
