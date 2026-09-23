# Piyush Raj Singh

**AI Systems Engineer — agent runtimes, backend systems, and production TypeScript & Python.**

I build AI systems end to end: the agent loop, the API, the database, the deployment, and the failure handling. Not demos — systems with tests, CI, and a documented design.

---

## What I work on

| Area | What that means concretely |
|---|---|
| **Agent runtimes** | Execution loops, tool-call permission gating with audit logs, mode management |
| **Backend systems** | Domain-tested APIs on PostgreSQL (auth, contacts, workflows, inbox), containerised deployment |
| **Automation pipelines** | Scheduled multi-stage pipelines with orchestration, fact-checking, and quality gates |
| **Developer tooling** | CLI products with typed configuration, release automation, and cross-platform installers |
| **Applied AI** | Multi-provider LLM abstraction, embeddings and memory subsystems, prompt libraries |

---

## Selected work

### 🔧 Signhify CLI — agent developer tool
A Turborepo monorepo CLI with an agent execution loop, a tool permission engine, and configurable operating modes. Typed config validated against JSON Schema, cross-platform installers, and a five-stage CI pipeline (lint · test · typecheck · release · CI).
`TypeScript` · `Turborepo` · `Vitest` · `GitHub Actions`

→ [`Signhify_CLI`](https://github.com/Warriorlegacy/Signhify_CLI)

### 🧩 CRM — multi-tenant backend platform
Backend platform covering authentication, contacts, follow-up workflows, and inbox handling, backed by Prisma/PostgreSQL with Docker and nginx deployment. Domain logic is covered by unit tests across all four areas.
`TypeScript` · `PostgreSQL` · `Prisma` · `Docker`

→ [`CRM`](https://github.com/Warriorlegacy/CRM)

### 🎨 DXFVec — image vectorisation & DXF conversion
A focused Python tool that vectorises raster images and converts them to DXF with no external API dependency — emitting native ARC/CIRCLE entities via Taubin/Kasa least-squares circle fitting. Two production bugs found by end-to-end testing and fixed with regression tests; 158-test suite, reproducible benchmark harness, CI green, ships containerised.
`Python` · `OpenCV` · `ezdxf` · `Docker` · `pytest`

→ [`dxfvec`](https://github.com/Warriorlegacy/dxfvec)

### 🎬 Autogram — autonomous content pipeline
A Python content pipeline driven by nine scheduled workflows: source fetching → topic scoring → carousel architecture → fact-checking → quality gate → deterministic Playwright rendering → CDN staging → publishing, with an operational dashboard API.
`Python` · `Playwright` · `GitHub Actions`

→ [`Autogram`](https://github.com/Warriorlegacy/Autogram)

### 🛠 Signhify Studio — AI product platform
A platform for shipping AI products, built on a relational schema with migrations, a secrets abstraction layer, Playwright smoke tests, and a unit suite.
`TypeScript` · `Supabase` · `Playwright`

→ [`Signhify_Studio`](https://github.com/Warriorlegacy/Signhify_Studio)

---

## How I build

- **Tests before claims.** Domain logic is covered by tests, and every repository states what is *not* finished.
- **CI on every project.** Lint → typecheck → test → build.
- **Diagrams in the repo.** Architecture is Mermaid in version control, not a screenshot.
- **Documented trade-offs.** Design decisions are recorded as ADRs, including the ones I'd revisit.
- **Honest scope.** A Limitations section is not optional.

---

## Stack

**Languages** — TypeScript · Python · SQL
**Frontend** — React · Next.js
**Backend** — Node.js · Prisma · PostgreSQL · Supabase
**AI** — LLM provider APIs · embeddings · vector retrieval · agent orchestration
**Infra** — Docker · GitHub Actions · Vercel · Render · Railway
**Quality** — Vitest · pytest · Playwright

---

## Currently

Building agent and RAG systems with a focus on evaluation and observability — measuring retrieval quality, tracking token cost, and instrumenting agent traces rather than guessing.

Open to **remote AI engineering / backend engineering** roles.

---

📫 **Contact** — [LinkedIn](https://www.linkedin.com/in/piyushraj-singh) · [GitHub](https://github.com/Warriorlegacy)

---

<sub>Every technical claim above maps to a file, a test, or a workflow in the linked repository.</sub>
