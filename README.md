# AI agent & backend developer

**Python · Node.js/TypeScript · Go · React**

I build AI agents that do real work for a business: reply to new leads, answer customer questions, and pull answers out of documents. They run on tested backends, connected to the tools you already use, like HubSpot, GoHighLevel, Twilio, Shopify and Stripe.

Before freelancing I spent 3+ years building payment backends in fintech, including a banking app with 2M+ users and 25M+ transactions. That's where I learned to write code that survives retries, duplicate webhooks and bad inputs.

Available for freelance projects. I'm on UTC+3, so I overlap with the European workday and the US morning.

---

## AI agents you can try

**[AI speed-to-lead agent](https://github.com/Sanoy24/ai-lead-agent)** for service businesses. Replies to every new lead by text, email or Telegram, asks your qualifying questions, sends qualified leads your booking link and keeps your CRM up to date. Your team can take over any conversation.<br/>
[▶ Watch the 2-minute demo](https://youtu.be/X6X4b2D8GlA) · 150 tests in CI · HubSpot and GoHighLevel sync

**[AI support agent](https://github.com/Sanoy24/ai-support-agent)** for online stores. Answers questions about orders, shipping and returns from your own store data, and hands anything else to a person on your team.<br/>
[▶ Watch the 2-minute demo](https://www.youtube.com/watch?v=wgjD3xhUipU) · Shopify or demo store · admin dashboard

**[PDF data extraction](https://github.com/Sanoy24/pdf-data-extraction)**. Turns messy PDFs (tables, multi-column, scanned) into structured data and answers questions with citations to the source page. Picks the cheapest extraction method per page.

---

## Node.js / TypeScript

- **[escrow-marketplace-fullstack](https://github.com/Sanoy24/escrow-marketplace-fullstack)**: React + NestJS + PostgreSQL excerpt from a marketplace I built, with escrow payments, real-time chat over Socket.IO and auth. 65 tests.
- **[safe-fetch-mcp-server](https://github.com/Sanoy24/safe-fetch-mcp-server)** ![npm downloads](https://img.shields.io/npm/dm/safe-fetch-mcp-server?style=flat-square&label=npm) lets AI agents fetch web pages without SSRF: it resolves each address once, pins that IP and re-checks every redirect.
- **[JevPolicy](https://github.com/Sanoy24/jevpolicy)** ![npm version](https://img.shields.io/npm/v/@sanoy24/jevpolicy?style=flat-square) is a decision runtime: an LLM answers typed questions, versioned YAML rules make the decision, and every decision can be replayed.
- **[e-commerce-api](https://github.com/Sanoy24/e-commerce-api)**: NestJS + Prisma REST API with Docker Compose.

## Python backend

- **[fastapi-ecommerce](https://github.com/Sanoy24/fastapi-ecommerce)** ![stars](https://img.shields.io/github/stars/Sanoy24/fastapi-ecommerce?style=flat-square) has Stripe payments and subscriptions with idempotency keys, an outbox for reliable events, ARQ workers and OpenTelemetry tracing, tested against real PostgreSQL.
- **[repoward](https://github.com/Sanoy24/repoward)** ![PyPI downloads](https://img.shields.io/pypi/dm/repoward?style=flat-square&label=pypi) is a GitHub MCP server that stops prompt-injected agents from leaking private code, with flow guards, policies, human approval and an audit log. Alpha.
- **[Brownfield Cartographer](https://github.com/Sanoy24/the-brownfield-cartographer)** ![PyPI downloads](https://img.shields.io/pypi/dm/brownfield-cartographer?style=flat-square&label=pypi) maps code structure, change impact and SQL, dbt and Airflow data lineage, as a CLI and a read-only MCP server.
- **[backend-performance-review](https://github.com/Sanoy24/backend-performance-review)**: an Agent Skill that teaches coding agents (Claude Code, Codex, Cursor) evidence-based backend performance review.

## Go

- **[YTGrab](https://github.com/Sanoy24/ytgrab)** ![downloads](https://img.shields.io/github/downloads/Sanoy24/ytgrab/total?style=flat-square) is a single-binary video downloader with a local web UI and a browser extension, shipped through 26 releases on Homebrew and Scoop.

## AI evaluation

- **[tenacious-bench](https://github.com/Sanoy24/tenacious-bench)**: a 242-task benchmark for B2B sales agents, plus a LoRA judge model ([dataset](https://huggingface.co/datasets/sanoy24/tenacious_bench_v0.1) on Hugging Face).
- **[agentic-event-store](https://github.com/Sanoy24/agentic-event-store)**: an append-only PostgreSQL event store for multi-agent systems, with a hash-chained audit log and an MCP server.

Graduated with distinction (top 3%) from 10 Academy's AI Agent and Forward Deployed Engineering program.

---

[Portfolio](https://yonas-mekonnen-portfolio-zeta.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/yonassanoy/) · [Upwork](https://www.upwork.com/freelancers/~01aacbf104ed26ec0d)
