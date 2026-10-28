# Yonas Mekonnen — Backend & AI Engineer

**I build backend systems and the tooling that makes AI agents safe, deterministic, and observable.**<br/>
Python · TypeScript · Go — MCP servers · agent tooling · developer tools · backend APIs

<p>
  <a href="https://www.linkedin.com/in/yonassanoy/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://yonas-mekonnen-portfolio-zeta.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white" /></a>
  <a href="mailto:myonas886@gmail.com"><img src="https://img.shields.io/badge/myonas886@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://huggingface.co/sanoy24"><img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" /></a>
  <a href="https://yonasmekonnen.substack.com"><img src="https://img.shields.io/badge/Blog-FF6719?style=flat-square&logo=substack&logoColor=white" /></a>
</p>

> 🟢 **Open to work** — Full-time · Contract · Freelance

---

## What I do

3+ years building backend systems, now focused on the infrastructure layer around AI agents: MCP servers, deterministic decision and policy runtimes, code-intelligence tooling, and evaluation. I ship my open-source work as installable packages with tests, CI, and releases.

---

## Open-source tools

| Project | What it is | Install |
| --- | --- | --- |
| 🗺️ [**Brownfield Cartographer**](https://github.com/Sanoy24/the-brownfield-cartographer) | Local-first repository analysis engine: code structure, dependency impact, and data lineage (Python, SQL, dbt) through one query engine exposed as a CLI, Python API, and read-only MCP server. Deterministic by default — no network or model required. | `pipx install brownfield-cartographer` |
| 🛡️ [**safe-fetch-mcp-server**](https://github.com/Sanoy24/safe-fetch-mcp-server) | MCP fetch server built around correct SSRF defense: resolve once, validate the resolved IP, pin the connection, and re-check every redirect hop. Covers IPv4-mapped IPv6, DNS rebinding, and encoded-IP edge cases. | `npx safe-fetch-mcp-server` |
| ⚖️ [**JevPolicy**](https://github.com/Sanoy24/jevpolicy) | TypeScript decision runtime: an LLM answers typed questions, ordered YAML rules make the decision. Versioned policies, offline tests, policy diffs, shadow evaluation, and replay from recorded signals. | `npm i @sanoy24/jevpolicy` |
| 🔍 [**backend-performance-review**](https://github.com/Sanoy24/backend-performance-review) | Agent Skill that teaches coding agents (Claude Code, Codex, Cursor, Copilot) evidence-based backend performance review, with a JSON schema validator and a GitHub Action. It refuses to invent numbers and returns zero findings rather than fake ones. | `npx skills add …` |
| ⬇️ [**YTGrab**](https://github.com/Sanoy24/ytgrab) | Single-binary Go app with a local web UI for yt-dlp: real quality selection, playlists, resumable downloads, tray integration, and a browser extension. Cross-platform releases via Homebrew, Scoop, and a checksum-verified installer. | `brew install sanoy24/tap/ytgrab` |

`Python` `TypeScript` `Go` `MCP` `tree-sitter` `sqlglot` `Zod` `Vercel AI SDK` `SQLite` `GitHub Actions`

---

## AI systems & evaluation

- 🏦 **[agentic-event-store](https://github.com/Sanoy24/agentic-event-store)** — Append-only PostgreSQL event store for multi-agent workflows: optimistic concurrency (covered by a double-decision concurrency test), CQRS projections, a SHA-256 hash-chained audit ledger, and an MCP server exposing the store as agent tools. `Python` `PostgreSQL` `FastMCP` `Event sourcing`
- 📊 **[tenacious-bench](https://github.com/Sanoy24/tenacious-bench)** — 242-task, machine-verifiable benchmark for B2B sales agents (14 failure dimensions, Cohen's κ = 0.91 on a stratified sample), plus a SimPO LoRA judge on Qwen2.5-3B. [Dataset](https://huggingface.co/datasets/sanoy24/tenacious_bench_v0.1) · [Adapter](https://huggingface.co/sanoy24/tenacious-judge-qwen25-3b-gamma15) · [Write-up](https://yonasmekonnen.substack.com/p/building-a-0-100-accurate-ai-sales)
- ⚖️ **[Automaton Auditor](https://github.com/Sanoy24/trp1-automation-auditor)** — LangGraph code-audit swarm: tool-based detective agents collect evidence, three LLM judges score a 10-dimension rubric, and a chief-justice node resolves disagreements with deterministic Python rules. Multi-provider (Ollama, OpenAI, Anthropic, Google). `LangGraph` `Python`
- 🤖 **[Conversion Engine](https://github.com/Sanoy24/conversion-engine)** — Lead-enrichment and outreach agent with HubSpot MCP, Cal.com, and Langfuse tracing; 70 tests and a 37-probe adversarial suite. `FastAPI` `Langfuse` `Python`

---

## Backend

| Project | What it is |
| --- | --- |
| [fastapi-ecommerce](https://github.com/Sanoy24/fastapi-ecommerce) | FastAPI e-commerce backend — Stripe payments & subscriptions, outbox pattern, ARQ workers, OpenTelemetry/Prometheus, tests on real PostgreSQL via testcontainers |
| [e-commerce-api](https://github.com/Sanoy24/e-commerce-api) | NestJS + Prisma REST API with Docker Compose |
| [lyrics-rest-api](https://github.com/Sanoy24/lyrics-rest-api) | Go REST API — GORM, PostgreSQL, unit tests, CI |
| [djinni-telegram-bot](https://github.com/Sanoy24/djinni-telegram-bot) | Go Telegram bot delivering filtered job alerts from Djinni's RSS feed |
| [trp1-document-intelligence-refinery](https://github.com/Sanoy24/trp1-document-intelligence-refinery) | Multi-stage document pipeline — Docling, ChromaDB, LangGraph |

---

## Skills

**Languages** — Python · TypeScript · Go · JavaScript<br/>
**Backend** — FastAPI · NestJS · Node.js · Express · Gin · Django<br/>
**AI & agents** — MCP · LangGraph · LangChain · OpenAI · Anthropic · Vercel AI SDK · Langfuse · LangSmith<br/>
**Data & infra** — PostgreSQL · Redis · MongoDB · SQLite · ChromaDB · Docker · GitHub Actions<br/>
**ML** — Hugging Face · LoRA / SimPO fine-tuning · RAG · LLM evaluation

---

## Open-source recognition

[![XERJ Corpus Hub contributor](https://hub.xerj.org/contributors/Sanoy24/badge.svg)](https://hub.xerj.org/contributors/Sanoy24.html)

A YTGrab commit ([podcast feeds for watched channels](https://github.com/Sanoy24/ytgrab/commit/6eeafb23f7)) was selected for the [XERJ Corpus Hub](https://hub.xerj.org/contributors/Sanoy24.html), an open reference corpus that AI coding agents search for worked examples.

---

<p align="center">
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=sanoy24&theme=tokyonight" />
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=sanoy24&theme=tokyonight" />
</p>

<p align="center">
  <sub><a href="mailto:myonas886@gmail.com">myonas886@gmail.com</a> · <a href="https://www.linkedin.com/in/yonassanoy/">LinkedIn</a> · <a href="https://yonas-mekonnen-portfolio-zeta.vercel.app/">Portfolio</a></sub>
</p>
