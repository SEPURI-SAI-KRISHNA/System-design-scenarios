# 📁 Scenarios

This directory contains **74 system design scenario files** (`S1.md` – `S74.md`). Each file presents one or more interview-style problems at varying difficulty levels (Easy → Hard / Lead Architect), followed by a detailed, structured solution.

---

## 📖 What Each Scenario Contains

- **Problem statement** — a realistic engineering challenge framed as an interview question.
- **Difficulty levels** — Easy, Medium, and Hard variants within the same topic.
- **Solution walkthrough** — requirements, data flow, component choices, trade-offs, and bottlenecks.
- **Design rationale** — explains *why* a particular technology or pattern was chosen.

---

## 🎯 How to Use This Section

1. **Read the problem statement only** — close the file and design the system yourself first.
2. **Sketch your design** — draw the components, define data flows, estimate capacity.
3. **Reopen and compare** — identify gaps, missed trade-offs, or better alternatives.
4. **Work through difficulty levels in order** — the Easy variant builds intuition; Hard and Lead Architect variants add operational depth.

> **Suggested order:** Work through S1 → S30 sequentially to build a strong base before tackling the advanced scenarios (S31+).

---

## 🗂️ Scenario Index

### Foundations of Scalability & Storage

| File | Topic |
|------|-------|
| [S1.md](S1.md) | Scalability foundations & high-throughput log ingestion |
| [S2.md](S2.md) | Read scalability — caching strategy for extreme read load |
| [S3.md](S3.md) | Database internals & indexing (OLTP vs. OLAP vs. Geo-spatial) |
| [S18.md](S18.md) | Back-of-the-envelope capacity estimation |
| [S19.md](S19.md) | Database sharding — horizontal partitioning at scale |

---

### API Design & Communication Patterns

| File | Topic |
|------|-------|
| [S4.md](S4.md) | API patterns — REST, GraphQL, gRPC, synchronous vs. asynchronous |
| [S29.md](S29.md) | API Gateway & Backend for Frontend (BFF) pattern |

---

### Message Queues & Event Streaming

| File | Topic |
|------|-------|
| [S5.md](S5.md) | Message queues — SQS, RabbitMQ, and Apache Kafka compared |
| [S39.md](S39.md) | Kafka internal storage & zero-copy architecture |
| [S40.md](S40.md) | Kafka exactly-once semantics (EOS) |

---

### Batch & Stream Processing

| File | Topic |
|------|-------|
| [S6.md](S6.md) | Batch vs. stream processing architectures |
| [S21.md](S21.md) | Lambda vs. Kappa architectures |
| [S37.md](S37.md) | Apache Flink & unbounded stream processing |
| [S38.md](S38.md) | Stateful checkpointing & the Chandy-Lamport algorithm |
| [S62.md](S62.md) | Complex Event Processing (Flink CEP) for fraud detection |
| [S67.md](S67.md) | Flink exactly-once guarantees & failure recovery |

---

### Observability & Reliability

| File | Topic |
|------|-------|
| [S7.md](S7.md) | Observability — metrics, logs, and distributed tracing |
| [S17.md](S17.md) | Distributed consensus — Raft, ZooKeeper, etcd, split-brain problem |
| [S27.md](S27.md) | Data quality & pipeline observability |
| [S63.md](S63.md) | Data platform monitoring & alerting |
| [S64.md](S64.md) | Incident response & on-call runbooks |

---

### Container Orchestration & Infrastructure

| File | Topic |
|------|-------|
| [S8.md](S8.md) | Kubernetes — stateless deployments, services, stateful apps |
| [S42.md](S42.md) | Container orchestration at scale |
| [S43.md](S43.md) | Infrastructure as Code with Terraform |
| [S44.md](S44.md) | Cloud networking — VPCs, subnets, and security groups |
| [S45.md](S45.md) | CI/CD pipelines for distributed systems |
| [S47.md](S47.md) | Cloud cost optimization |

---

### Security & Identity

| File | Topic |
|------|-------|
| [S9.md](S9.md) | Authentication, authorization & zero-trust networks |
| [S16.md](S16.md) | Advanced rate limiting strategies |
| [S46.md](S46.md) | IAM & cloud security (least-privilege access) |
| [S48.md](S48.md) | Data encryption & row-level security |

---

### Multi-Region & Global Systems

| File | Topic |
|------|-------|
| [S10.md](S10.md) | Multi-region architecture & global state synchronization |

---

### Real-World Case Studies

| File | Topic |
|------|-------|
| [S11.md](S11.md) | Deconstructing Uber — location ingestion, spatial indexing, matching |
| [S12.md](S12.md) | Deconstructing Netflix — video ingestion, transcoding, CDN streaming |
| [S13.md](S13.md) | Deconstructing WhatsApp & Discord — 2 billion concurrent connections |
| [S30.md](S30.md) | Design Ticketmaster — high-concurrency seat reservation |
| [S50.md](S50.md) | Uber's real-time surge pricing engine |

