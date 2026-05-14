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

### Architecture & Design Patterns (4)

| Skill | Purpose |
|-------|---------|
| `microservices-architect` | Service decomposition and inter-service communication |
| `event-driven-architect` | Event schemas, producers, consumers, and streaming |
| `design-system-documenter` | Design tokens, component libraries, and theming |
| `error-handling-specialist` | Error taxonomy, retry strategies, and circuit breakers |

### Framework & Platform (12)

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
| `serverless-specialist` | FaaS, event sources, and serverless patterns |
| `terraform-specialist` | Terraform modules, state, and IaC workflows |
| `database-specialist` | SQL/NoSQL schema and query documentation |

### API & Integration (4)

| Skill | Purpose |
|-------|---------|
| `message-queue-specialist` | Kafka, RabbitMQ, SQS/SNS, and Pub/Sub |
| `oauth2-specialist` | OAuth2, OpenID Connect, and SSO integration |
| `webhook-specialist` | Webhook events, payloads, and delivery |
| `api-gateway-specialist` | API gateway, rate limiting, and routing |

### CI/CD & Deployment (4)

| Skill | Purpose |
|-------|---------|
| `ci-cd-specialist` | Pipeline configuration and automation docs |
| `deployment-specialist` | Release, deploy, and rollback procedures |
| `build-system-specialist` | Build tools and compilation pipeline docs |
| `release-manager` | Release coordination and versioning strategy |

### Quality & Testing (5)

| Skill | Purpose |
|-------|---------|
| `testing-strategist` | Test pyramid, coverage goals, and quality gates |
| `integration-tester` | E2E, contract, and service-level testing docs |
| `api-testing-specialist` | Contract testing, collections, and API monitoring |
| `accessibility-specialist` | WCAG compliance and inclusive design docs |
| `performance-engineer` | Benchmarking and optimization documentation |

### Development Workflow (8)

| Skill | Purpose |
|-------|---------|
| `readme-specialist` | Compelling project README creation |
| `changelog-writer` | Release notes and changelog documentation |
| `contributing-guide-writer` | Open source contribution guidelines |
| `migration-guide-writer` | Version migration and upgrade guides |
| `troubleshooting-specialist` | Error resolution and FAQ documentation |
| `git-workflow-specialist` | Branching strategy and commit conventions |
| `dependency-manager` | Package management, lock files, and vulnerability scanning |
| `code-generator` | Scaffolding and code generation docs |

### Infrastructure & Operations (9)

| Skill | Purpose |
|-------|---------|
| `monitoring-specialist` | Metrics, dashboards, and alerting docs |
| `logging-specialist` | Structured logging and log analysis docs |
| `sre-specialist` | SLOs, error budgets, and incident management |
| `caching-specialist` | Multi-layer caching strategy documentation |
| `backup-specialist` | Backup, restore, and disaster recovery docs |
| `secret-management-specialist` | Vault, secrets rotation, and encryption |
| `config-manager` | Configuration and environment variable management |
| `incident-response-specialist` | Incident response, on-call, and postmortems |

### Compliance & Governance (2)

| Skill | Purpose |
|-------|---------|
| `compliance-documenter` | Regulatory compliance (SOC 2, GDPR, HIPAA) docs |
| `documentation-strategist` | Information architecture and doc planning |

### Environment & Setup (2)

| Skill | Purpose |
|-------|---------|
| `environment-specialist` | Development environment setup guides |
| `dependency-manager` | Dependency management and lock file docs |

### NeoRWC-Specific (4)

| Skill | Purpose |
|-------|---------|
| `neorwc-cli` | CLI tool documentation for neorwc |
| `neorwc-config` | Configuration and provider setup guides |
| `neorwc-workflow` | Scan-Analyze-Write documentation workflow |
| `neorwc-template-creator` | Creating custom persona skill templates |

## License

ISC
