# Leandro Kuranaga

**AI Engineer · Engenheiro de Software Sênior.** Mais de 8 anos colocando sistemas .NET em
produção no Azure e na AWS, e construindo o ferramental de agentes que roda em cima deles:
MCP servers, times de agentes, suítes de avaliação e guardrails.

[![Portfólio](https://img.shields.io/badge/Portf%C3%B3lio-lkuranaga.com-2FB4CE?style=flat-square&logo=google-chrome&logoColor=white)](https://www.lkuranaga.com/pt/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-leandrokuranaga-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leandrokuranaga/)
[![Email](https://img.shields.io/badge/Email-le.s.kuranaga-2FB4CE?style=flat-square&logo=maildotru&logoColor=white)](mailto:le.s.kuranaga@hotmail.com)

Hoje sou **AI Engineer na Marlabs**, num time da **PracticeTek** na Califórnia, construindo SaaS
multi-cliente para laboratórios odontológicos. Antes passei pela **Andritz** (IIoT industrial,
com times na Alemanha e no Canadá), pela **Stefanini** (Raízen/Shell e produtos de IA generativa)
e pela **Sonda** (automação e chatbots para Claro, Vivo, Embraer e Sodexo).

Remoto, em Indaiatuba, SP. Aberto a oportunidades.

## Sistemas que entreguei

**Ecossistema de agentes da engenharia** · Marlabs / PracticeTek
Claude Code e Codex com mais de 40 skills, times de agentes especializados (revisão, SRE,
DevOps, QA) e integrações MCP com Jira, Datadog, Playwright e Azure, sobre uma stack de .NET 8,
PHP, Next.js, Azure e AWS ECS Fargate, com Terraform e 54 workflows no GitHub Actions.

**Plataforma de otimização industrial** · Andritz
As leituras de sensores da planta degradavam no SQL Server e a calibração ainda dependia de
ajuste manual do operador. Separei o caminho de escrita com streaming em Kafka para um store
de série temporal no InfluxDB, com otimização AI/ML devolvendo a calibração aos operadores.
**Queries analíticas 3x mais rápidas e 40% menos tempo de calibração manual.**

**IA em produção para e-commerce**
Uma API MCP que deixa agentes de IA fazerem pedidos, busca semântica com Azure OpenAI e um
pipeline com Claude que valida 13 mil imagens de produto. Migrei uma VM IIS legada para o Azure
App Service, com slot swap sem downtime e deploy por OIDC federado.

**CSOnline, integração enterprise** · Stefanini / Raízen
SAP, Salesforce e pagamentos Pix convergindo numa plataforma de distribuição de combustíveis.
A API .NET publica em tópicos do Azure Service Bus e workers independentes consomem com
at-least-once e dead-letter, então um sistema lento nunca trava um pagamento.
**Mais de 13 mil usuários por mês.**

**Produtos de IA generativa** · Stefanini
Speech analytics (S3 → Transcribe → SQS → GPT) auditando ligações de mais de 20 operações de
BPO, triagem de incidentes do ServiceNow para a Petrobras e análise de contestação de conta
para a Comgás.

## Open source e projetos acadêmicos

- 🏆 **[TC Agro](https://github.com/rdpresser/tc-agro-solutions)** · 1º lugar no Hackathon FIAP 8NETT. Plataforma IoT agrícola em microsserviços .NET 10: TimescaleDB, Outbox (Wolverine/RabbitMQ), Kubernetes + ArgoCD, OpenTelemetry e React Native.
- **[FIAP Cloud Games](https://github.com/leandrokuranaga/FCG)** · de monólito a 5 microsserviços: gateway YARP, Stripe com Outbox + SQS, Event Sourcing (KurrentDB), Lambda e AWS EKS. Repositórios: [FCG](https://github.com/leandrokuranaga/FCG), [CRM](https://github.com/leandrokuranaga/Fiap-CRM), [Payment](https://github.com/leandrokuranaga/Fiap-Payment), [Events](https://github.com/leandrokuranaga/Fiap-Events) e [Proxy](https://github.com/leandrokuranaga/Fiap-Proxy).
- **[CareerAI](https://github.com/leandrokuranaga/careermentor-back)** · análise de currículo e coach de carreira com Semantic Kernel e OpenAI ([front-end](https://github.com/leandrokuranaga/careermentor-ai)).
- **[Delivery Book](https://github.com/leandrokuranaga/Puc-delivery-book)** · projeto integrador da PUC-SP, .NET com Clean Architecture + React.
- **[MX7](https://github.com/leandrokuranaga/Tcc-unip)** · TCC na UNIP, React Native + Node.js, depois reescrito em [.NET](https://github.com/leandrokuranaga/unip-backend-tcc).

## Engenharia de agentes

A maioria dos engenheiros consome ferramentas de IA. Eu construo o harness em que elas rodam.

- **Ferramental de agentes** — MCP servers, subagentes, hooks e skills reutilizáveis sobre o Claude Code e o Claude Agent SDK
- **Times de agentes** — agentes de revisão, SRE, DevOps e QA ligados a Jira, Datadog, Playwright e Azure via MCP
- **Avaliação e guardrails** — suítes de prompts de regressão, asserções determinísticas sobre respostas estruturadas e gates de revisão antes do merge
- **Segurança de IA** — ferramentas com menor privilégio e aprovação humana nos fluxos de agentes

## Stack

Ordenada pela profundidade de domínio, não em ordem alfabética.

**Domínio** — .NET 8/10, C#, ASP.NET Core, Azure, SQL Server, arquitetura orientada a eventos, microsserviços, DDD, CQRS, APIs REST, xUnit

**Fluente** — Claude Code, MCP, Semantic Kernel, OpenAI/Azure OpenAI, avaliação de LLM, AWS (EKS, ECS, Lambda, SQS), Kubernetes, Helm, Terraform, GitHub Actions, Azure Service Bus, Kafka, RabbitMQ, Redis, PostgreSQL, InfluxDB, React, Next.js, Angular, Vue, TypeScript, Module Federation, Playwright, Testcontainers, Datadog, OpenTelemetry, Docker

**Contato** — PHP, Rust/Tauri, MongoDB, Elasticsearch, KurrentDB, Blip, SAP / Salesforce

## Formação

- **Computação Quântica**, pós-graduação · PUC Minas (em andamento)
- **Arquitetura de Software**, pós-graduação · FIAP (2025–2026)
- **Engenharia de Software**, especialização · PUC-SP (2021–2022)
- **Ciência da Computação**, bacharelado · UNIP (2016–2020)

Certificações: Anthropic (Introduction to MCP, Claude Code in Action, Agent Skills, AI Fluency) · EF SET C1 em inglês
