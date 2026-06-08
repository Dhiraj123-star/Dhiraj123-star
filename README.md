# Hi, I'm Dhiraj Kumar 👋

**Backend Engineer · GenAI/LLM Systems · Cloud & Platform Engineering**

I build **production-grade AI-powered backend systems** — from LLM pipelines and RAG architectures to distributed batch processing and cloud-native deployments. I don't just integrate AI; I engineer the infrastructure around it that makes it reliable, scalable, and cost-efficient.

---

## 🚀 What I've Shipped

> Real systems. Real scale. Real production.

| What | How | Impact |
|---|---|---|
| 50K+ domain batch processing | Celery + SQS FIFO + PgBouncer | Zero data loss across crashes & deployments |
| LLM pipeline migration | OpenAI Assistants API → Responses API | Zero downtime, cut latency + Redis dependency |
| Hybrid RAG search engine | DuckDB + Qdrant + Cohere Reranker | Powers cultural relevance scoring (CRS™) in production |
| 6 SSP/DSP reporting integrations | Index Exchange, PubMatic, Media.Net, Equativ, OpenX, Magnite | Nightly ingestion, unified dashboard |
| MCP protocol middleware | AI Platform ↔ Hexagon DSP | Autonomous campaign creation via natural language |
| Video AI pipeline | AllTold + SQS FIFO + Celery + GPT-4 | Parallel CRS + Persona + Blueprint generation |
| AWS RDS cost optimisation | Graviton3 (db.m7g.large) upgrade | ~20% cost saving, handles 50K+ write bursts |

---

## 🧠 Core Expertise

### GenAI & LLM Systems
- **RAG Pipelines** — Retrieval-Augmented Generation with hybrid search (keyword + semantic), Cohere reranking, cache-first fallback (Redis → DB → API)
- **OpenAI Ecosystem** — Responses API, Assistants API, function calling, streaming with AbortController, multimodal inputs (text, image, PDF, video)
- **GraphRAG** — Neo4j knowledge graph ingestion, LLM entity extraction, smart query routing across domain/audience data
- **Vector Search** — Qdrant semantic search, DuckDB keyword retrieval, multi-collection hybrid retrieval with domain boost rules
- **Agents & Orchestration** — LangChain, LangGraph, CrewAI, OpenAI Agents, multi-agent workflows, MCP / ACP / A2A protocols
- **Prompt Engineering** — Zero-Shot, Few-Shot, Chain-of-Thought, Single-Shot, Style-Based, temperature tuning

### Backend & System Architecture
- **Frameworks** — FastAPI, Django (DRF), Flask · async APIs, REST, WebSockets, streaming responses
- **Async Processing** — Celery (`acks_late`, `reject_on_worker_lost`, `-O fair`), Celery Beat schedulers, SQS FIFO guaranteed delivery, exponential backoff + jitter
- **Connection Management** — PgBouncer transaction mode, `CONN_MAX_AGE=0`, connection pool math (nodes × pool = total RDS connections)
- **Design Patterns** — Microservices, CQRS, Event Sourcing, Domain-Driven Design, Clean Architecture
- **Reliability** — Cache-first architecture, retry logic, dead letter queues, rate limiting, graceful SIGTERM shutdown

### Database Engineering
- **Relational** — PostgreSQL (advanced indexing, triggers, views, stored procedures, query plan analysis), MySQL, SQLite
- **Specialised** — DuckDB + Parquet (columnar analytics), Neo4j (knowledge graphs), Qdrant (vector store), Redis (caching + broker), Chroma DB
- **Scale patterns** — Sharding, partitioning, replication, PgBouncer pooling, 10x query optimisation via strategic indexing

### Cloud & DevOps
- **AWS** — EC2, RDS, S3 (+ lifecycle → Glacier), SQS FIFO, CloudFront CDN, IAM (least-privilege roles/policies), CloudWatch
- **Containers & Orchestration** — Docker (non-root, stripped runtime images, immutable builds), Kubernetes (K8s, Helm, auto-scaling), Docker Compose
- **Nginx** — HTTP/2, TLS 1.3, HSTS, `server_tokens off`, gzip, unbuffered proxy for streaming, Keepalive upstream pools
- **IaC** — Terraform, Ansible, CloudFormation
- **CI/CD** — GitHub Actions, GitLab CI, CircleCI, Jenkins · blue-green, canary releases, automated security scanning

