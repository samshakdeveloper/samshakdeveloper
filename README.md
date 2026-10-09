<h1 align="center">Sam Shak</h1>

<p align="center">
  <strong>Senior Backend Engineer · Documentation-Driven · Independent Contractor</strong><br/>
  Remote, written, async-first
</p>

<p align="center">
  <a href="mailto:samshakdeveloper@proton.me">Email</a> ·
  <a href="https://t.me/sam_shak">Telegram</a> ·
  <a href="./Sam-Shak-Working-Terms.pdf">Working Terms (PDF)</a>
</p>

---

## About

I design and build backend systems that other engineers can run, understand, and take over without me. Ten-plus years of programming, focused on event-driven architecture, observability, and crypto payment infrastructure, with every decision and every operation written down.

My work is meant to be judged by what is in the repository: the architecture, the code, the tests, and the documentation.

## How I work

| Principle | In practice |
| --- | --- |
| **Documentation ships with the code** | Docs change in the same pull request as the implementation, never "later". |
| **Decisions are recorded** | Architecture Decision Records (ADRs) capture the context, the options considered, and the trade-offs. |
| **Operations are written down** | Runbooks cover setup, deployment, monitoring, and recovery. |
| **No key-person risk** | Another engineer can pick up the project from the documentation alone. |
| **Written and async** | Text-only communication, always online, quick to respond. |

## Featured project: Nexus Enterprise

An event-driven TypeScript monorepo built to demonstrate enterprise-grade Node.js standards: business logic decoupled from frameworks, asynchronous messaging, containerized deployment, and end-to-end tracing.

**Repository:** [`nexus-enterprise`](https://github.com/samshakdeveloper/nexus-enterprise)

| Area | What it demonstrates |
| --- | --- |
| **Architecture** | Domain-Driven Design, Hexagonal Architecture (ports and adapters), and CQRS. Domain and application layers stay framework-agnostic. |
| **Messaging** | Event-driven integration on Apache Kafka, using the Outbox Pattern for reliable event publishing. |
| **API and gateway** | Fastify services with a GraphQL Mesh gateway. Redis for caching. |
| **Type safety** | Strict TypeScript with Zod schema contracts end to end. |
| **Observability** | OpenTelemetry tracing with a Grafana-based monitoring stack. |
| **Platform** | Docker Compose for local development, Kubernetes manifests, and Argo CD application definitions (GitOps). |
| **Quality gates** | GitHub Actions CI, Vitest, ESLint, Prettier, Husky pre-commit hooks, lint-staged, and Conventional Commits enforced by commitlint. |
| **Developer velocity** | Turborepo build caching across the workspace. |

Start with the repository README: architecture overview, workspace topology, and the getting-started guide.

## Core stack

| Domain | Technologies |
| --- | --- |
| **Backend** | Node.js, TypeScript, Fastify, GraphQL, GraphQL Mesh, REST, webhooks |
| **Architecture** | DDD, CQRS, Hexagonal Architecture, event-driven design, Outbox Pattern |
| **Messaging and data** | Apache Kafka, Redis, MongoDB |
| **Observability** | OpenTelemetry, Grafana |
| **Infrastructure** | Docker, Kubernetes, Argo CD, GitHub Actions, Turborepo |
| **Quality** | Vitest, ESLint, Prettier, Zod, commitlint, Husky |
| **Also worked with** | Express, Ethers.js, Web3.js, EVM event listening, on-chain USDT settlement, OpenAI APIs, RAG, vector search, Telegram bot engines |

## Working together

I take on remote backend engineering work as an independent contractor. The terms are short and explicit: [**Working Terms (PDF)**](./Sam-Shak-Working-Terms.pdf).

- **Instead of an interview:** I will complete a small, well-defined task (under one day) and push the source, so you can assess the result directly.
- **Before we start:** review the code and documentation in this profile and confirm you are comfortable with the style.
- **Fit:** my terms are built around the work. Teams that evaluate a contractor by deliverable quality (architecture, code, tests, documentation) are the right match.

## Contact

Written communication only.

- **Email:** [samshakdeveloper@proton.me](mailto:samshakdeveloper@proton.me)
- **Telegram:** [@sam_shak](https://t.me/sam_shak)
