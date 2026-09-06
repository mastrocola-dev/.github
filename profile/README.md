# mastrocola.dev

> Event-driven systems, done right. A living portfolio built as a real company.

**[mastrocola.dev](https://mastrocola.dev)** is a software engineering organization built from scratch to demonstrate — in public — how to design, build, and operate mission-critical backend platforms. Every architectural decision is documented, every service is production-grade, and everything runs on real cloud infrastructure.

Created and maintained by [Marcio Mastrocola Alcantara](https://www.linkedin.com/in/marcio-mastrocola) — Software Architect & Tech Lead specialized in modernizing legacy systems, event-driven architectures, and data engineering for fintech.

## Why this exists

Most portfolios are a pile of tutorial clones. This one is structured like an actual company:

- **Multi-repo architecture** with clear domain boundaries
- **Infrastructure as Code** provisioning real Azure resources via OIDC-authenticated pipelines
- **Documented decisions** — every significant choice has an ADR explaining the trade-offs
- **Production practices** — CI/CD, observability, and automated testing from day one

Even the landing page follows the rules: [mastrocola.dev](https://mastrocola.dev) is served by Azure Static Web Apps declared in Terraform, with its DNS zone managed as code and deployed by its own pipeline — the site is itself a working sample of the platform.

The goal is twofold: showcase architectural competence, and keep the door open for this to become a real product company.

## Repositories

| Repository | Description | Status |
|---|---|---|
| [docs](https://github.com/mastrocola-dev/docs) | Architecture documentation, ADRs, runbooks | 🟢 Active |
| [infra](https://github.com/mastrocola-dev/infra) | Azure infrastructure as code (Terraform) | 🟢 Active |
| [www](https://github.com/mastrocola-dev/www) | Public site content, deployed to the edge on every push | 🟢 Active |
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
- [x] Documentation baseline: ADRs and operational runbooks (`docs`)
- [x] Public site live at [mastrocola.dev](https://mastrocola.dev) — hosting, DNS and deploys fully as code
- [ ] Landing page content and design
- [ ] C4 architecture diagrams (`docs`)
- [ ] `template-service` with golden-path CI/CD
- [ ] First domain service end-to-end (API → event bus → persistence)
- [ ] Observability wired to all services

## Get in touch

Open to architecture opportunities — and to conversations about this project.

📫 [marcio@mastrocola.dev](mailto:marcio@mastrocola.dev) · [LinkedIn](https://www.linkedin.com/in/marcio-mastrocola) · [GitHub](https://github.com/mastrocola-dev)