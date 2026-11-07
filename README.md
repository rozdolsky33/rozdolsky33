## Hi there 👋

I'm a **Principal SRE and Platform Engineer**. I build cloud-native infrastructure and developer tooling, mostly in Go, for environments where reliability, security, and compliance actually matter.

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat&logo=istio&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat&logo=argo&logoColor=white)

## What I care about

- **Tooling that removes toil**: Go CLIs and automation that give teams self-service instead of tickets
- **Observability**: OpenTelemetry, Prometheus, distributed tracing, and SLIs/SLOs that tell you something true
- **Infrastructure as code and GitOps**: Terraform, event-driven provisioning, and Argo CD-style GitOps (Git as the source of truth, progressive delivery with Argo Rollouts) so deployments need no hands
- **Security by default**: service mesh, mTLS, hardened Kubernetes, and secrets handled properly
- **Reliability**: incident response, runbooks, and migrations done without drama

## Currently

- Standardizing observability and platform patterns across large fleets of services
- Exploring **MLOps and applied GenAI**: RAG design, grounded answers, and treating LLM accuracy as a testable, regression-gated concern rather than a vibe
- Building guardrails for AI coding agents: keeping sensitive data out of prompts without breaking the workflow

## 📌 Featured

**[ocloud](https://github.com/cnopslabs/ocloud)**: an open-source Go CLI for Oracle Cloud Infrastructure operations that I use daily.

**[cui-proxy](https://github.com/rozdolsky33/cui-proxy)**: a fail-closed local proxy that masks sensitive data (IPs, resource IDs, credentials, your own dictionary) in AI coding-agent traffic with realistic synthetic values, then restores them in responses. It has a strict block-by-default policy profile, a live dashboard, and a macOS menu-bar app. Install with `brew install rozdolsky33/tap/cui-proxy`.

**[OpenLex](https://github.com/rozdolsky33/OpenLex)**: a proof-of-concept retrieval-augmented legal research assistant (NY landlord-tenant law), built to learn MLOps by running an LLM system like any production service. Hybrid retrieval (pgvector + Postgres FTS), citations that answer *only* from retrieved statute, and a **CI-gated accuracy harness**: 21 golden questions with known-correct citations, run on Haiku in CI and Sonnet on demand, with a [**live evaluation report**](https://rozdolsky33.github.io/OpenLex/) showing per-question pass/fail and model divergence. SRE regression-gating and cost-awareness applied to GenAI.

## 🎓 Certifications

<p align="left">
  <img src="https://img.shields.io/badge/CKS-Kubernetes_Security_Specialist-326CE5?style=flat&logo=kubernetes&logoColor=white" alt="CKS"/>
  <img src="https://img.shields.io/badge/CKA-Kubernetes_Administrator-326CE5?style=flat&logo=kubernetes&logoColor=white" alt="CKA"/>
  <img src="https://img.shields.io/badge/ICA-Istio_Certified_Associate-466BB0?style=flat&logo=istio&logoColor=white" alt="ICA"/>
  <img src="https://img.shields.io/badge/PCA-Prometheus_Certified_Associate-E6522C?style=flat&logo=prometheus&logoColor=white" alt="PCA"/>
  <img src="https://img.shields.io/badge/OTCA-OpenTelemetry_Certified-425CC7?style=flat&logo=opentelemetry&logoColor=white" alt="OTCA"/>
  <a href="https://www.credly.com/earner/earned/badge/2115fa68-a402-47d5-8773-a3cbed4dd5de"><img src="https://img.shields.io/badge/CAPA-Certified_Argo_Project_Associate-EF7B4D?style=flat&logo=argo&logoColor=white" alt="CAPA"/></a>
  <img src="https://img.shields.io/badge/OCI-DevOps_Professional-F80000?style=flat&logo=oracle&logoColor=white" alt="OCI DevOps Pro"/>
  <img src="https://img.shields.io/badge/GCP-Professional_Data_Engineer-4285F4?style=flat&logo=googlecloud&logoColor=white" alt="GCP PDE"/>
</p>

---

*Also: SRE mentor, and a former musician who now finds rhythm in reliable systems.* 🎼
