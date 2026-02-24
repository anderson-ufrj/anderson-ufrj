# Anderson Henrique da Silva

AI Systems Engineer. Philosophy before code, systems before features.

I think in systems -- from data ingestion to the end user, from the philosophical question to the running inference. I studied Philosophy at UFRJ before Computer Science -- I learned to think before I learned to build. The interesting problems in AI live at the seam between what a machine can parse and what a citizen needs to understand. AI is a component in that architecture, not the point of it.

---

## Systems in Production

### [Cidadão.AI](https://cidadao-ai-frontend.vercel.app) -- Government Transparency Platform

A multi-agent system for public spending oversight. Twenty operational AI agents, each named after a Brazilian historical figure -- Zumbi investigates anomalies, Tiradentes generates reports, Machado analyzes text, Obaluaie detects corruption patterns. The system integrates 30+ federal and state transparency APIs into a unified intelligence layer.

INPI Registration: BR512025004322-8 | Thesis grade: 10/10

| Metric | Value |
|--------|-------|
| Agents | 20 operational + 2 base frameworks |
| Endpoints | 376 |
| Tests | 2,451 across 170 files |
| Codebase | 151K lines of Python |
| p95 latency | < 180ms |

`FastAPI` `LangChain` `FAISS` `BERTimbau` `PostgreSQL` `Redis` `Railway` `Prometheus` `Grafana`

[API Docs](https://cidadao-api-production.up.railway.app/docs)

### [NTS Lab](https://neuralthinkers.up.railway.app) -- Multi-Product Monorepo

A Turborepo monorepo running four subsidiary systems across 10 Railway services: **Hipócrates** (medical AI -- transcription, SOAP notes, OCR), **Mercurius** (multi-tenant notary management), **Polis** (municipal health), and **Argos** (law firm management). 322+ API endpoints, 12 shared TypeScript packages, and a Python SDK published on PyPI (`ntlabs`).

`Next.js 15` `TypeScript` `Turborepo` `Supabase` `Tailwind` `Docker`

---

## Open Source Contributions

- **[langchain-maritaca](https://pypi.org/project/langchain-maritaca/)** -- First LangChain integration for Maritaca AI (Brazilian LLM). Published on PyPI.
- **[DSPy](https://github.com/stanfordnlp/dspy)** (Stanford) -- Submitted tutorial: "Building Multi-Agent Systems with Cultural Personalities." [PR #9124](https://github.com/stanfordnlp/dspy/pull/9124) (under review)
- **[Instructor](https://github.com/jxnl/instructor)** (jxnl) -- Proposed cache observability hooks (CACHE_HIT/CACHE_MISS). [PR #1960](https://github.com/jxnl/instructor/pull/1960) (under review)
- **[mcp-brasil](https://github.com/anderson-ufrj/mcp-brasil)** -- MCP server in Go for Brazilian government transparency APIs.

---

## Writing

**Papers** (Zenodo, 2025)
1. [*Cidadão.AI: Sistema Multi-Agente de IA para Democratização do Acesso a Dados de Transparência Governamental Brasileira*](https://doi.org/10.5281/zenodo.18550749)
2. [*The Cyborg Developer: Empirical Analysis of Cognitive Extension Through Human-AI Collaborative Programming*](https://doi.org/10.5281/zenodo.18111064)
3. [*From Commits to Cognition: A Mixed-Methods Framework for Inferring Developer Mental Models from Repository Artifacts*](https://doi.org/10.5281/zenodo.18012186)

**Blog** -- [neuralthinkers.up.railway.app/pt/blog](https://neuralthinkers.up.railway.app/pt/blog)
Ten articles at the intersection of philosophy, AI engineering, and Brazilian public policy. Speaker at UaiSINT 2025.

---

## Links

[Website](https://neuralthinkers.up.railway.app) | [Blog](https://neuralthinkers.up.railway.app/pt/blog) | [LinkedIn](https://linkedin.com/in/anderson-h-silva95/) | [HuggingFace](https://huggingface.co/neural-thinker) | andersonhs27@gmail.com

Minas Gerais, Brazil -- GMT-3 -- Available for remote work.
