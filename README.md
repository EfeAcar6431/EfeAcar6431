# Hey, I'm Efe

**AI & Software Engineer** building production AI systems including autonomous coding agents, forecasting engines, RAG pipelines, LLM evaluation frameworks, and agentic assistants.

CS at Northeastern University.

https://efeacar.com 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/efe-acar/)

[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:efeacar2705@gmail.com)

---

### What I've been building

**CodeRouter** — Autonomous coding agent with a model-routing brain ([github.com/Code-Router/CodeRouter](https://github.com/Code-Router/CodeRouter))
- A planner LLM decomposes each prompt into a task DAG and picks the best-value model per task from a live scored catalog — frontier models for architecture, cheap/free models for tests and boilerplate
- One agent per task in parallel git worktrees, with file-scope conflict serialization and 3-way merges into an integration branch
- Lean per-agent context from a persisted SQLite repo index (symbol outlines + import graph); validators (lint/typecheck/tests) with bounded self-fix passes
- Every plan, model assignment, cost, and merge is journaled and browsable — CLI, REPL, MCP server, and desktop app

**ForesightAI** — AI-powered KPI forecasting for enterprise distribution networks (1,400+ endpoints)
- GPT-4o analysis engine with multi-grain drill-down narrative reports
- Dealer-level forecasting pipeline with automated backtesting (MAPE/RMSE) and rolling calibration
- Multi-tenant isolation via PostgreSQL schema-per-tenant, asyncpg, and Redis caching

**VerifyWise** — Open-source AI governance platform ([verifywise.ai](https://verifywise.ai/platform/llm-evaluations))
- Built the LLM Evaluations module — judge orchestration, multi-provider abstraction (OpenAI, Anthropic, Google), and async evaluation pipelines
- Automated testing for bias, toxicity, hallucination, and answer relevancy using DeepEval

**AssistAI** — Enterprise RAG platform for automotive clients ([miventoassist.ai](https://miventoassist.ai))
- 7-stage retrieval pipeline with hybrid search (E5-Large + BM25 via RRF fusion)
- Entity-aware anti-hallucination filtering, multi-tenant Qdrant collections, and real-time SSE streaming

---


<sub>More at [efeacar.com](https://efeacar.com)</sub>
