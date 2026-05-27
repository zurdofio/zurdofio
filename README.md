# Martin Ferreyra

**Telecom & Devops engineer from Cordoba, Argentina**

</div>

---

Telecom and devops engineer running [Wilab](https://wilab.io) — I design and operate Kubernetes platforms, build observability stacks, and ship data products for telecom and enterprise clients. Infrastructure-first mindset applied to everything from multi-cluster GitOps deployments to AI-powered analytics backends.

## What I'm building

### [Pulse Agent](https://wilab.io) — MCP-native data agent

The main product at Wilab. A conversational analyst wired to your warehouse through MCP — it reads the schema, writes the SQL, renders the chart, and hands you a narrative you can forward to your team. Connects to Postgres, Snowflake, BigQuery, or ClickHouse. Includes an SQL Studio for promoting queries to production, context engineering for skill/memory orchestration, and automation workflows that fan out to Slack, Linear, or your own APIs.

### Under the hood

- **Multi-cluster Kubernetes platform** — GitOps-managed with ArgoCD across GKE and on-prem clusters. Full observability with Grafana, Prometheus, and Loki. CDC pipelines running Debezium into Kafka and RisingWave for real-time stream processing.

- **Polyglot microservices monorepo** — Nx-orchestrated workspace shipping Go backend services, Next.js frontends, and shared libraries. Hexagonal architecture with NATS messaging, Elasticsearch analytics, and LDAP/OAuth2 auth.

- **AI-powered data platform** — FastAPI + Prophet for time-series forecasting, MCP server for LLM tool integration, RisingWave stream processing, and Gemini-powered query generation with token cost tracking.

- **Reusable CI/CD toolkit** — Custom GitHub Actions for Nx monorepos with affected-project detection, multi-language builds (Node.js + Go), Docker image publishing to GHCR, and matrix-based integration testing.

- **Telecom network observability** — SNMP monitoring for carrier-grade equipment with custom Logstash pipelines and Nokia MIB libraries, 5G network analytics (NWDAF), and real-time alerting.

## Tech stack

### Infrastructure & Orchestration
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

### CI/CD
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Nx](https://img.shields.io/badge/Nx-143055?style=for-the-badge&logo=nx&logoColor=white)

### Observability
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F2C811?style=for-the-badge&logo=grafana&logoColor=black)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Jaeger](https://img.shields.io/badge/Jaeger-66CFE3?style=for-the-badge&logo=jaeger&logoColor=black)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)

### Data & Streaming
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![NATS](https://img.shields.io/badge/NATS-27AAE1?style=for-the-badge&logo=natsdotio&logoColor=white)
![RisingWave](https://img.shields.io/badge/RisingWave-6236FF?style=for-the-badge&logoColor=white)
![Debezium](https://img.shields.io/badge/Debezium-FF6600?style=for-the-badge&logoColor=white)

### AI & LLM Infrastructure
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_Server-4A154B?style=for-the-badge&logoColor=white)
![Vercel AI SDK](https://img.shields.io/badge/AI_SDK-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Langflow](https://img.shields.io/badge/Langflow-FF6E42?style=for-the-badge&logoColor=white)

### Networking & Security
![NGINX](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Envoy](https://img.shields.io/badge/Envoy_Gateway-AC6199?style=for-the-badge&logo=envoyproxy&logoColor=white)
![cert-manager](https://img.shields.io/badge/cert--manager-003A70?style=for-the-badge&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white)

### Backend
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

## GitHub stats

<div align="center">

<img src="https://github-readme-stats-sigma-five.vercel.app/api?username=zurdofio&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="170" />

[![GitHub Streak](https://streak-stats.demolab.com?user=zurdofio&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

[![trophy](https://github-profile-trophy-rust.vercel.app/?username=zurdofio&theme=darkhub&no-frame=true&row=1&column=6)](https://github.com/ryo-ma/github-profile-trophy)

</div>

## Let's connect

[![Website](https://img.shields.io/badge/wilab.io-6C63FF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://wilab.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/martinferreyra)
