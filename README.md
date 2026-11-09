<p align="center"><img src="readme-banner.svg" alt="Code Intelligence / Systems — Typed contracts, explicit authority, and inspectable execution." width="100%"></p>

# Code intelligence and execution infrastructure

**Building systems for code intelligence, deterministic verification, and AI-native software engineering.**

I work on Rust search, execution, and memory infrastructure, connected to TypeScript/Python agents and developer tools. The repositories pair implementation with architecture decisions, operating contracts, and verification procedures.

## Selected systems

| Project | Problem | Foundation |
| --- | --- | --- |
| [Quanta Index](https://github.com/josongmin/quanta-index) | Typed ingestion, code retrieval, index generations, and activation | Rust · Search infrastructure |
| [Quanta Taskmesh](https://github.com/josongmin/quanta-taskmesh) | Admission, fairness, budgets, cancellation, and worker capacity | Rust · Execution governance |
| [Quanta Memory Platform](https://github.com/josongmin/quanta-memory-platform) | Memory budgeting, accounting, ownership transfer, and reclaim | Rust · Resource management |
| [Quanta CodeAgent v3](https://github.com/josongmin/quanta-codeagent-v3) | Tool execution, permissions, sessions, and context management | TypeScript · Bun |
| [Quanta GQLang](https://github.com/josongmin/quanta-gqlang-v2) | Query-language syntax, types, semantics, and checked execution documents | Rust · Language frontend |
| [Tantivy SSTable patch](https://github.com/josongmin/quanta-tantivy-sstable) | Admission before ordinal decoding and guard-carrying results | Rust · Storage integration |


## Engineering priorities

- **Explicit ownership:** separate contracts, domain logic, storage, execution, and presentation.
- **Visible failure:** reject invalid inputs, missing authority, and exhausted resources explicitly.
- **Reproducible verification:** bind results to source, inputs, and the environment that produced them.
- **Operational constraints:** account for cancellation, recovery, observability, capacity, and cost.

Implementation, verification, consumer integration, and release status are tracked separately in each repository.

## Interfaces and visualization

- [Quanta IDE](https://github.com/josongmin/quanta-ide): a modular IDE workspace with shared libraries and mountable product interfaces.
- [Quanta AI IDE v2](https://github.com/josongmin/quanta-ai-ide-v2): a codebase visualization workbench.
- [Quanta Terminal](https://github.com/josongmin/quanta-terminal): a terminal with a Rust core and TypeScript interface.
- [Quanta Code City](https://github.com/josongmin/quanta-code-city): a 3D prototype for spatial code metrics.

- [Quanta Next.js IDE](https://github.com/josongmin/quanta-nextjs-ide): a Vite-based workbench for Next.js-oriented route analysis.
- [Semantica AI IDE](https://github.com/josongmin/semantica-ai-ide): agent-session UI, protocol/kernel packages, and a local daemon.

## Search, data, and earlier work

- [Wine Search Engine](https://github.com/josongmin/wine-search-engine): wine retrieval, ranking, and agent APIs.
- [Wine Recommendation](https://github.com/josongmin/recommandation-ml-w): event data, feature pipelines, model training, and recommendation serving.
- [Semantica Codegraph](https://github.com/josongmin/semantica-codegraph): the earlier Python code graph and hybrid retrieval implementation.
- [Semantica Copilot](https://github.com/josongmin/semantica-copilot): code understanding through the Codegraph API.

## Platform and collection

- [P0 Platform](https://github.com/josongmin/p0-platform): identity, organizations, subscriptions, entitlements, usage, and audit.
- [Semantica Task Engine](https://github.com/josongmin/semantica-task-engine): SQLite-backed local job orchestration and subprocess recovery.
- [Wine Crawler Workspace](https://github.com/josongmin/crawler-engine-web-w): registered Playwright site adapters and an admin surface.
- [Crawler Engine Design](https://github.com/josongmin/crawler-engine-w): workflow/execution authority, raw replay, lineage, and operating specifications.
