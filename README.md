# Nuno Salvação – AI Solutions Architect
*AI Solutions Architect · Designing Idempotent, Secure & Observable Systems · Multi-Provider Orchestration & FinOps*

I design **AI-native systems** that balance **quality, compliance, and cost** — from prototype to **production-grade observability**.  
My focus is on **RAG pipelines**, **multi-provider orchestration**, and **GDPR-compliant architectures** across **GCP, Azure, and AWS**, built for **idempotence, zero-trust, and measurable performance**.

---

## CORE COMPETENCIES

|**Architecture Domain**|**Technologies & Methods**|
|---|---|
|**AI/ML Solutions**|Multi-LLM architectures, prompt orchestration, **RAG pipelines (LlamaIndex)**, semantic retrieval, embedding optimization|
|**LLMOps & Observability**|**Langfuse / Helicone** for tracing & metrics, **Prometheus + Grafana** dashboards, latency & cost telemetry, reproducible evals (RAGAS)|
|**Data Engineering**|**PostgreSQL + pgvector**, **Qdrant**, synthetic & masked datasets, lineage tracking, schema-aware ingestion|
|**Cloud & Infrastructure**|**GCP / AWS / Azure**, containerized runtimes (**Docker / Compose**), **IaC with Terraform + Ansible**, idempotent provisioning|
|**Security & Compliance**|**Zero-Trust perimeter (mTLS, Cloudflare Tunnel)**, IAM least-privilege design, GDPR-by-design (Art. 25/30/32), auditable retention|
|**FinOps & Optimization**|**Multi-provider orchestration (LiteLLM, ModelFusion, OpenRouter)**, rate-limiting, caching & graceful degradation, **cost-aware routing**|
|**Agent Orchestration**|**LangGraph / CrewAI patterns**, adaptive task routing, memory persistence, **autonomous multi-agent coordination**|
|**Technical Documentation**|ADRs, runbooks, **solution architecture blueprints**, compliance & funding documentation (EU / PT programs)|


---

## FEATURED PROJECTS

