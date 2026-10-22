# Hi, I'm Starlin 👋
### Staff Software Engineer & Solutions Architect | Full-Stack, Distributed Systems & AI Engineering

[![GitHub: Starlin](https://img.shields.io/badge/GitHub-starl1n-181717.svg?logo=github)](https://github.com/starl1n)
[![Specialization: Enterprise Systems](https://img.shields.io/badge/Focus-Multi--Tenant%20%7C%20AI%20Runtime%20%7C%20Event--Driven-blue.svg)](https://github.com/starl1n)
[![Available: Strategic Roles](https://img.shields.io/badge/Status-Open%20to%20High--Impact%20Opportunities-success.svg)](https://github.com/starl1n)

> I architect, build, and scale production-grade software ecosystems—spanning high-throughput backend services, multi-tenant enterprise applications, and autonomous AI agent runtimes.

---

## 🏛️ Featured Production Architecture Blueprints

### 1. 🏢 [Nexus Enterprise Suite](https://github.com/starl1n/nexus-enterprise-suite)
> **Stack:** `.NET 10` · `C#` · `React 19` · `Expo (React Native)` · `EF Core 10` · `Docker`
* **Zero-Leak Multi-Tenancy:** Automated database-level Row-Level Security (RLS) via Entity Framework Core Global Query Filters; tenant identity resolved strictly from validated JWT claims.
* **Unified API Contracts:** Predictable `ApiResponse<T>` envelopes and typed pagination across Web and Mobile.
* **100% Verified:** Includes automated xUnit test suites verifying cross-tenant data isolation.

---

### 2. 🤖 [Agentic AI Runtime](https://github.com/starl1n/agentic-ai-runtime)
> **Stack:** `Python 3.12+` · `FastAPI` · `Pydantic v2` · `SSE Streaming` · `Pytest Asyncio`
* **Autonomous Reasoning (ReAct):** Multi-step tool-calling loops executing typed analytical queries and financial calculations.
* **Resilient Multi-Provider Fallback:** Automatic failover circuit (Claude ↔ GPT-4o ↔ Gemini) mitigating third-party rate limits and outages.
* **Fiscal Cost Guardrails:** Real-time token and USD cost tracking ($/1M tokens) with automated budget limit cutoffs.

---

### 3. ⚡ [Resilient Worker Core](https://github.com/starl1n/resilient-worker-core)
> **Stack:** `Node.js 22+` · `TypeScript (Strict)` · `Fastify` · `Zod` · `Vitest` · `Pino`
* **Strict Idempotency:** Zero double-processing guarantee for financial transactions and webhooks using atomic key deduplication (`X-Idempotent-Replay`).
* **Priority Queue & Backoff:** Priority-weighted scheduling (Critical > High > Normal > Low) with randomized jitter backoff.
* **Dead-Letter Queue (DLQ):** Automated isolation of unrecoverable jobs with manual re-enqueue recovery APIs and end-to-end `x-trace-id` correlation.

---

## 🛠️ Core Engineering Stack

```
Backend:           .NET 10 / C#, ASP.NET Core, Node.js 22+, Python 3.12+, FastAPI, Fastify
Frontend:          React 19, React Router 7, TypeScript (Strict), Vite, Tailwind CSS v4
Mobile:            Expo 54+, React Native, Expo Router, SecureStore
Data & Queues:     PostgreSQL, SQL Server, Redis, SQLite, EF Core, Drizzle/Prisma
AI & LLMs:         Autonomous Agents (ReAct), Tool Calling, Pydantic v2, Multi-Provider Fallbacks
DevOps & Quality:  Docker, GitHub Actions, xUnit, Pytest, Vitest, Structured Logging (Pino, Serilog)
```

---

## 📬 Connect & Collaborate
- **GitHub:** [@starl1n](https://github.com/starl1n)
- Interested in consulting, architectural reviews, or full-time Staff / Lead engineering opportunities? Feel free to reach out via GitHub or email.
