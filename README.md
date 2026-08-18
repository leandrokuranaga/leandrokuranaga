# Leandro Kuranaga

**Backend & AI Engineer.** 8 years building .NET and Azure distributed systems, now
building the agent tooling that runs on top of them: MCP servers, guardrails and
evaluation suites, not just tool usage.

[![Portfolio](https://img.shields.io/badge/Portfolio-lkuranaga.com-2FB4CE?style=flat-square&logo=google-chrome&logoColor=white)](https://www.lkuranaga.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-leandrokuranaga-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leandrokuranaga/)
[![Email](https://img.shields.io/badge/Email-le.s.kuranaga-2FB4CE?style=flat-square&logo=maildotru&logoColor=white)](mailto:le.s.kuranaga@hotmail.com)

Currently at **Andritz**, working daily in English with teams in Germany and Canada on
industrial optimization. Before that, enterprise integrations at **Stefanini** (client
Raízen) and conversational automation at **Sonda** for Claro, Vivo, Embraer and Sodexo.

Remote, based in Indaiatuba, SP, Brazil. Open to opportunities.

## Systems I've shipped

**Industrial optimization platform** · Andritz
Plant sensor reads were degrading in SQL Server and calibration still depended on
manual operator adjustment. Split the write path into Kafka streaming plus a dedicated
InfluxDB time-series store, with AI/ML optimization feeding calibration back to
operators. **3x faster analytical queries, 40% less manual calibration time.**

**CSOnline, enterprise integration** · Stefanini / Raízen
SAP, Salesforce and Pix payments had to converge into one fuel distribution platform
without coupling the systems to each other. Event-driven core: the .NET API publishes
to Azure Service Bus topics, independent workers consume at-least-once with dead-letter
handling, so a slow downstream never blocks a payment. **13,000+ monthly users.**

**Conversational automation** · Sonda
Claro, Vivo, Embraer and Sodexo needed to absorb high interaction volumes without
growing support headcount. Intent handling and dialog flows in ASP.NET orchestrated
through Blip, with explicit fallback routing so anything the classifier could not match
reached a human instead of failing.

Each one is drawn as a real architecture diagram on [lkuranaga.com](https://www.lkuranaga.com).

## Agentic engineering

Most engineers consume AI tools. I build the harness they run on.

- **Custom agent tooling** — MCP servers, subagents, hooks and reusable skills on the Claude Agent SDK
- **Harness & loop engineering** — a CLI-first agentic pipeline adopted by the team: design context via MCP, automated code review, Playwright E2E, spec-driven delivery
- **Evaluation & guardrails** — regression prompt suites, deterministic assertions over structured responses, review gates that block off-spec generations before merge
- **Retrieval** — Azure AI Search with RAG patterns: chunking, embeddings, vector search
- **AI security** — least-privilege tool scoping and human-in-the-loop approval on agent workflows

## Stack

Ranked by how deep the ownership goes, not alphabetically.

**Core** — .NET 8 / Core, C#, Azure, SQL Server, event-driven architecture, DDD, CQRS, REST APIs, xUnit

**Fluent** — Claude Agent SDK, MCP servers, Semantic Kernel, Azure AI Search, Azure AI Foundry, LLM evaluation, guardrails, RAG, Python, React, TypeScript, Angular, Service Bus, Kafka, Redis, PostgreSQL, InfluxDB, Terraform, AWS, Docker, Playwright, Git / CI-CD

**Exposed** — Kubernetes, MongoDB, ElasticSearch, KurrentDB, Blip, SAP / Salesforce

## Education

Postgraduate in Quantum Computing (PUC Minas, from Sep 2026) · Specialization in
Software Architecture (FIAP) · Postgraduate in Software Engineering (PUC-SP) ·
B.Sc. Computer Science (UNIP)
