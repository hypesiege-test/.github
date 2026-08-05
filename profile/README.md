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
