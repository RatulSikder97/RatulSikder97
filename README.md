<div align="center">

# Hi, I'm Ratul Sikder 👋

### CTO • AI/ML Engineer • Researcher

I architect intelligent, cloud-native systems — from LLM-powered products and NLP engines to
high-throughput microservices that stay fast and reliable at scale. I care about clean
architecture, measurable performance, and turning research ideas into shipped software.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ratulsikder-arch/)
[![Email](https://img.shields.io/badge/Email-Reach%20me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ratulsikder.research@gmail.com)
[![GitHub](https://img.shields.io/badge/Follow-RatulSikder97-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RatulSikder97)

<img src="https://github-readme-activity-graph.vercel.app/graph?username=RatulSikder97&theme=tokyo-night&area=true&hide_border=true" width="100%"/>

</div>

---

## 🧭 About Me

- 🔭 **Currently** leading engineering as a CTO — owning architecture, AI strategy, and delivery.
- 🤖 **Focused on** applied AI/ML: LLM applications, NLP engines, and intelligent automation.
- 🔬 **Research-minded** — I enjoy taking ideas from papers to production-grade systems.
- ⚙️ **Builder at heart** — distributed backends, event-driven services, and platforms that scale.
- 🌱 **Always learning** — sharpening the edge between systems engineering and machine learning.

---

## 🧠 What I Build

- 🚀 High-performance **NestJS** & **Spring Boot** backend systems
- 🤖 **LLM-powered** applications, NLP engines & intelligent automation
- 🕸️ Distributed **microservices** with event-driven architecture
- ☁️ **Cloud-native** platforms on AWS, Docker & Kubernetes
- 📈 **AI/ML pipelines** with TensorFlow, PyTorch & model optimization workflows
- 🔍 **Observability** with the ELK Stack, Prometheus & Grafana
- 🗄️ Scalable data layers using MySQL, PostgreSQL & Redis

---

## 🚀 Featured Projects

> Every repo below is tested, CI-gated, and documented with architecture diagrams and real output.

### 🤖 Agentic AI & LLM Engineering

| Project | What it is | Stack |
| --- | --- | --- |
| [**rex-dex**](https://github.com/RatulSikder97/rex-dex) | One-person-company workbench: every department (eng, QA/DevOps, marketing, SEO, content, video) is an AI agent driven through Claude Code, Codex & other agent CLIs | TypeScript · Node · Agent CLIs |
| [**agentflow**](https://github.com/RatulSikder97/agentflow) | Durable workflow engine for LLM agent pipelines: YAML DAGs, checkpointed exactly-once steps, crash-resume, Redis Streams workers, SSE, OpenTelemetry | Go · Postgres · Redis |
| [**rag-eval-harness**](https://github.com/RatulSikder97/rag-eval-harness) | RAG pipeline that treats retrieval quality as a CI-gated regression test: hybrid pgvector + BM25, cited Claude answers, LLM-as-judge, recall@k / MRR / nDCG | Python · pgvector · Claude |
| [**mcp-postgres-insight**](https://github.com/RatulSikder97/mcp-postgres-insight) | Safe, read-only MCP server giving agents real Postgres insight: AST-guarded SQL, PII redaction, EXPLAIN-driven index advice, prompt-injection-aware output | TypeScript · MCP · PostgreSQL |
| [**stack_hub**](https://github.com/RatulSikder97/stack_hub) | Voice-preserving, human-gated AI content pipeline that fails loudly when its own output starts sounding like a model | Python · LLMs |

### 🛡️ AI Security, Platform & Ops

| Project | What it is | Stack |
| --- | --- | --- |
| [**agent-guard**](https://github.com/RatulSikder97/agent-guard) | A firewall for AI agent tool use: MCP security gateway with policy-as-code, prompt-injection and exfiltration defenses, human approvals, tamper-evident audit log | TypeScript · MCP · LLM Security |
| [**agent-redteam**](https://github.com/RatulSikder97/agent-redteam) | Automated red-teaming benchmark for tool-using LLM agents: 50 sandboxed attack scenarios (OWASP LLM / MITRE ATLAS), programmatic oracles, ablatable defenses, CI regression gating | Python · LLM Security · Claude |
| [**hostwarden**](https://github.com/RatulSikder97/hostwarden) | Single-binary Linux security auditor & compromise detector: 39 hardening checks, crypto-miner and persistence hunting, SARIF for code scanning, fleet scans over SSH | Go · Linux · DevSecOps |
| [**sre-copilot**](https://github.com/RatulSikder97/sre-copilot) | Agentic incident-response copilot: investigates alerts with read-only Prometheus / Loki / Kubernetes tools, proposes remediations behind a dry-run + human approval gate, hash-chained audit log | Python · Kubernetes · Claude |
| [**platform-blueprint**](https://github.com/RatulSikder97/platform-blueprint) | Reference AWS platform for LLM-backed microservices: Terraform (VPC, EKS + Karpenter, RDS pgvector, Valkey), hardened Helm chart, offline-tested plans, kind e2e in CI | Terraform · EKS · Helm · Go |

### 🏗️ Backend & Distributed Systems

| Project | What it is | Stack |
| --- | --- | --- |
| [**nest-saas-kit**](https://github.com/RatulSikder97/nest-saas-kit) | Multi-tenant SaaS backend: Postgres row-level security + app-layer isolation, rotating refresh tokens with reuse detection, API keys, BullMQ outbox, Redis rate limits | NestJS · TypeORM · Postgres · Redis |
| [**ledgerflow**](https://github.com/RatulSikder97/ledgerflow) | Event-driven double-entry ledger: balanced immutable entries, idempotent transfers, transactional outbox → Kafka, proven under concurrent load with Testcontainers | Spring Boot 3 · Java 21 · Kafka |

### 📊 Data & ML

| Project | What it is | Stack |
| --- | --- | --- |
| [**outbreak-forecast-mlops**](https://github.com/RatulSikder97/outbreak-forecast-mlops) | End-to-end MLOps for probabilistic dengue forecasting: LightGBM + conformal intervals, walk-forward backtests (MASE 0.21 vs 0.60 seasonal-naive), MLflow promotion gate, FastAPI serving, drift-triggered retraining | Python · MLflow · FastAPI · LightGBM |
| [**smart-retail-intelligence**](https://github.com/RatulSikder97/smart-retail-intelligence) | Big-data analytics on 719k GPS-tagged retail shops in Bangladesh: Spark pipeline for clustering, regression, classification & anomaly detection, Streamlit dashboard | Python · Spark · Docker |

### 🧩 Tools

| Project | What it is | Stack |
| --- | --- | --- |
| [**tabsync**](https://github.com/RatulSikder97/tabsync) | Chrome MV3 extension that saves, restores and syncs tab-group workspaces via Google Drive: offline-first, versioned, ⌘K palette | React · TypeScript · Vite |

---

## 🧰 Tech Stack & Expertise

**🤖 AI / ML & LLMs**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![RAG](https://img.shields.io/badge/RAG%20%2F%20Vector%20Search-4B8BBE?style=for-the-badge)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**💻 Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)

**⚙️ Backend & APIs**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244B5A?style=for-the-badge&logo=grpc&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![REST](https://img.shields.io/badge/REST%20APIs-005571?style=for-the-badge)

**🕸️ Distributed Systems**

![Microservices](https://img.shields.io/badge/Microservices-FF6B6B?style=for-the-badge)
![Event-Driven](https://img.shields.io/badge/Event--Driven-8E44AD?style=for-the-badge)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

**☁️ Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**🗄️ Data & Storage**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)

**📊 Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![ELK Stack](https://img.shields.io/badge/ELK%20Stack-005571?style=for-the-badge&logo=elasticstack&logoColor=white)

**🔬 Research**

![NLP](https://img.shields.io/badge/NLP-4B8BBE?style=for-the-badge)
![Model Optimization](https://img.shields.io/badge/Model%20Optimization-EE4C2C?style=for-the-badge)
![Experiment Design](https://img.shields.io/badge/Experiment%20Design-8E44AD?style=for-the-badge)
![Applied ML Systems](https://img.shields.io/badge/Applied%20ML%20Systems-009688?style=for-the-badge)

---

## 🔥 Areas of Expertise

| Domain | Focus |
| --- | --- |
| 🧩 **AI / ML Engineering** | LLM apps, NLP, feature optimization & model performance tuning |
| 🏗️ **System Architecture** | Microservices, event-driven & distributed design |
| ⚡ **API Performance** | Low-latency, high-throughput backend platforms |
| 🔐 **Secure Backends** | Scalable, resilient, production-grade services |
| 📊 **Observability** | Monitoring, tracing & data-driven reliability |

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=RatulSikder97&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RatulSikder97&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=RatulSikder97&theme=tokyonight&hide_border=true" width="60%"/>

</div>

---

## 🤝 Let's Connect

<div align="center">

I'm always open to collaborating on ambitious systems, AI products, and research-driven engineering.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ratulsikder-arch/)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ratulsikder.research@gmail.com)

<br/>

<i>“Code is the closest thing we have to magic.”</i>

<img src="https://komarev.com/ghpvc/?username=RatulSikder97&style=flat-square&color=blueviolet" alt="Profile views" />

</div>