---

### E-Commerce & Distributed Transactions

| File | Topic |
|------|-------|
| [S14.md](S14.md) | Distributed shopping cart, inventory concurrency & idempotency |
| [S20.md](S20.md) | Distributed transactions — Two-Phase Commit & Saga pattern |

---

### ML, AI & Generative AI Systems

| File | Topic |
|------|-------|
| [S15.md](S15.md) | ML feature store & recommendation system architecture |
| [S57.md](S57.md) | ML platform & LLMOps for data-driven products |
| [S58.md](S58.md) | Retrieval-Augmented Generation (RAG) & vector search |
| [S60.md](S60.md) | LLM agent orchestration with memory and tool use |

---

### Data Warehouse, Lakehouse & Storage Formats

| File | Topic |
|------|-------|
| [S23.md](S23.md) | Data Warehouse vs. Data Lake vs. Lakehouse |
| [S31.md](S31.md) | Medallion Architecture (Bronze / Silver / Gold layers) |
| [S52.md](S52.md) | Lakehouse transactional formats — Delta Lake & Apache Iceberg |

---

### Data Modeling

| File | Topic |
|------|-------|
| [S32.md](S32.md) | Slowly Changing Dimensions (SCDs) |
| [S33.md](S33.md) | Fact table design patterns |
| [S61.md](S61.md) | Data Vault modeling for multi-source enterprise warehouses |

---

### Workflow Orchestration

| File | Topic |
|------|-------|
| [S24.md](S24.md) | Apache Airflow — DAG design & dependency management |
| [S53.md](S53.md) | Advanced Airflow — dynamic task generation & scaling |

---

### Data Transformation with dbt

| File | Topic |
|------|-------|
| [S26.md](S26.md) | dbt (data build tool) & ELT pipelines |
| [S51.md](S51.md) | Advanced dbt — Jinja macros & DRY SQL |
| [S59.md](S59.md) | dbt testing & data quality enforcement |

---

### Data Governance, Catalog & Contracts

| File | Topic |
|------|-------|
| [S25.md](S25.md) | Data Mesh architecture & domain ownership |
| [S49.md](S49.md) | Data catalog & metadata governance |
| [S54.md](S54.md) | Data contracts — schema evolution & upstream coordination |
| [S56.md](S56.md) | Organizational data strategy & decentralized data teams |

---

### Change Data Capture & Real-Time OLAP

| File | Topic |
|------|-------|
| [S22.md](S22.md) | Change Data Capture (CDC) with Debezium |
| [S28.md](S28.md) | Real-Time OLAP — ClickHouse & Druid for customer-facing analytics |

---

### Apache Spark (Deep Dive)

| File | Topic |
|------|-------|
| [S34.md](S34.md) | Spark physical execution — driver, executors, DAG |
| [S35.md](S35.md) | Advanced Spark joins — broadcast, sort-merge, shuffle |
| [S36.md](S36.md) | Spark memory management & OOM debugging |
| [S65.md](S65.md) | Spark Catalyst Optimizer & query planning |
| [S66.md](S66.md) | Spark shuffle — data movement across the network |

---

### Systems Programming & Low-Level I/O

| File | Topic |
|------|-------|
| [S68.md](S68.md) | Zero-copy I/O & kernel/user space optimization |
| [S69.md](S69.md) | Memory-mapped files, page cache, and DPDK |

---

### Event-Driven Architecture

| File | Topic |
|------|-------|
| [S41.md](S41.md) | Event Sourcing & CQRS |

---

### Data Security & Compliance

| File | Topic |
|------|-------|
| [S48.md](S48.md) | Data encryption & column-level access control |
| [S74.md](S74.md) | GDPR Right to be Forgotten in append-only systems |

---

### Data Activation & Cloud Platforms

| File | Topic |
|------|-------|
| [S55.md](S55.md) | Serving layer — making warehouse data queryable by applications |
| [S70.md](S70.md) | Reverse ETL & operational data activation |
| [S71.md](S71.md) | Snowflake & Databricks — enterprise cloud data platforms |
| [S72.md](S72.md) | CI/CD for data — testing and deploying warehouse changes safely |
| [S73.md](S73.md) | End-to-end system design interview framework (Lambda/Kappa) |

---

## 🤝 Contributing

Spotted an error or want to suggest a new scenario? Open an issue or pull request on the root repository.

---

## 📄 License

Content is shared for educational purposes. Please credit the source if you reuse or adapt any material.

---

<sub>← Back to [repository root](../README.md) · by [Sepuri Sai Krishna](https://github.com/SEPURI-SAI-KRISHNA)</sub>
