# Hi, I'm Pedro 👋
**Total Rewards Technology & Quantitative Compensation Systems**  
*Engineering Scalable Compensation Engines, Modern Agentic AI Workflows & Cloud Infrastructure*

[![GitHub](https://img.shields.io/badge/GitHub-pedrogriff-181717?style=flat&logo=github)](https://github.com/pedrogriff)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9-blue?style=flat&logo=typescript)](https://github.com/pedrogriff/nextcomp)
[![Next.js](https://img.shields.io/badge/Next.js-15%20App%20Router-black?style=flat&logo=next.js)](https://github.com/pedrogriff/nextcomp)
[![Python](https://img.shields.io/badge/Python-3.11%20%7C%203.12%20%7C%203.13-blue?style=flat&logo=python)](https://python.org)
[![pgvector](https://img.shields.io/badge/pgvector-Cosine%20Search%20(%3C%3D%3E)-336791?style=flat&logo=postgresql)](https://github.com/pedrogriff/nextcomp)
[![Trigger.dev](https://img.shields.io/badge/Trigger.dev-v3%20Workers-00F2FE?style=flat)](https://github.com/pedrogriff/nextcomp)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-Talos%20Linux%20v1.36-326ce5?style=flat&logo=kubernetes&logoColor=white)](https://github.com/pedrogriff/homelab-k8s-talos)
[![Topology](https://img.shields.io/badge/Topology-Multi--Node%20Cluster-blue?style=flat&logo=kubernetes&logoColor=white)](https://github.com/pedrogriff/homelab-k8s-talos)
[![Disaster Recovery](https://img.shields.io/badge/Disaster%20Recovery-Velero%20%26%20MinIO%20S3-0052CC?style=flat&logo=minio&logoColor=white)](https://github.com/pedrogriff/homelab-k8s-talos)
[![CI/CD](https://img.shields.io/badge/CI%2FCD-Self--Hosted%20ARC%20Runners-black?style=flat&logo=githubactions&logoColor=white)](https://github.com/pedrogriff/homelab-k8s-talos)
[![SSO](https://img.shields.io/badge/Identity-Authentik%20SSO-blue?style=flat&logo=authentik&logoColor=white)](https://github.com/pedrogriff/homelab-k8s-talos)
[![MCP](https://img.shields.io/badge/MCP-FastMCP%20Server-8A2BE2?style=flat)](https://github.com/pedrogriff/homelab-k8s-talos)
[![eBPF](https://img.shields.io/badge/eBPF-Cilium%20%26%20Hubble-blue?style=flat&logo=cilium&logoColor=white)](https://github.com/pedrogriff/homelab-k8s-talos)
[![GitOps](https://img.shields.io/badge/GitOps-ArgoCD-orange?style=flat&logo=argo&logoColor=white)](https://github.com/pedrogriff/homelab-k8s-talos)
[![Observability](https://img.shields.io/badge/Observability-Prometheus%20%26%20Grafana-F46800?style=flat&logo=grafana&logoColor=white)](https://github.com/pedrogriff/homelab-k8s-talos)
[![Code Style](https://img.shields.io/badge/Code%20Style-Ruff-000000?style=flat&logo=ruff)](https://github.com/astral-sh/ruff)
[![Type Checked](https://img.shields.io/badge/Type%20Checked-MyPy%20Strict%20%7C%20TypeScript-brightgreen)](https://mypy-lang.org)
[![AI Fluency](https://img.shields.io/badge/AI%20Fluency-Agentic%20Tool%20Calling-blueviolet)](https://github.com/pedrogriff)
[![Agent Mesh](https://img.shields.io/badge/Agent%20Orchestrator-Stateful%20HITL%20DAG-blueviolet)](https://github.com/pedrogriff/people-agent-mesh)

---

### 💡 Overview
Specialized in engineering high-throughput computational tools, deterministic financial simulation engines, and modern **agentic AI workflows** for total rewards and enterprise compensation. Combining deep domain expertise in compensation mechanics with software craftsmanship, algorithmic rigor, and cloud-native distributed infrastructure.

---

### 🚀 Featured Technical Systems

| System | Focus & Capabilities | Tech Stack | Status |
| :--- | :--- | :--- | :--- |
| **[`people-agent-mesh`](https://github.com/pedrogriff/people-agent-mesh)** | Enterprise multi-agent orchestration, human-in-the-loop (HITL) governance, and automated evaluation platform for sensitive People Operations across Brazil 🇧🇷 (CLT/LGPD), United States 🇺🇸 (FLSA/Title VII), and Canada 🇨🇦 (PIPEDA). Implements a stateful checkpointed supervisor DAG with pause/resume execution, bi-directional PII/SPII tokenization (CPF/SSN/SIN), hierarchical ABAC security trimming, resilient Pydantic v2 tool contracts with circuit breakers and idempotency, OpenTelemetry GenAI tracing, and automated CI quality gates blocking eval regressions. | Python 3.13, Stateful Multi-Agent DAG, Pydantic v2, Zero-Retention PII Tokenizer, ABAC Security Trimming, Circuit Breakers, OpenTelemetry GenAI, Pytest, Golden Evals | [![CI](https://github.com/pedrogriff/people-agent-mesh/actions/workflows/ci.yml/badge.svg)](https://github.com/pedrogriff/people-agent-mesh/actions) |
| **[`nextcomp`](https://github.com/pedrogriff/nextcomp)** | Enterprise total rewards & compensation intelligence platform. Features a formally verified compensation calculation engine (midpoint/spread invariants, compa-ratio, range penetration, and green/red-circle boundaries) paired with an asynchronous **Trigger.dev v3** pipeline executing **pgvector (`<=>`)** cosine similarity retrieval against Radford market benchmarks and structured **Vercel AI SDK** LLM evaluations enforcing the WorldatWork 80% duty match rule. | Next.js 15, TypeScript 5, Prisma ORM, PostgreSQL (pgvector), Trigger.dev v3, Vercel AI SDK (gpt-4o, text-embedding-3-large), Vitest, Tailwind v4 | Active |
| **[`comp-flow-platform`](https://github.com/pedrogriff/comp-flow-platform)** | Agentic compensation calibration & workflow platform. Orchestrates autonomous ReAct compliance loops with deterministic tool-calling (salary bands, equity guidelines, compa-ratio calculations) and state machine governance for calibration committees. Audits 60,000+ proposals/sec. | Python 3.13, Agentic ReAct, State Machines, Tool Calling, Pytest | [![CI](https://github.com/pedrogriff/comp-flow-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/pedrogriff/comp-flow-platform/actions) |
| **[`vesting-sim-engine`](https://github.com/pedrogriff/vesting-sim-engine)** | High-throughput Monte Carlo simulation & equity valuation engine. Distributes complex vesting schedules (such as front-loaded 33/33/22/12) using the **Largest Remainder Method** to guarantee exact share conservation ($\sum s_i \equiv S_{\text{total}}$). Evaluates millions of price paths in parallel across worker pools. | Python 3.13, Multiprocessing, Hypothesis, GBM Stochastic Modeling | [![CI](https://github.com/pedrogriff/vesting-sim-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/pedrogriff/vesting-sim-engine/actions) |
| **[`algocore-ds`](https://github.com/pedrogriff/algocore-ds)** | Computational laboratory for foundational algorithms, memory profiling, and high-performance indexing. Implements cache-aware contiguous dynamic arrays, circular ring buffers, open-addressing HashMaps with Tombstones, and augmented AVL trees with $O(\log N)$ percentile calculation. | Python 3.13, Ctypes Contiguous Memory, Pytest, Benchmarks | [![CI](https://github.com/pedrogriff/algocore-ds/actions/workflows/ci.yml/badge.svg)](https://github.com/pedrogriff/algocore-ds/actions) |
| **[`homelab-k8s-talos`](https://github.com/pedrogriff/homelab-k8s-talos)** | Declarative, immutable multi-node distributed Kubernetes platform on **Proxmox VE** and **Talos Linux (v1.13)**. Features **Velero & MinIO S3** automated disaster recovery & volume backups, self-hosted autoscaling **Actions Runner Controller (ARC)** CI/CD runners, containerized **FastMCP Compensation Microservices** with anti-affinity, **Authentik Enterprise OIDC Single Sign-On**, **SOPS & Age** asymmetric GitOps secrets, **ArgoCD** continuous delivery, **Cilium eBPF** kernel routing & **Hubble UI** network radar, **Prometheus & Grafana** observability, and **cert-manager** PKI. | Multi-Node Kubernetes v1.36, Talos Linux, Velero, MinIO S3, Actions Runner Controller (ARC), Authentik OIDC, FastMCP, SOPS/Age, Cilium (eBPF), ArgoCD, Prometheus, Grafana, cert-manager, Proxmox VE, IaC | Active |

---

### 🛠️ Technical Toolkit & Core Competencies

* **AI Fluency & Agentic Systems**: Multi-Agent DAG Orchestration, Stateful Human-in-the-Loop (HITL) Checkpoints, Zero-Retention PII/SPII Tokenization (LGPD · PIPEDA · US), Model Context Protocol (MCP / FastMCP), LLM-as-a-Judge & Golden CI Quality Gates, OpenTelemetry GenAI Tracing, Agentic ReAct Loops, Vercel AI SDK (`@ai-sdk/openai`), Dense 1536-dim Vector Embeddings (`text-embedding-3-large`), Vector Nearest Neighbors (`<=>`), Structured LLM Outputs (Pydantic v2 / Zod), Asynchronous Background Workers (Trigger.dev v3), WorldatWork 80% Duty Match Governance.
* **Core Software Engineering**: Modern TypeScript / Next.js 15 (App Router, Server Actions), Prisma ORM with PostgreSQL & pgvector, Modern Python (Strict Type Annotations, PEP 695 Generics), Java Backend Architecture, Parallel & Multi-Process Computing (`ProcessPoolExecutor`), Continuous Integration (`GitHub Actions`).
* **Cloud & Distributed Infrastructure**: Multi-Node Distributed Kubernetes (v1.36 on Talos Linux), Control Plane vs Worker Separation, Velero & MinIO S3 Disaster Recovery & Snapshot Automation, Self-Hosted Ephemeral CI/CD Runners (Actions Runner Controller - ARC), Authentik OIDC Single Sign-On & Centralized RBAC, FastMCP Microservices, Cilium eBPF Datapath & Zero-Trust L7 Security Policies, Hubble Observability Radar, GitOps Continuous Delivery (ArgoCD), SOPS & Age Asymmetric Secrets, Full-Stack Prometheus & Grafana Telemetry, Automated 2-Tier PKI (`cert-manager`), Proxmox VE Bare-Metal Virtualization.
* **Quantitative Compensation & Analytics**: Total Rewards Mathematical Modeling, Reciprocal Midpoint & Spread Band Invariants, Compa-Ratio & Range Penetration Dynamics, Green/Red-Circle Boundary Governance, Equity Grant Dynamics (GSUs/PSUs), Discrete Allocation Algorithms, Stochastic Valuation (Geometric Brownian Motion).
* **Code Health & Reliability**: Test-Driven Development (TDD), Vitest & Pytest Automated Suites, Property-Based Testing (`Hypothesis`), Linter Automation (`ESLint`, `Ruff`, `MyPy Strict`), Automated CI/CD Pipelines.

---

### 🏛️ Engineering & Design Principles
1. **Financial & Mathematical Precision**: Zero rounding drift and formally verified invariants across all compensation models.
2. **Intelligent Agentic Workflows**: Augmenting complex compensation cycles with transparent, scalable, and reproducible AI tool systems.
3. **Cloud-Native Reliability**: Declarative, reproducible infrastructure with strict code health standards (>90% test coverage).

---
*Exploring scalable compensation infrastructure, agentic AI systems, and high-performance financial engineering.*
