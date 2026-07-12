## Hi there 👋

I'm a **Principal SRE and Platform Engineer** at Oracle Health, building cloud-native infrastructure and operational tooling in Go for FedRAMP-regulated healthcare workloads.

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![OCI](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat&logo=oracle&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat&logo=istio&logoColor=white)

## What I build

- **Platform tooling** — Go CLIs, automation frameworks, and internal developer platforms that eliminate toil and give teams self-service capabilities
- **Observability** — OpenTelemetry pipelines, Prometheus, distributed tracing, and SLI/SLO instrumentation across multi-cluster Kubernetes (OKE)
- **Infrastructure automation** — Terraform, OCI Functions, External Secrets + OCI Vault, event-driven provisioning, and zero-touch deployment
- **Service mesh & security** — Istio traffic management, mTLS, and hardened Kubernetes clusters (CKS)
- **Reliability at scale** — Incident response, runbooks, and large-scale database migrations (MySQL → HeatWave, Redis → OCI Cache/Valkey) across 100+ services

## Current focus

Standardizing observability and platform patterns across a fleet of 100+ services on OCI (FedRAMP OC2) — OpenTelemetry, Prometheus, OKE, Go, and whatever removes the next piece of manual toil.

Also exploring **MLOps and applied GenAI** — RAG architecture, grounded-answer contracts, model evaluation, and treating LLM accuracy as a testable, regression-gated concern rather than a vibe.

## 📌 Featured

**[ocloud](https://github.com/cnopslabs/ocloud)** — my open-source Go CLI for OCI operations, adopted as the org-standard operational tool and used daily across my team.

**[OpenLex](https://github.com/rozdolsky33/OpenLex)** — a POC retrieval-augmented legal research assistant (NY landlord-tenant law) I built to learn MLOps by running an LLM system the way I'd run any production service. Hybrid retrieval (pgvector + Postgres FTS), grounded citations that answer *only* from retrieved statute, and — the part I care about most — a **CI-gated legal-accuracy evaluation harness**: 21 golden questions with known-correct citations fired against a live stack, run on cheap Haiku in CI and the production Sonnet model on demand, with a [**live evaluation report**](https://rozdolsky33.github.io/OpenLex/) publishing per-question pass/fail, Haiku-vs-Sonnet divergence, and statute-freshness drift. Applying SRE regression-gating and cost-awareness to GenAI, not just wiring up a demo.

## 🎓 Certifications

<p align="left">
  <img src="https://img.shields.io/badge/CKS-Kubernetes_Security_Specialist-326CE5?style=flat&logo=kubernetes&logoColor=white" alt="CKS"/>
  <img src="https://img.shields.io/badge/CKA-Kubernetes_Administrator-326CE5?style=flat&logo=kubernetes&logoColor=white" alt="CKA"/>
  <img src="https://img.shields.io/badge/ICA-Istio_Certified_Associate-466BB0?style=flat&logo=istio&logoColor=white" alt="ICA"/>
  <img src="https://img.shields.io/badge/PCA-Prometheus_Certified_Associate-E6522C?style=flat&logo=prometheus&logoColor=white" alt="PCA"/>
  <img src="https://img.shields.io/badge/OTCA-OpenTelemetry_Certified-425CC7?style=flat&logo=opentelemetry&logoColor=white" alt="OTCA"/>
  <img src="https://img.shields.io/badge/OCI-DevOps_Professional-F80000?style=flat&logo=oracle&logoColor=white" alt="OCI DevOps Pro"/>
  <img src="https://img.shields.io/badge/GCP-Professional_Data_Engineer-4285F4?style=flat&logo=googlecloud&logoColor=white" alt="GCP PDE"/>
</p>

---

*Also: SRE mentor, and a former musician who now finds rhythm in reliable systems.* 🎼
