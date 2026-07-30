# 👋 Hey, I'm Javier

> *I build reliable data and AI systems by understanding how they fail.*

**Data & AI Engineer** in A Coruña, Spain 🇪🇸, working where production data pipelines meet AI-native applications. In my day job I own incident resolution across Snowflake, Kafka, and REST APIs at enterprise scale — triaging 100+ production incidents and shipping Python automation that **cut ~14 hrs/week of manual work and reduced data-readiness latency by ~80%**.

I bring that same production discipline to AI: I ship LLM and RAG systems with the engineering they actually need to be trusted in production — answer-quality eval gates, OpenTelemetry tracing, hardened APIs, and CI. Reliability, observability, and operational correctness are first principles for me, not afterthoughts.

---
## 🛠️ Stack

|                                   |                                                                                                                                                                                                                                                                                                                                                                   |
| --------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Programming & Querying**        | <img src="https://cdn.simpleicons.org/python" width="14"/> Python &nbsp; <img src="https://cdn.simpleicons.org/typescript" width="14"/> TypeScript &nbsp; <img src="https://cdn.simpleicons.org/postgresql" width="14"/> SQL &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="14"/> VS Code                 |
| **Data Engineering & Streaming**  | <img src="https://logo.svgcdn.com/logos/dbt-icon.svg" width="14"/> dbt &nbsp; <img src="https://cdn.simpleicons.org/apachekafka" width="14"/> Kafka &nbsp; <img src="https://cdn.simpleicons.org/apacheairflow" width="14"/> Airflow                                                                                                                              |
| **AI & LLM Engineering**          | <img src="https://cdn.simpleicons.org/langchain" width="14"/> LangChain &nbsp; <img src="https://cdn.simpleicons.org/postgresql" width="14"/> pgvector &nbsp; <img src="https://cdn.simpleicons.org/anthropic/D97757" width="14"/> Claude Code &nbsp;|
| **Databases & Warehousing**       | <img src="https://cdn.simpleicons.org/snowflake" width="14"/> Snowflake &nbsp; <img src="https://cdn.simpleicons.org/databricks" width="14"/> Databricks &nbsp; <img src="https://cdn.simpleicons.org/postgresql" width="14"/> PostgreSQL                                                                                                                        |
| **Backend & APIs**                | <img src="https://cdn.simpleicons.org/fastapi" width="14"/> FastAPI &nbsp; <img src="https://cdn.simpleicons.org/fastify" width="14"/> Fastify &nbsp; <img src="https://cdn.simpleicons.org/nextdotjs" width="14"/> Next.js                                                         |
| **Cloud, DevOps & Observability** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" width="14"/> Azure &nbsp; <img src="https://cdn.simpleicons.org/docker" width="14"/> Docker &nbsp; <img src="https://cdn.simpleicons.org/githubactions" width="14"/> GitHub Actions &nbsp; <img src="https://cdn.simpleicons.org/opentelemetry" width="14"/> OpenTelemetry |

---

## 🚀 Featured Projects

### [MERA — AI-Native Product Operations Platform](https://github.com/FranciscoJavierCotos/MERA-Product-Operations)

> A full-stack ops platform where the database is the source of truth — and every resolved ticket makes the next one cheaper to solve.

<p align="left">
  <img
    src="https://raw.githubusercontent.com/FranciscoJavierCotos/MERA-Product-Operations/main/docs/screenshots/analytics.png"
    width="460"
    alt="MERA Dashboard"
  />
</p>

**The impact:** MERA replaces five fragmented ops tools with one system. Closed tickets are automatically chunked, embedded (Gemini), and indexed in **pgvector**, so a **RAG** engine surfaces the most relevant past resolutions the moment a new case opens — turning support history into a compounding knowledge asset. SLAs are computed as a pure function of stored timestamps (never drift, zero cron), and business invariants live in Postgres triggers so they hold no matter the client.

**Owned, versioned API layer** (Fastify, Zod, OpenAPI), **RLS as the security boundary**, and a three-tier test strategy (Vitest unit + integration against real Postgres/RLS, Playwright E2E) gated in CI alongside Semgrep and secret scanning.

**Stack:** Next.js 16 · Fastify 5 · PostgreSQL · Supabase · pgvector · Gemini · TypeScript · React 19

---

### [ChordCoach — Production-Grade LLM Agent](https://github.com/FranciscoJavierCotos/guitar-chord-assistant)

> A conversational AI agent that teaches guitar theory — wrapped in the engineering an LLM feature actually needs to ship: an eval gate, tracing, and a hardened API.

**The impact:** The interesting work isn't the guitar app — it's everything around the LLM that makes it **trustworthy, measurable, and safe to expose publicly**. A LangChain function-calling agent (13 tools) drives the UI through a structured JSON contract, but every chord rendered is re-fetched from an authoritative database — **the model can't hallucinate output onto the screen**.

**Stack:** Python · FastAPI · LangChain · DeepSeek API · OpenTelemetry · Next.js 14 · TypeScript

---

## 📬 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-javier--cotos--ventoso-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/javier-cotos-ventoso)
