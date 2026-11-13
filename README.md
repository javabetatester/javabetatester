<h1 align="center">
   <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=600&height=70&duration=4000&lines=Hi+there!+I'm+Bernardo+Kunz+👋;Senior+Software+Engineer;Backend+%26+AI+Engineering" />
</h1>

<div align="center">

[![Linkedin](https://img.shields.io/badge/-LinkedIn-00AEFF?style=for-the-badge&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/bernardokunz)
[![Website](https://img.shields.io/badge/-Portfolio-00AEFF?style=for-the-badge&logo=Google-Chrome&logoColor=white)](https://github.com/javabetatester?tab=repositories)
[![Email](https://img.shields.io/badge/-Email-00AEFF?style=for-the-badge&logo=Gmail&logoColor=white)](mailto:bernardokunz@gmail.com)

</div>

## About Me

Senior Software Engineer working on backend, distributed systems and security since 2016. Experience with large-scale gaming platforms (40k+ concurrent players, p99 < 50 ms), mission-critical financial systems on Kafka, and AI engineering tooling (agent orchestration, LLM-as-judge evals, guardrails). Focused on high performance, low latency and developer productivity, with **Go** as my main stack and a strong **Java** background.

**Education**
- Bachelor's Degree in Software Engineering · FIAP
- Postgraduate in Software Architecture, emphasis on security · FIAP *(in progress)*

**Certifications:** BSCP · MCP Security · API Penetration Testing · API Security for PCI Compliance · API Security for Connected Cars and Fleets

---

## Core Competencies

- **AI systems architecture** · Agent orchestration with tool use over domain adapters, typed intent routing, grounding on native queries, hybrid retrieval (BM25 + embeddings), purpose-based routing with provider fallback, prompt caching, token metering and per-attempt cost.
- **Evaluation & guardrails** · Seeded paired baseline × candidate evals, McNemar test and 95% Wilson intervals, deterministic checks, rubric-based LLM-as-judge, infra errors isolated from the pass rate; prompt-leak canary and shingle guard at the output edge.
- **Distributed systems** · Event-driven multi-tenant platforms with Outbox and at-least-once delivery, idempotency keys, optimistic locking, rate limiting, retries with jitter and concurrency control; correlated traces, metrics and logs.
- **Security** · Large-scale anti-cheat and anti-abuse (packet inspection, statistical anomaly detection), reverse engineering and low-level dynamic analysis (decompilers, firmware, DMA), sandboxing, web and API pentesting, LLM guardrail bypass analysis.
- **Technical leadership & DevX** · Architecture direction through ADRs, engineering standards and internal libraries, context engineering for coding agents (skills, subagents, hooks), parallel worker orchestration, CI/CD integrated with evals.

---

## Technical Stack

### **Languages**
**Go** • **Java** • **TypeScript**

### **Messaging & APIs**
**gRPC** • **Apache Kafka** • **Amazon EventBridge** • **Amazon SQS**

### **Databases**
**PostgreSQL** • **DynamoDB** • **Redis** • **MySQL**

### **Cloud & Observability**
**AWS** • **Kubernetes (k3s)** • **OpenTelemetry**

### **AI Engineering**
**Claude** • **Multi-provider LLM routing** • **Evals (LLM-as-judge)** • **Guardrails** • **Hybrid retrieval**

---

## Experience Highlights

**MeuControle.AI** · Sr. Software Engineer, Applied AI & Backend *(2026 – present)*
- Conversational AI orchestrator in Go (gRPC, hexagonal): WhatsApp ordering bot and portal assistant on Claude, with 30+ domain adapters exposed as tools
- Multi-provider LLM layer with purpose-based routing, fallback and per-attempt usage metering; output-edge guardrails and reports grounded in typed native queries
- Evals harness with versioned batteries, budget guard and ephemeral candidate deploys on every push; integrated into CI, **−35% deployment errors**
- Multi-tenant platform with 25+ event-driven Go services (EventBridge, SQS + Outbox, DynamoDB, PostgreSQL, Redis, OpenTelemetry)
- Agent-assisted engineering: internal library with 37 skills and 18 role-based subagents; **+50% code reuse**, **+20% delivery speed**

**Lello Condomínios** · Software Engineer, Backend *(2025 – 2026)*
- Billing and payments in Java, Go and Kafka for Brazil's largest condominium manager (millions of transactions/month): idempotent consumers, dead-letter topics, boleto and PIX reconciliation
- Strangler-pattern modernization of a legacy monolith into event-driven services with zero downtime

**Hypixel Studios** · Software Engineer, Distributed Systems & Security *(2020 – 2024)*
- BungeeCord proxy network and Java (Netty) game servers for **40k+ concurrent players** (100k+ daily peaks) at **p99 < 50 ms**
- Real-time anti-cheat and anti-fraud pipeline with statistical anomaly detection over millions of daily events
- Hytale: server-side modding engine in Java with a plugin API, ECS systems and data-driven assets

**CraftLandia** · Software Developer, Systems & Platform *(2016 – 2020)*
- Proprietary anti-cheat in the Netty pipeline; Java backend for 13k+ concurrent users with a stable tick loop under load

---

## GitHub Stats

<div align="center">
  <img width="41%" height="195px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=javabetatester&layout=compact&hide_border=true&title_color=00AEFF&text_color=00AEFF&bg_color=0d1117" />
</div>

---

## 💬 Let's Connect

Always up for talking about AI engineering, distributed systems, performance and security. Open to collaborations and technical conversations.

---

<div align="center">
  <i>"Measure twice, optimize once."</i>
</div>
