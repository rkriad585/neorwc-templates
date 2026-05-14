# neorwc-templates

![Logo](https://github.com/rkriad585/neorwc-cli/blob/main/logo/logo.svg)

Persona skill templates for [neorwc-cli](https://github.com/rkriad585/neorwc-cli) — an AI-powered documentation generator. These `.md` skill files define AI personas that control tone, focus, and output style when generating project documentation.

## Usage

```bash
neorwc --skill <skill-name>
```

Skills are installed to `~/.config/neostore/neorwc/skills/`. Use `neorwc --init` to initialize the folder, then copy skill files from this repository.

## Skill Categories

### Core Personas (20)

| Skill | Purpose |
|-------|---------|
| `architect` | System architecture and design documentation |
| `senior-architect` | Distributed systems and architectural decisions |
| `code-reviewer` | Rigorous code review with actionable feedback |
| `technical-writer` | Clear, structured technical documentation |
| `developer-advocate` | Developer experience and onboarding guides |
| `devrel` | Community-focused documentation and adoption |
| `educator` | Step-by-step coding tutorials and instruction |
| `w3-teacher` | Beginner-friendly W3Schools-style tutorials |
| `product-manager` | Feature documentation and user stories |
| `qa-engineer` | Test plans, scenarios, and coverage analysis |
| `security-auditor` | Security audit, threat analysis, and compliance |
| `devops-engineer` | CI/CD, containerization, and infrastructure docs |
| `cli-expert` | Command-line tool documentation and UX |
| `pythonista` | Python package creation and PyPI publishing |
| `js-ninja` | Node.js module creation and npm publishing |
| `maintainer` | Open source maintenance and contribution guides |
| `sysadmin` | Linux system administration and package docs |
| `unix-guru` | MAN-page style technical reference |
| `minimalist` | Ultra-concise, no-fluff documentation |
| `legal-counsel` | Licensing, IP, and open source governance |

### Architecture & Design Patterns (5)

| Skill | Purpose |
|-------|---------|
| `microservices-architect` | Service decomposition and inter-service communication |
| `event-driven-architect` | Event schemas, producers, consumers, and streaming |
| `design-system-documenter` | Design tokens, component libraries, and theming |
| `error-handling-specialist` | Error taxonomy, retry strategies, and circuit breakers |
| `chaos-engineering-specialist` | Fault injection experiments and resilience validation |

### Framework & Platform (13)

| Skill | Purpose |
|-------|---------|
| `frontend-developer` | UI framework and component documentation |
| `backend-developer` | Server-side API and service documentation |
| `mobile-developer` | iOS, Android, and cross-platform app docs |
| `api-documenter` | REST and GraphQL API reference documentation |
| `graphql-specialist` | GraphQL schema, queries, and resolver docs |
| `openapi-specialist` | OpenAPI/Swagger specification and codegen |
| `grpc-specialist` | gRPC services, protobuf, and streaming |
| `docker-specialist` | Dockerfile, Compose, and container docs |
| `kubernetes-specialist` | K8s manifests, Helm, networking, and operations |
| `helm-chart-specialist` | Helm chart structure, values, and lifecycle |
| `serverless-specialist` | FaaS, event sources, and serverless patterns |
| `terraform-specialist` | Terraform modules, state, and IaC workflows |
| `database-specialist` | SQL/NoSQL schema and query documentation |

### API & Integration (6)

| Skill | Purpose |
|-------|---------|
| `api-gateway-specialist` | Gateway routing, rate limiting, and auth aggregation |
| `api-versioning-specialist` | Versioning schemes, deprecation, and migration |
| `message-queue-specialist` | Kafka, RabbitMQ, SQS/SNS, and Pub/Sub |
| `oauth2-specialist` | OAuth2, OpenID Connect, and SSO integration |
| `webhook-specialist` | Webhook events, payloads, and delivery |
| `sbom-specialist` | SBOM generation, supply chain, and vulnerability management |

### CI/CD & Deployment (5)

| Skill | Purpose |
|-------|---------|
| `ci-cd-specialist` | Pipeline configuration and automation docs |
| `deployment-specialist` | Release, deploy, and rollback procedures |
| `build-system-specialist` | Build tools and compilation pipeline docs |
| `release-manager` | Release coordination, versioning, and approval gates |
| `load-testing-specialist` | Stress, soak, spike testing with k6, JMeter, Locust |

### Quality & Testing (7)

| Skill | Purpose |
|-------|---------|
| `testing-strategist` | Test pyramid, coverage goals, and quality gates |
| `integration-tester` | E2E, contract, and service-level testing docs |
| `api-testing-specialist` | Contract testing, collections, and API monitoring |
| `static-analysis-specialist` | Linters, SAST, code quality gates |
| `code-coverage-specialist` | Coverage metrics, thresholds, and reporting |
| `accessibility-specialist` | WCAG compliance and inclusive design docs |
| `performance-engineer` | Benchmarking and optimization documentation |

### Development Workflow (9)

| Skill | Purpose |
|-------|---------|
| `readme-specialist` | Compelling project README creation |
| `changelog-writer` | Release notes and changelog documentation |
| `contributing-guide-writer` | Open source contribution guidelines |
| `migration-guide-writer` | Version migration and upgrade guides |
| `troubleshooting-specialist` | Error resolution and FAQ documentation |
| `git-workflow-specialist` | Branching strategy and commit conventions |
| `dependency-manager` | Package management, lock files, and vulnerability scanning |
| `localization-specialist` | i18n, translations, RTL support, and locale files |
| `code-generator` | Scaffolding and code generation docs |

### Infrastructure & Operations (12)

| Skill | Purpose |
|-------|---------|
| `monitoring-specialist` | Metrics, dashboards, and alerting docs |
| `logging-specialist` | Structured logging and log analysis docs |
| `sre-specialist` | SLOs, error budgets, and incident management |
| `incident-response-specialist` | Severity matrix, on-call, runbooks, postmortems |
| `service-mesh-specialist` | Istio, Linkerd, mTLS, and traffic policies |
| `proxy-specialist` | Nginx, Caddy, Traefik reverse proxy configuration |
| `caching-specialist` | Multi-layer caching strategy documentation |
| `backup-specialist` | Backup, restore, and disaster recovery docs |
| `secret-management-specialist` | Vault, secrets rotation, and encryption |
| `config-manager` | Configuration and environment variable management |
| `scheduled-task-specialist` | Cron, Airflow, batch processing, and job scheduling |
| `data-migration-specialist` | ETL pipelines, schema migration, and data validation |

### Compliance & Governance (2)

| Skill | Purpose |
|-------|---------|
| `compliance-documenter` | Regulatory compliance (SOC 2, GDPR, HIPAA) docs |
| `documentation-strategist` | Information architecture and doc planning |

### Environment & Setup (1)

| Skill | Purpose |
|-------|---------|
| `environment-specialist` | Development environment setup guides |

### NeoRWC-Specific (4)

| Skill | Purpose |
|-------|---------|
| `neorwc-cli` | CLI tool documentation for neorwc |
| `neorwc-config` | Configuration and provider setup guides |
| `neorwc-workflow` | Scan-Analyze-Write documentation workflow |
| `neorwc-template-creator` | Creating custom persona skill templates |

## License

ISC
