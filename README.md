# Anderson Henrique

**AI/ML Engineer | Python Systems Developer**

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anderson-h-silva95/)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/anderson-ufrj)
[![HuggingFace](https://img.shields.io/badge/-HuggingFace-FFAE00?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/neural-thinker)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:andersonhs27@gmail.com)

---

## About

**3+ years** building Python systems with **2+ years** specializing in AI/ML infrastructure. Computer Science background with focus on production-ready applications, API optimization, and multi-agent system design.

**Location**: Minas Gerais, Brazil • **Remote**: Available worldwide • **Languages**: PT-BR, EN

---

## Technical Expertise

**Backend Development**
- Python (FastAPI, Django), async/await patterns
- PostgreSQL optimization, Redis caching strategies
- RESTful API design, JWT authentication
- Docker multi-stage builds, container orchestration

**AI/ML Integration**
- LangChain orchestration, custom RAG pipelines
- Vector databases (ChromaDB, FAISS), semantic search
- HuggingFace Transformers, prompt engineering
- Anomaly detection (Isolation Forest, DBSCAN)

**Infrastructure**
- Docker/Kubernetes deployment, CI/CD pipelines
- Prometheus/Grafana monitoring, structured logging
- AWS services, HuggingFace Spaces deployment

---

## Impact Metrics

| Achievement | Result | Implementation |
|-------------|--------|----------------|
| API Latency | 73% reduction (2.3s → 620ms) | Async handlers + Redis caching layer |
| System Throughput | 10k+ requests/hour | Horizontal scaling + load balancing |
| Operational Cost | $8k/month reduction | In-house model deployment vs external APIs |
| Anomaly Detection | 94% relevance score | Multi-model ensemble + threshold tuning |

---

## Featured Project: Cidadão.AI

**Multi-agent system for Brazilian public data analysis**

```python
# Core architecture
async def orchestrate_agents(task: AnalysisTask) -> Result:
    async with asyncio.TaskGroup() as tg:
        anomaly_task = tg.create_task(zumbi_agent.detect(task.data))
        analysis_task = tg.create_task(anita_agent.analyze(task.contracts))
    return await self.synthesize([anomaly_task.result(), analysis_task.result()])
```

**Technical Stack**: FastAPI 0.109+ • LangChain 0.1+ • PostgreSQL 16 • Redis 7 • ChromaDB

**Production Metrics**:
- 17 specialized agents processing government transparency data
- FastAPI backend with <500ms p95 response time  
- Vector search across 1M+ document embeddings
- JWT auth + rate limiting + comprehensive audit logging

**Live System**: 
- [API Documentation](https://neural-thinker-cidadao-ai-backend.hf.space/docs)
- [Source Code](https://github.com/anderson-ufrj/cidadao.ai-backend)
- [HuggingFace Space](https://huggingface.co/spaces/neural-thinker/cidadao.ai-backend)

---

## Engineering Philosophy

- **Production-first**: Every feature designed for observability and maintenance
- **Performance-focused**: Measure twice, optimize once - always with benchmarks
- **Security-conscious**: Authentication, rate limiting, and audit trails as foundation
- **Pragmatic choices**: Technology decisions based on requirements, not trends

---

## Selected Projects

**[Cidadão.AI Backend](https://github.com/anderson-ufrj/cidadao.ai-backend)**
Multi-agent system with 17 specialized AI agents, FastAPI async architecture, comprehensive monitoring

**[Frontend Dashboard](https://github.com/anderson-ufrj/cidadao.ai-frontend)** 
Next.js 15 + TypeScript interface with real-time WebSocket connections, internationalization

**[Documentation Hub](https://anderson-ufrj.github.io/cidadao.ai-docs/)**
Technical documentation with interactive agent showcase, accessibility compliance

---

## Technical Environment

**Languages**: Python 3.11+, JavaScript/TypeScript, SQL, Bash  
**Frameworks**: FastAPI, LangChain, Next.js, React  
**Databases**: PostgreSQL, Redis, ChromaDB  
**Infrastructure**: Docker, Kubernetes, AWS, GitHub Actions  
**Monitoring**: Prometheus, Grafana, OpenTelemetry

---

## Current Focus

Building cost-effective LLM inference pipelines and expanding multi-agent coordination capabilities. Open to opportunities in AI infrastructure, backend systems, and technical leadership roles.

---

*Minas Gerais, Brazil • Available for remote collaboration*