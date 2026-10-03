# Hemanth Kumar

**Senior Software Engineer: backend, distributed systems, and AI-powered data systems.**

I build backend services and the data infrastructure behind them: microservices in Go and TypeScript, analytics pipelines on ClickHouse and StarRocks, and LLM and embedding features that run against production data. Currently at Avacend Inc; previously a founding engineer on a startup product at Constient Global Solutions. Based in Bengaluru, India.

## What I Build

- **Backend services and microservices**: REST and gRPC APIs in Go, NestJS and FastAPI, with multi-tenancy, RBAC and JWT authentication.
- **Distributed and real-time systems**: Kafka and RabbitMQ pipelines, Redis-backed WebSockets, offline-first sync.
- **Data-intensive systems**: ClickHouse and StarRocks schema design, high-volume batch ingestion, PostgreSQL indexing and query tuning.
- **AI-powered backends**: text-to-SQL with GPT-4o, semantic search with pgvector, embedding and clustering pipelines.
- **Cloud infrastructure**: Docker, Kubernetes, FluxCD GitOps, GitHub Actions pipelines with Trivy scanning.

## Experience

**Avacend Inc, Senior Software Engineer** (Dec 2024 – Present)

- Architected a multi-tenant FastAPI backend with RBAC, JWT authentication and asynchronous ClickHouse access.
- Designed a ClickHouse analytics schema on ReplacingMergeTree, loaded with 100K-row batch inserts across 8 parallel threads and exponential-backoff retries.
- Built a text-to-SQL pipeline that uses GPT-4o to turn natural-language questions into ClickHouse queries.
- Analyzed 33,000 HVAC maintenance work orders with SentenceTransformers, HDBSCAN and UMAP to power semantic search and clustering for predictive analytics.
- Built Python pipelines against an OAuth2 API with automatic token refresh and incremental sync, feeding production dashboards covering 10+ KPIs.

**Constient Global Solutions, Senior Software Engineer** (Nov 2022 – Dec 2024)

- Founding engineer on a startup product; designed its REST API backend as Go microservices.
- Architected a distributed log management system on StarRocks and Kafka.
- Implemented gRPC communication between Python and Go services, and published SDKs integrating OpenAI APIs.
- Tuned PostgreSQL, ClickHouse and StarRocks performance; built Go CLI tooling; deployed with Docker and Kubernetes.
- Built the Next.js and Tailwind frontend with real-time visualization and AI-recommended filters, with Jest tests at 90% coverage.

## Tech Stack

| Area | Technologies |
| --- | --- |
| Languages | Go, TypeScript, Python, SQL |
| Backend | NestJS, FastAPI, Node.js, gRPC, REST, WebSockets, Envoy |
| Databases | PostgreSQL, ClickHouse, StarRocks, MongoDB, Neo4j, CockroachDB, Redis, DragonflyDB, Prisma |
| Messaging and sync | Kafka, RabbitMQ, pg-boss, PowerSync |
| AI / ML | GPT-4o, RAG, pgvector, Pinecone, SentenceTransformers, HDBSCAN, UMAP |
| Infrastructure | Docker, Kubernetes, FluxCD, GitHub Actions, Trivy, AWS, GCP, Cloudflare, Hetzner, Dokploy |
| Frontend | React, Next.js, React Native, TailwindCSS, Jest |

## Featured Projects

### Sitekeep: Facilities Maintenance SaaS

A multi-tenant facilities maintenance platform built on NestJS and PostgreSQL 17. *Private repository.*

- Tenant isolation enforced in the database with PostgreSQL Row-Level Security.
- Offline-first synchronization using PowerSync.
- AI search over maintenance history using pgvector.
- Background scheduling with pg-boss.
- Deployed to Hetzner Cloud with Dokploy.

**Stack:** NestJS, PostgreSQL 17, pgvector, PowerSync, pg-boss, Hetzner, Dokploy

### Amour: Dating App

A dating app backend built as NestJS microservices with a gRPC transport layer and hexagonal architecture. *Private repository.*

- 68+ services communicating over gRPC, with 16 proto service definitions and Envoy integration.
- 68-model Prisma schema with 141 BTREE indexes; optimized chat list queries and eliminated N+1 queries in the recommendation services.
- RabbitMQ priority queuing (CRITICAL / HIGH / NORMAL / LOW), with circuit breakers and database failover.
- Redis-backed Socket.io infrastructure with cross-pod message delivery and offline message queuing.
- FluxCD GitOps, multi-stage ARM64/x86 Docker builds, Kubernetes rolling deployments and Trivy vulnerability scanning.

**Stack:** NestJS, gRPC, Envoy, Prisma, PostgreSQL, RabbitMQ, Redis, Socket.io, Kubernetes, FluxCD

### Public code

- [Cognia](https://github.com/hemanthkumar-eng/Cognia): a voice-based English practice app for students, built with React Native and Sarvam AI speech and language models.

## Engineering Interests

Distributed systems · Backend architecture · Database performance · AI infrastructure · Cloud engineering · System design

## Connect

- [LinkedIn](https://www.linkedin.com/in/hemanth-kumar-763011165/)
- [Portfolio](https://hemanth38-portfolio.vercel.app/)
