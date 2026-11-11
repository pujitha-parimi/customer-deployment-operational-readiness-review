
# Customer Deployment & Operational Readiness Review

This repository contains a deployment review for a Multi-Agent AI Customer Support System.

## Project Overview

The review covers how an AI customer support application can be operated in a customer-controlled environment.

## Topics Covered

- Proposed deployment architecture
- Security and IAM design
- Secrets management
- Monitoring and observability
- Operational readiness and troubleshooting
- Knowledge transfer
- Reusable assets
- Deployment limitations

## Technology Stack

- Python
- FastAPI
- Google Gemini API
- HashiCorp Vault (proposed secrets-management option)
- Prometheus and Grafana (proposed monitoring tools)

## Documentation

The main assessment document is available here:

[Deployment Review](docs/deployment-review.md)

## Deployment Status

Docker installation could not be completed on my Windows system because of Windows error 14098 (component store corruption). Therefore, a working Docker-based deployment has not been demonstrated.

The repository documents the proposed deployment approach and this limitation transparently.
