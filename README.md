# Leandro Kuranaga

**FDE · AI Engineer · Senior Software Engineer.** 8+ years shipping .NET systems to production on
Azure and AWS, and building the agent tooling that runs on top of them: MCP servers, agent
teams, evaluation suites and guardrails.

[![Portfolio](https://img.shields.io/badge/Portfolio-lkuranaga.com-2FB4CE?style=flat-square&logo=google-chrome&logoColor=white)](https://www.lkuranaga.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-leandrokuranaga-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leandrokuranaga/)
[![Email](https://img.shields.io/badge/Email-le.s.kuranaga-2FB4CE?style=flat-square&logo=maildotru&logoColor=white)](mailto:le.s.kuranaga@hotmail.com)

Currently an **AI Engineer at Marlabs**, on a **PracticeTek** team in California building
multi-tenant SaaS for dental labs. Before that, **Andritz** (industrial IIoT, teams in Germany
and Canada), **Stefanini** (Raízen/Shell and GenAI products) and **Sonda** (automation and
chatbots for Claro, Vivo, Embraer and Sodexo).

Remote, based in Indaiatuba, SP, Brazil. Open to opportunities.

## Systems I've shipped

**Engineering agent ecosystem** · Marlabs / PracticeTek
Claude Code and Codex with 40+ skills, specialized agent teams (review, SRE, DevOps, QA) and
MCP integrations with Jira, Datadog, Playwright and Azure, over a SaaS stack of .NET 8, PHP,
Next.js, Azure and AWS ECS Fargate with Terraform and 54 GitHub Actions workflows.

**Industrial optimization platform** · Andritz
Plant sensor reads were degrading in SQL Server and calibration still depended on manual
operator adjustment. Split the write path into Kafka streaming plus a dedicated InfluxDB
time-series store, with AI/ML optimization feeding calibration back to operators.
**3x faster analytical queries, 40% less manual calibration time.**

**AI in production for e-commerce**
An MCP API that lets AI agents place orders, Azure OpenAI semantic search and a Claude
pipeline that validates 13k product images. Migrated a legacy IIS VM to Azure App Service
with zero-downtime slot swaps and federated OIDC deploys.

**CSOnline, enterprise integration** · Stefanini / Raízen
SAP, Salesforce and Pix payments converged into one fuel distribution platform. The .NET API
publishes to Azure Service Bus topics, independent workers consume at-least-once with
dead-letter handling, so a slow downstream never blocks a payment. **13,000+ monthly users.**

**GenAI products** · Stefanini
Speech analytics (S3 → Transcribe → SQS → GPT) auditing calls for 20+ BPO operations,
ServiceNow incident triage for Petrobras and billing-dispute analysis for Comgás.

## Open source & academic

- 🏆 **[TC Agro](https://github.com/rdpresser/tc-agro-solutions)** · 1st place, FIAP 8NETT Hackathon. IoT farming platform in .NET 10 microservices: TimescaleDB, Outbox (Wolverine/RabbitMQ), Kubernetes + ArgoCD, OpenTelemetry, React Native.
- **[FIAP Cloud Games](https://github.com/leandrokuranaga/FCG)** · monolith to 5 microservices: YARP gateway, Stripe with Outbox + SQS, Event Sourcing (KurrentDB), Lambda, AWS EKS. Repos: [FCG](https://github.com/leandrokuranaga/FCG), [CRM](https://github.com/leandrokuranaga/Fiap-CRM), [Payment](https://github.com/leandrokuranaga/Fiap-Payment), [Events](https://github.com/leandrokuranaga/Fiap-Events), [Proxy](https://github.com/leandrokuranaga/Fiap-Proxy).
- **[CareerAI](https://github.com/leandrokuranaga/careermentor-back)** · résumé analysis and career coach with Semantic Kernel and OpenAI ([front end](https://github.com/leandrokuranaga/careermentor-ai)).
- **[Delivery Book](https://github.com/leandrokuranaga/Puc-delivery-book)** · PUC-SP capstone, .NET Clean Architecture + React.
- **[MX7](https://github.com/leandrokuranaga/Tcc-unip)** · UNIP thesis, React Native + Node.js, later rewritten in [.NET](https://github.com/leandrokuranaga/unip-backend-tcc).

## Agentic engineering

Most engineers consume AI tools. I build the harness they run on.

- **Agent tooling** — MCP servers, subagents, hooks and reusable skills on Claude Code and the Claude Agent SDK
- **Agent teams** — specialized review, SRE, DevOps and QA agents wired to Jira, Datadog, Playwright and Azure through MCP
- **Evaluation & guardrails** — regression prompt suites, deterministic assertions over structured responses, review gates before merge
- **AI security** — least-privilege tool scoping and human-in-the-loop approval on agent workflows

## Stack

Ranked by how deep the ownership goes, not alphabetically.

**Core** — .NET 8/10, C#, ASP.NET Core, Azure, SQL Server, event-driven architecture, microservices, DDD, CQRS, REST APIs, xUnit

**Fluent** — Claude Code, MCP, Semantic Kernel, OpenAI/Azure OpenAI, LLM evaluation, AWS (EKS, ECS, Lambda, SQS), Kubernetes, Helm, Terraform, GitHub Actions, Azure Service Bus, Kafka, RabbitMQ, Redis, PostgreSQL, InfluxDB, React, Next.js, Angular, Vue, TypeScript, Module Federation, Playwright, Testcontainers, Datadog, OpenTelemetry, Docker

**Exposed** — PHP, Rust/Tauri, MongoDB, Elasticsearch, KurrentDB, Blip, SAP / Salesforce

## Education

- **Quantum Computing**, postgraduate · PUC Minas (in progress)
- **Software Architecture**, postgraduate · FIAP (2025–2026)
- **Software Engineering**, specialization · PUC-SP (2021–2022)
- **Computer Science**, bachelor's · UNIP (2016–2020)

Certifications: Anthropic (Introduction to MCP, Claude Code in Action, Agent Skills, AI Fluency) · EF SET C1 English
