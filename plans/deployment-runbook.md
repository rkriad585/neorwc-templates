# Plan: Operational Runbook (DevOps)

**Goal:** Create the "Manual" for running this application in a production environment.

**Files to Generate:**
1.  **`docs/ops/deployment.md`**:
    - CI/CD Pipeline explanation (GitHub Actions/GitLab CI analysis).
    - Docker build and run commands.
2.  **`docs/ops/configuration.md`**:
    - **ENV VARS Table:** Name, Description, Required?, Default Value.
    - Secret Management strategy (e.g., "Do not commit .env").
3.  **`docs/ops/monitoring.md`**:
    - Health Check endpoints (look for `/health` or `/status` routes).
    - Logging format analysis (JSON vs Text).

**Instructions:**
- Heavily weigh `Dockerfile`, `docker-compose.yml`, and config files.
