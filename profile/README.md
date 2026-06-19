<div align="center">

# XOps Labs

**Open-source systems for AI-native operations, observability, automation, security, and cost governance.**

XOps Labs is a place for practical infrastructure: tools that help teams run modern software and AI workloads with clearer signals, safer defaults, and less operational guesswork.

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/xops-labs)
[![Status](https://img.shields.io/badge/Status-active%20lab-brightgreen.svg)](https://github.com/xops-labs)
[![Open Source](https://img.shields.io/badge/Open%20Source-by%20default-111827.svg)](https://github.com/xops-labs)
[![Platform Engineering](https://img.shields.io/badge/Platform%20Engineering-tooling%20first-2563EB.svg)](https://github.com/xops-labs)
[![Observability](https://img.shields.io/badge/Observability-signals%20over%20guesswork-0F766E.svg)](https://github.com/xops-labs)
[![DevSecOps](https://img.shields.io/badge/DevSecOps-secure%20operations-7C3AED.svg)](https://github.com/xops-labs)
[![AI FinOps](https://img.shields.io/badge/AI%20FinOps-cost%20aware-5B2C6F.svg)](https://github.com/xops-labs)
[![LLMOps](https://img.shields.io/badge/LLMOps-production%20ready-7B2D8E.svg)](https://github.com/xops-labs)

[![.NET](https://img.shields.io/badge/.NET-ready-512BD4?logo=dotnet&logoColor=white)](https://github.com/xops-labs)
[![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-services-512BD4?logo=dotnet&logoColor=white)](https://github.com/xops-labs)
[![Prometheus](https://img.shields.io/badge/Prometheus-metrics-E6522C?logo=prometheus&logoColor=white)](https://github.com/xops-labs)
[![Grafana](https://img.shields.io/badge/Grafana-dashboards-F46800?logo=grafana&logoColor=white)](https://github.com/xops-labs)
[![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-traces%20%7C%20metrics-425CC7?logo=opentelemetry&logoColor=white)](https://github.com/xops-labs)
[![OpenMetrics](https://img.shields.io/badge/OpenMetrics-compatible-E6522C.svg)](https://github.com/xops-labs)
[![Docker](https://img.shields.io/badge/Docker-container%20first-2496ED?logo=docker&logoColor=white)](https://github.com/xops-labs)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-cloud--native-326CE5?logo=kubernetes&logoColor=white)](https://github.com/xops-labs)
[![CI](https://img.shields.io/badge/CI-automated%20quality-111827.svg)](https://github.com/xops-labs)
[![CodeQL](https://img.shields.io/badge/CodeQL-security%20analysis-1F6FEB.svg)](https://github.com/xops-labs)

[![FOCUS Spec](https://img.shields.io/badge/FOCUS%20Spec-cost%20data-2E75B6.svg)](https://github.com/xops-labs)
[![Multi-Cloud](https://img.shields.io/badge/Multi--Cloud-AWS%20%7C%20Azure%20%7C%20GCP-4285F4.svg)](https://github.com/xops-labs)
[![Cloud-Native](https://img.shields.io/badge/Cloud--Native-platform%20ready-326CE5.svg)](https://github.com/xops-labs)
[![Zero Vendor Lock-in](https://img.shields.io/badge/Zero%20Vendor%20Lock--in-self--hosted-1F2937.svg)](https://github.com/xops-labs)
[![Low Cardinality](https://img.shields.io/badge/Low%20Cardinality-operable%20metrics-059669.svg)](https://github.com/xops-labs)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/xops-labs)

</div>

---

```mermaid
flowchart LR
    Build["Build"] --> Observe["Observe"]
    Observe --> Govern["Govern"]
    Govern --> Automate["Automate"]
    Automate --> Secure["Secure"]
    Secure --> Improve["Improve"]
    Improve --> Build
```

## What XOps Labs Works On

XOps Labs is not a single-project org. It is an open-source lab for tools that sit close to production operations: the layer where platform engineering, observability, security, FinOps, and AI systems all start to overlap.

| Workstream | Direction |
|---|---|
| AI-native operations | LLMOps, model usage visibility, provider telemetry, agent-aware infrastructure |
| Observability | Prometheus metrics, Grafana dashboards, OpenTelemetry, health signals, alert-ready data |
| FinOps and governance | Cost attribution, budget signals, FOCUS-style records, showback and chargeback workflows |
| Platform automation | Kubernetes, containers, CI/CD, release workflows, deployment scaffolding, day-2 operations |
| Security operations | Least privilege, secret-safe patterns, CodeQL, supply-chain metadata, secure defaults |
| Developer experience | Practical docs, local-first demos, repeatable examples, boringly useful tooling |

## Current Public Work

### [llm-usage-exporter](https://github.com/xops-labs/llm-usage-exporter)

A self-hosted Prometheus and OpenTelemetry exporter for LLM usage, token volume, request counts, prompt caching, and cost telemetry across major AI providers.

It shows the XOps Labs observability pattern: make invisible AI usage signals visible, keep telemetry self-hosted, and give teams data they can actually act on.

### [relixq-oss](https://github.com/xops-labs/relixq-oss)

An open-source Post-Quantum Cryptography scanner that inventories quantum-vulnerable cryptography across source code, dependencies, TLS endpoints, certificates, and configs.

Relix-Q scores risk, grades crypto-agility, exports SARIF for CI gating, and keeps scans self-hosted so code stays on the operator's machine.

These projects follow the same pattern: focused tools, open standards, production-minded defaults, and clear docs.

## Operating Principles

- Open source by default
- Self-hosted before SaaS-dependent
- Open standards over proprietary lock-in
- Low-cardinality, production-safe telemetry
- Security and cost treated as operational concerns, not afterthoughts
- Tools should be easy to run locally and credible in production

## Get Involved

Bring issues, ideas, provider integrations, dashboards, examples, docs, tests, and real-world operational feedback. XOps Labs is built around practical tools that become sharper when operators use them.

Explore the repositories: [github.com/xops-labs](https://github.com/xops-labs)