**🚀 NexoCLI**  
Lightweight CLI to automate developer workflows with pragmatic AI. Designed for reproducibility, short feedback loops, and minimal friction.
- **Links**: [Repo](https://github.com/nsalvacao/NexoCLI_BaseGemini) · [Docs](https://nsalvacao.github.io/NexoCLI_BaseGemini/)

**🤖 Nexo-Agents**  
Collection of 44 production-ready AI agent commands for Google AI CLI integration. Role-specific expertise with automatic context discovery.
- **Links**: [Repo](https://github.com/nsalvacao/Nexo-Agents) · [Docs](https://nsalvacao.github.io/Nexo-Agents/)

---

## FEATURED PRODUCTION EXPERIENCE

**Enterprise RAG Knowledge Platform**

- Designed and deployed **multi-stage retrieval** (BM25 + dense + rerank) with **>95% citation accuracy**, ensuring traceable and explainable results.    
- Implemented a **privacy-by-design ingestion pipeline** (GDPR Art. 25) with automated **PII masking** and audit-ready logging.    
- **PostgreSQL + pgvector self-hosted architecture**, achieving **€7.9 k cost reduction over 24 months** compared to managed DB services.    
- Integrated **RAGAS-based evaluation harnesses** for continuous model quality assurance and regression testing.    


**Multi-Provider LLM Gateway & Cost Optimization**

- Architected **LiteLLM-driven orchestration layer** with **99.9 % uptime** and **automatic failover** across Anthropic, OpenRouter, and Gemini providers.    
- Applied **caching and adaptive rate-limiting** to achieve **average cost ≈ $0.02 / 1 k tokens** while maintaining consistent latency.    
- Delivered **end-to-end observability** using **Langfuse traces**, **Prometheus metrics**, and **Grafana dashboards** linked to defined **SLOs (P50 < 3 s | P95 < 8 s)**.    
- Deployed under **GCP infrastructure** aligned with **DNSH and renewable-energy compliance (>60 %)**, ensuring sustainability within EU funding standards.

---

## CURRENT FOCUS

- Consolidating **RAG and LLMOps pipelines** with multi-stage retrieval and **rerankers**, supported by **RAGAS harnesses** and **Langfuse-based observability** for trace-level evaluation.
- Advancing **multi-provider orchestration** through **LiteLLM** and **LangGraph**, introducing adaptive caching, load balancing, and real-time cost/latency optimisation.    
- Extending **serving efficiency** via **vLLM** and **TGI backends**, exploring **INT4 quantization** and **batch inference** for scalable, low-latency deployment.    
- Formalising **IaC and FinOps blueprints** to ensure reproducibility, auditability, and governance across hybrid and multi-cloud environments.    
- Evolving **compliance engineering** with automated **DPIA tooling**, dynamic data masking, and continuous GDPR/AI Act alignment.    
- Designing **agent collaboration frameworks** that enable self-diagnosing infrastructure and context-aware orchestration across pipelines.

---

## TECHNICAL SKILLS MATRIX

| **Domain / Layer**             | **Implementation & Evidence**                                                                                                                                      |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **RAG Architecture**           | Multi-stage retrieval (BM25 + dense + rerank), **LlamaIndex**, hybrid scoring & evaluation with **RAGAS**, citation precision > 95%, context window optimization   |
| **LLM Orchestration**          | **LiteLLM** (multi-provider routing), **ModelFusion** / **OpenRouter** interoperability, 99.9 % uptime, cost ≈ $0.02 / 1 k tokens, adaptive load balancing         |
| **Agent Frameworks**           | **LangGraph** and **CrewAI** patterns, memory persistence, collaborative task routing, deterministic state machines                                                |
| **Compliance Engineering**     | **GDPR Art. 25/30/32**, DPIA templates, **privacy-by-design ingestion**, PII masking pipelines, encrypted audit logs                                               |
| **Observability & Telemetry**  | **Langfuse / Helicone** for inference tracing, **Prometheus + Grafana** dashboards, **SLO enforcement (P50/P95 latency, uptime > 99.5 %)**, A/B eval tracking      |
| **Cloud & Infrastructure**     | **GCP / AWS / Azure**, **Docker CE + Compose**, **Portainer CE**, **Cockpit**, **Terraform + Ansible**, PostgreSQL + pgvector, optional **Neo4j** knowledge graphs |
| **Automation & IaC**           | Declarative provisioning (Terraform), convergence & hardening (Ansible), idempotent rebuilds, policy-as-code validation                                            |
| **FinOps & Optimization**      | Multi-provider cost routing, rate limiting, caching, throughput forecasting, usage dashboards, per-tenant cost analytics                                           |
| **Development & Integration**  | **Python 3.x**, REST / WebSocket APIs, CLI tools, Git + GitHub Actions CI/CD, containerized development environments                                               |
| **Backup & DR**                | `pg_dump` automation, **Duplicati** incremental backups, GCP snapshots, RTO < 15 min validation scripts                                                            |
| **Data Layer & Storage**       | **PostgreSQL 16 + pgvector**, **MongoDB**, **Qdrant**, synthetic & masked datasets, lineage & versioning                                                           |
| **Documentation & Governance** | Architecture Decision Records (ADRs), runbooks, **Mermaid diagrams**, Obsidian knowledge base, EU funding deliverables alignment                                   |

---

## 🌐 LINKS & CONTACT

- Website/Portfolio → [https://en.nunosalvacao.pro/](https://en.nunosalvacao.pro/)
- LinkedIn → [https://www.linkedin.com/in/nsalvacao/](https://www.linkedin.com/in/nsalvacao/)
- Email → **[nuno.salvacao@gmail.com](mailto:nuno.salvacao@gmail.com)**

**CET (EQF Level 5, PT)**. Unavailable during internship Sep–Dec 2025 (400h); **open to opportunities thereafter**.