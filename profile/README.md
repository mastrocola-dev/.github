# mastrocola.dev

> Event-driven systems, done right. A living portfolio built as a real company.

**mastrocola.dev** is a software engineering organization built from scratch to demonstrate — in public — how to design, build, and operate mission-critical backend platforms. Every architectural decision is documented, every service is production-grade, and everything runs on real cloud infrastructure.

Created and maintained by [Marcio Mastrocola Alcantara](https://www.linkedin.com/in/marciomastrocola) — Software Architect & Tech Lead specialized in modernizing legacy systems, event-driven architectures, and data engineering for fintech.

## Why this exists

Most portfolios are a pile of tutorial clones. This one is structured like an actual company:

- **Multi-repo architecture** with clear domain boundaries
- **Infrastructure as Code** provisioning real Azure resources via OIDC-authenticated pipelines
- **Documented decisions** — every significant choice has an ADR explaining the trade-offs
- **Production practices** — CI/CD, observability, and automated testing from day one

The goal is twofold: showcase architectural competence, and keep the door open for this to become a real product company.

## Repositories

| Repository | Description | Status |
|---|---|---|
| [docs](https://github.com/mastrocola-dev/docs) | Architecture documentation, ADRs, runbooks | 🟢 Active |
| [infra](https://github.com/mastrocola-dev/infra) | Azure infrastructure as code (Terraform) | 🟢 Active |
| `template-service` | Golden-path microservice template | ⚪ Planned |
| `service-*` | Domain services — created as the platform grows | ⚪ Planned |

## Tech stack

**Backend:** Node.js (TypeScript), Python
**Architecture:** Event-driven microservices
**Cloud:** Microsoft Azure, Terraform, GitHub Actions with OIDC federation
**Data & messaging:** SQL Server, PostgreSQL, MongoDB, RabbitMQ, Apache Airflow
**Observability:** Grafana, Elasticsearch/Kibana

## Roadmap

- [x] Base infrastructure on Azure (`infra`)
- [x] Multi-repo structure with organization-wide OIDC authentication
- [ ] Documentation baseline: ADR-001, C4 diagrams (`docs`)
- [ ] `template-service` with golden-path CI/CD
- [ ] First domain service end-to-end (API → event bus → persistence)
- [ ] Observability wired to all services

## Get in touch

Open to architecture opportunities — and to conversations about this project.

📫 [mastrocola@gmail.com](mailto:mastrocola@gmail.com) · [LinkedIn](https://www.linkedin.com/in/marciomastrocola) · [GitHub](https://github.com/mastrocola)