### Observability & SRE
- **Monitoring** — Prometheus, Grafana, CloudWatch
- **Logging** — ELK Stack (Elasticsearch, Logstash, Kibana), Loki
- **Practices** — Distributed tracing (OpenTelemetry), SLA/SLO monitoring, incident response, chaos engineering

### Message Brokers & Event-Driven
- Apache Kafka (streaming pipelines, Kafka Streams, real-time analytics)
- RabbitMQ, Celery Beat, SQS FIFO — async task processing, workflow orchestration

---

## 🛠️ Tech Stack

```
Languages       Python · SQL · Go · TypeScript
Backend         FastAPI · Django · Flask · Celery · WebSockets
AI / LLM        OpenAI · LangChain · LangGraph · CrewAI · RAG · Qdrant
                Cohere · GraphRAG · Neo4j · MCP · ACP · A2A
Databases       PostgreSQL · DuckDB · Neo4j · Qdrant · Redis · MySQL · Parquet
Message Queues  Apache Kafka · RabbitMQ · SQS FIFO · Celery
Cloud           AWS (EC2 · RDS · S3 · SQS · CloudFront · IAM · ECS · EKS · Lambda)
Orchestration   Kubernetes · Helm · Docker · Docker Compose
IaC             Terraform · Ansible · CloudFormation
CI/CD           GitHub Actions · GitLab CI · CircleCI · Jenkins
Observability   Prometheus · Grafana · ELK Stack · Loki · OpenTelemetry
Data Tools      Scrapy · Pandas · BeautifulSoup · Selenium · ETL Pipelines
```

---

## 💼 Experience Highlights

**4.5 years** building backend systems across AI SaaS, ERP, and data engineering:

- Architected and shipped AI-powered SaaS platforms — LLM pipelines, reporting dashboards, SSP/DSP integrations, and MCP campaign automation — primarily as the **sole engineer** across multi-phase, long-running projects
- Built batch processing systems handling **50K+ records** with zero data loss using layered reliability: queue guarantees (SQS FIFO) + task acknowledgement (Celery acks_late) + connection pooling (PgBouncer)
- Delivered **hybrid RAG search** combining DuckDB keyword search + Qdrant semantic search + Cohere reranking — powering a Cultural Relevance Score (CRS™) platform launched April 2026 with advisory board from Google, WPP Media, PubMatic, and OpenX
- Integrated **6 SSP reporting APIs** with auto-renewing auth, nightly Celery ingestion, and unified analytics dashboard — handling daily data from Index Exchange, PubMatic, Media.Net, Equativ, OpenX, and Magnite
- **Migrated OpenAI Assistants API → Responses API** in production with zero downtime — refactored thread/run lifecycle to stateless Prompt ID persistence
- Engineered **Odoo/OpenERP** backend systems (PostgreSQL, stored procedures, triggers) for service, manufacturing, and engineering-domain enterprise clients

---

## 📚 Currently Exploring

- **Advanced Kubernetes** — service mesh (Istio), platform engineering, K8s operators
- **GraphRAG at scale** — Neo4j + Qdrant combined retrieval, entity disambiguation
- **OpenTelemetry** — end-to-end distributed tracing across async Celery + FastAPI systems
- **Kafka Streams** — stateful stream processing, exactly-once semantics
- **Multi-agent systems** — LangGraph stateful agents, CrewAI enterprise workflows, A2A protocol

---

## 📫 Get in Touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dhiraj_Kumar-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/dhiraj-kumar-993447204)
[![GitHub](https://img.shields.io/badge/GitHub-Dhiraj123--star-181717?style=flat&logo=github)](https://github.com/Dhiraj123-star)
[![Email](https://img.shields.io/badge/Email-gdhiraj499@gmail.com-D14836?style=flat&logo=gmail)](mailto:gdhiraj499@gmail.com)
