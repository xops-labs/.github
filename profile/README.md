<div align="center">

# XOps Labs

**Open-source infrastructure for AI-native reliability, observability, cost governance, and secure operations.**

We build small, sharp, self-hosted tools that help platform teams see, govern, and operate AI systems with the same confidence they expect from the rest of their cloud-native stack.

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/xops-labs/llm-usage-exporter/blob/main/LICENSE)
[![Status](https://img.shields.io/badge/Status-active%20development-brightgreen.svg)](https://github.com/xops-labs/llm-usage-exporter)
[![.NET](https://img.shields.io/badge/.NET-10.0-512BD4?logo=dotnet&logoColor=white)](https://github.com/xops-labs/llm-usage-exporter)
[![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-10-512BD4?logo=dotnet&logoColor=white)](https://github.com/xops-labs/llm-usage-exporter)
[![Prometheus](https://img.shields.io/badge/Prometheus-native-E6522C?logo=prometheus&logoColor=white)](https://github.com/xops-labs/llm-usage-exporter)
[![Grafana](https://img.shields.io/badge/Grafana-dashboards-F46800?logo=grafana&logoColor=white)](https://github.com/xops-labs/llm-usage-exporter/tree/main/dashboards)
[![Docker](https://img.shields.io/badge/Docker-ready-2496ED?logo=docker&logoColor=white)](https://github.com/xops-labs/llm-usage-exporter/tree/main/deploy)
[![CI](https://github.com/xops-labs/llm-usage-exporter/actions/workflows/ci.yml/badge.svg)](https://github.com/xops-labs/llm-usage-exporter/actions/workflows/ci.yml)
[![CodeQL](https://github.com/xops-labs/llm-usage-exporter/actions/workflows/codeql.yml/badge.svg)](https://github.com/xops-labs/llm-usage-exporter/actions/workflows/codeql.yml)

[![LLMOps](https://img.shields.io/badge/LLMOps-ready-7B2D8E)](https://github.com/xops-labs/llm-usage-exporter)
[![AI FinOps](https://img.shields.io/badge/AI%20FinOps-cost%20signals-5B2C6F)](https://github.com/xops-labs/llm-usage-exporter)
[![FOCUS Spec](https://img.shields.io/badge/FOCUS%20Spec-v1.0%20active-2E75B6)](https://github.com/xops-labs/llm-usage-exporter)
[![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-OTLP%20active-425CC7?logo=opentelemetry&logoColor=white)](https://github.com/xops-labs/llm-usage-exporter)
[![OpenMetrics](https://img.shields.io/badge/OpenMetrics-v1.0.0-E6522C)](https://github.com/xops-labs/llm-usage-exporter)
[![Providers](https://img.shields.io/badge/Providers-OpenAI%20%7C%20Azure%20%7C%20Anthropic%20%7C%20Gemini%20%7C%20Bedrock-FF6B35)](https://github.com/xops-labs/llm-usage-exporter)
[![Multi-Cloud](https://img.shields.io/badge/Multi--Cloud-AWS%20%7C%20Azure%20%7C%20GCP-4285F4)](https://github.com/xops-labs/llm-usage-exporter)
[![Cloud-Native](https://img.shields.io/badge/Cloud--Native-container%20first-326CE5?logo=kubernetes&logoColor=white)](https://github.com/xops-labs/llm-usage-exporter)
[![Zero Vendor Lock-in](https://img.shields.io/badge/Zero%20Vendor%20Lock--in-self--hosted-1F2937)](https://github.com/xops-labs/llm-usage-exporter)
[![Low Cardinality](https://img.shields.io/badge/Low%20Cardinality-Prometheus--safe-059669)](https://github.com/xops-labs/llm-usage-exporter)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/xops-labs/llm-usage-exporter/blob/main/CONTRIBUTING.md)

</div>

---

```mermaid
flowchart LR
    Workloads["AI workloads"] --> Signals["Usage, tokens, requests, spend"]
    Signals --> Exporters["Prometheus, OTLP, FOCUS"]
    Exporters --> Ops["Grafana, Alertmanager, FinOps"]
    Ops --> Teams["Platform, SRE, Finance, Product"]
```

## What We Build

XOps Labs focuses on tools that make AI systems easier to operate in production:

| Area | What we care about |
|---|---|
| Observability | Metrics, dashboards, alerts, health signals, and operational feedback loops |
| AI FinOps | Cost visibility, showback, budget burn, provider spend, and model-level attribution |
| Platform operations | Kubernetes-ready, automation-friendly, self-hosted building blocks |
| Security and governance | Minimal permissions, inspectable code, open standards, and vendor-neutral workflows |

## Featured Project

### [llm-usage-exporter](https://github.com/xops-labs/llm-usage-exporter)

A self-hosted Prometheus exporter for LLM usage, token consumption, request volume, prompt caching, and USD cost telemetry across OpenAI, Azure OpenAI, Anthropic Claude, Google Gemini, and AWS Bedrock.

It gives platform, SRE, FinOps, and engineering teams a near-real-time AI cost signal inside Prometheus, Grafana, OpenTelemetry, Alertmanager, and FOCUS-compatible cost workflows.

## Operating Principles

- Open source by default
- Self-hosted and vendor-neutral
- Low-cardinality telemetry that can survive real Prometheus deployments
- OpenTelemetry and OpenMetrics friendly
- Built for cloud-native teams running Kubernetes, containers, and CI/CD
- Cost, reliability, and governance treated as the same operational problem

## Contributing

We welcome practical, production-minded contributions: provider integrations, dashboards, deployment examples, bug reports, docs, tests, and hard-earned operational feedback from real AI platforms.

Start here: [llm-usage-exporter contribution guide](https://github.com/xops-labs/llm-usage-exporter/blob/main/CONTRIBUTING.md)