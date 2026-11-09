# Public project directory

[← Profile](README.md)

A map of 20 public project repositories, grouped by responsibility. Follow each repository for its implementation, operating contracts, and current verification/release scope.

The labels describe project scope; they do not imply uniform maturity or a single integrated deployment.

## Code and execution infrastructure

| Repository | Stack | Scope |
| :--- | :--- | :--- |
| [quanta-codeagent-v3](https://github.com/josongmin/quanta-codeagent-v3) | TypeScript / Bun | Coding agent runtime, streaming tools, versioned sessions, permission boundaries, and SDK embedding. |
| [quanta-index](https://github.com/josongmin/quanta-index) | Rust | Typed ingestion, immutable index generations, publication/activation, retrieval, and producer SDK. |
| [quanta-taskmesh](https://github.com/josongmin/quanta-taskmesh) | Rust | Bounded admission, fairness, resource budgets, executor topology, and worker custody. |
| [quanta-memory-platform](https://github.com/josongmin/quanta-memory-platform) | Rust | Memory budgets, accounting authority, ownership transfer, retained stores, and reclaim. |
| [quanta-gqlang-v2](https://github.com/josongmin/quanta-gqlang-v2) | Rust | Query-language frontend, semantic analysis, normalized IR, and checked execution documents. |
| [quanta-tantivy-sstable](https://github.com/josongmin/quanta-tantivy-sstable) | Rust | Budget-aware Tantivy SSTable patch; preserves upstream provenance and format documentation. |

## Developer workbenches and interfaces

| Repository | Stack | Scope |
| :--- | :--- | :--- |
| [quanta-ai-ide-v2](https://github.com/josongmin/quanta-ai-ide-v2) | React / TypeScript / Tauri | Registered workbench surfaces, code visualization, agent integration, and UI architecture checks. |
| [quanta-ide](https://github.com/josongmin/quanta-ide) | TypeScript / React / Tauri | IDE monorepo with shared canvas/shell libraries and separately composed product interfaces. |
| [quanta-terminal](https://github.com/josongmin/quanta-terminal) | Rust / TypeScript | PTY execution, terminal state, event replay, and desktop/editor surfaces. |
| [quanta-nextjs-ide](https://github.com/josongmin/quanta-nextjs-ide) | React / TypeScript / Vite | Vite workbench for Next.js-oriented route analysis, Monaco editing, and diagnostics. |
| [quanta-code-city](https://github.com/josongmin/quanta-code-city) | React / Three.js | 3D code-city prototype using sample metrics and dependency relationships. |
| [semantica-ai-ide](https://github.com/josongmin/semantica-ai-ide) | React / TypeScript | Agent-session UI, protocol/kernel packages, editor surfaces, and a local WebSocket daemon. |

## Search, data, and platform work

| Repository | Stack | Scope |
| :--- | :--- | :--- |
| [wine-search-engine](https://github.com/josongmin/wine-search-engine) | TypeScript / Fastify | Query planning, hybrid retrieval, ranking, snapshot publication, and Vespa/PostgreSQL/Redis adapters. |
| [recommandation-ml-w](https://github.com/josongmin/recommandation-ml-w) | Python | Event ingestion, feature datasets/manifests, model training/evaluation, and recommendation serving. |
| [crawler-engine-web-w](https://github.com/josongmin/crawler-engine-web-w) | Python / Playwright / React | Browser/session primitives, registered site adapters, and an admin backend/UI. |
| [crawler-engine-w](https://github.com/josongmin/crawler-engine-w) | Specifications / runbooks | Crawler-engine design: workflow/execution authority, raw replay, lineage, and egress controls. |
| [p0-platform](https://github.com/josongmin/p0-platform) | TypeScript / Bun | Identity, organizations, subscriptions, entitlements, metering, and audit infrastructure. |

## Earlier foundations

| Repository | Stack | Scope |
| :--- | :--- | :--- |
| [semantica-codegraph](https://github.com/josongmin/semantica-codegraph) | Python | Earlier code intelligence implementation: parsing, code graphs, hybrid retrieval, CLI/HTTP/MCP. |
| [semantica-copilot](https://github.com/josongmin/semantica-copilot) | Python / LangGraph | Code-understanding pipeline with intent planning, Codegraph retrieval, and answer generation. |
| [semantica-task-engine](https://github.com/josongmin/semantica-task-engine) | Rust / SQLite | Local job orchestration, subprocess execution, scheduling, recovery, and JSON-RPC clients. |

[Return to the selected work →](README.md#selected-work)
