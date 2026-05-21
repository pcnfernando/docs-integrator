---
title: Deploy Overview
description: Learn about the different deployment options for your WSO2 Integrator projects and how to choose the right one for your needs.
keywords: [wso2 integrator, deployment, wso2 cloud, docker, kubernetes, vm-based deployment, integration control plane]
---
{/* TODO: Work in progress */}

# Deploy and Operate

Once your integration is ready, this section covers everything you need to ship it, keep it running, and operate it in production.

## Deployment options

WSO2 Integrator supports multiple deployment targets. Choose the one that fits your infrastructure:

- **[WSO2 Cloud](./cloud/overview.md)** — Push your project directly from the IDE or the cloud editor to the managed WSO2 Integration Platform. No infrastructure setup required.
- **[Run locally](./self-hosted/run-locally.md)** — Run your integration on your local machine for development or testing.
- **[VM-based deployment](../deploy-operate/deploy/vm-based-deployment.md)** — Deploy to a virtual machine or bare-metal server.
- **[Docker](./self-hosted/docker.md)** and **[Kubernetes](./self-hosted/kubernetes.md)** — Package your integration as a container and deploy it to a Kubernetes cluster.
- **Red Hat OpenShift** — Deploy on OpenShift using standard Kubernetes tooling.
- **Serverless deployment** — Run integrations as serverless functions.
- **AWS, Azure, and GCP** — Deploy to major cloud providers using native services.
- **GraalVM native images** — Compile your integration to a native binary for faster startup and lower memory usage.

## Configuration and scaling

- **Environments** — Manage dev, staging, and production environment configurations.
- **[Managing configurations](../deploy-operate/deploy/managing-configurations.md)** — Externalize and manage runtime configuration values.
- **Scaling and high availability** — Design your deployment for resilience and scale.
- **Capacity planning** — Estimate resource requirements and plan deployment sizing.

## CI/CD

Automate your deployment pipeline using your preferred CI/CD platform:

- GitHub Actions
- Jenkins
- GitLab
- Azure DevOps

## Observability

Monitor your integrations in production with logs, metrics, and traces:

- **Observability overview** — Understand the observability model.
- **Logging overview** — Capture and query structured log output.
- **Metrics overview** — Emit application-level metrics.
- **[Prometheus and Grafana](../deploy-operate/observe/metrics-prometheus-grafana.md)** — Scrape metrics and build dashboards.
- **Jaeger** and **Zipkin** tracing — Distributed request tracing.
- **[Datadog](../deploy-operate/observe/datadog-integration.md)**, **New Relic**, **[Elastic Stack (ELK)](../deploy-operate/observe/elastic-stack-elk.md)**, **[OpenSearch](../deploy-operate/observe/opensearch-integration.md)**, **Moesif** — Third-party observability platforms.

## Security

Protect your integrations and the data they process:

- **Runtime security** — Harden the runtime environment.
- **Authentication** — Secure service endpoints.
- **API security and rate limiting** — Enforce access policies.
- **Secrets and encryption** — Manage sensitive credentials safely.
- **Compliance considerations** — Meet regulatory and audit requirements.
