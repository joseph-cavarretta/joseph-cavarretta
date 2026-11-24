# Hi, I'm Joseph

Data & AI Platform Engineer building scalable data infrastructure, ML pipelines, and production LLM systems.
I work across the stack—from ingestion and orchestration to Kubernetes-based platforms and user-facing AI applications.

## What I do

- **Data & AI Platforms** — Design and operate scalable data, ML, and LLM infrastructure
- **ML & Data Pipelines** — End-to-end pipelines for training, inference, and analytics
- **GenAI & LLMs** — RAG systems, agent tooling, and structured extraction at scale
- **Data Products** — Self-serve platforms and internal tools that teams rely on

## Homelab

I run a self-hosted Kubernetes cluster ([`homelab`](https://github.com/joseph-cavarretta/homelab)) to operate data and ML platform infrastructure end-to-end:

- **Cluster & Provisioning** — k3s across an `x86_64` control plane (`arch-mini`) and 3 `arm64` Raspberry Pi workers, automated with `cloud-init` and Ansible
- **GitOps & Management** — Argo CD (app-of-apps with automated sync/prune/self-heal) and Rancher
- **Networking & Security** — MetalLB (L2 LoadBalancer), Traefik ingress with LAN-only IP allowlists, and `cert-manager`
- **Storage & ML Platform** — Garage (S3-compatible object storage) backing MLflow for experiment tracking and artifact storage

## Tech I work with

| Category | Technologies |
|----------|-------------|
| **Languages** | Python, SQL, Bash, Go |
| **Infrastructure** | Kubernetes, Terraform, Helm, Ansible, Argo CD, Docker |
| **Orchestration** | Prefect, Airflow |
| **Data** | Spark, Dataflow, BigQuery, Databricks, dbt |
| **AI/ML** | Vertex AI, MLflow, RAG systems, pgvector, OpenSearch |
| **Cloud** | GCP, AWS |

## Featured projects

| Project | What it is |
|---------|------------|
| [homelab](https://github.com/joseph-cavarretta/homelab) | Self-hosted k3s cluster provisioned with Ansible and managed via Argo CD GitOps |
| [agent-dev-harness](https://github.com/joseph-cavarretta/agent-dev-harness) | Standards, guardrails, and MCP servers for AI coding agents |
| [ekg-classifier](https://github.com/joseph-cavarretta/ekg-classifier) | Neural network classifying EKG signals into 5 arrhythmia categories (F1 0.97), trainable locally or on GCP Dataproc via Terraform |
| [billion-rows-challenge](https://github.com/joseph-cavarretta/billion-rows-challenge) | Benchmarking Polars, DuckDB, pandas, AWK, and more on aggregating 1 billion rows (14 GB CSV) |
| [kafka-spark-streaming](https://github.com/joseph-cavarretta/kafka-spark-streaming) | Real-time event pipeline: Kafka + Avro + Schema Registry → Spark Structured Streaming → Cassandra, fully Dockerized |
| [kube-plugins](https://github.com/joseph-cavarretta/kube-plugins) | Custom `kubectl` plugins in Go |

## Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joseph-cavarretta-87242871/)
