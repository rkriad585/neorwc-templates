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

### Framework & Platform (10)

| Skill | Purpose |
|-------|---------|
| `frontend-developer` | UI framework and component documentation |
| `backend-developer` | Server-side API and service documentation |
| `mobile-developer` | iOS, Android, and cross-platform app docs |
| `api-documenter` | REST and GraphQL API reference documentation |
| `graphql-specialist` | GraphQL schema, queries, and resolver docs |
| `docker-specialist` | Dockerfile, Compose, and container docs |
| `database-specialist` | SQL/NoSQL schema and query documentation |
| `ci-cd-specialist` | Pipeline configuration and automation docs |
| `deployment-specialist` | Release, deploy, and rollback procedures |
| `build-system-specialist` | Build tools and compilation pipeline docs |

### Quality & Testing (3)

| Skill | Purpose |
|-------|---------|
| `integration-tester` | E2E, contract, and service-level testing docs |
| `accessibility-specialist` | WCAG compliance and inclusive design docs |
| `performance-engineer` | Benchmarking and optimization documentation |

### Development Workflow (6)

| Skill | Purpose |
|-------|---------|
| `readme-specialist` | Compelling project README creation |
| `changelog-writer` | Release notes and changelog documentation |
| `contributing-guide-writer` | Open source contribution guidelines |
| `migration-guide-writer` | Version migration and upgrade guides |
| `troubleshooting-specialist` | Error resolution and FAQ documentation |
| `git-workflow-specialist` | Branching strategy and commit conventions |

### Observability & Operations (7)

| Skill | Purpose |
|-------|---------|
| `monitoring-specialist` | Metrics, dashboards, and alerting docs |
| `logging-specialist` | Structured logging and log analysis docs |
| `sre-specialist` | SLOs, error budgets, and incident management |
| `caching-specialist` | Multi-layer caching strategy documentation |
| `backup-specialist` | Backup, restore, and disaster recovery docs |
| `webhook-specialist` | Webhook events, payloads, and integration docs |
| `config-manager` | Configuration and secrets management docs |

### Compliance & Governance (2)

| Skill | Purpose |
|-------|---------|
| `compliance-documenter` | Regulatory compliance (SOC 2, GDPR, HIPAA) docs |
| `documentation-strategist` | Information architecture and doc planning |

### Environment & Setup (2)

| Skill | Purpose |
|-------|---------|
| `environment-specialist` | Development environment setup guides |
| `code-generator` | Scaffolding and code generation docs |

### NeoRWC-Specific (4)

| Skill | Purpose |
|-------|---------|
| `neorwc-cli` | CLI tool documentation for neorwc |
| `neorwc-config` | Configuration and provider setup guides |
| `neorwc-workflow` | Scan-Analyze-Write documentation workflow |
| `neorwc-template-creator` | Creating custom persona skill templates |

## License

ISC
