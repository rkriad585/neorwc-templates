# Plan: Migration & Changelog Analysis

**Goal:** Document the current state of the code to help developers migrating from an older version or legacy system.

**Files to Generate:**
1.  **`CHANGELOG.md`** (Draft):
    - Summarize major features found in the current code.
2.  **`docs/migration/breaking-changes.md`**:
    - Identify any strictly required environment variables or dependencies.
    - highlight deprecated patterns if comments indicate them (e.g., `@deprecated`).
3.  **`docs/migration/database.md`**:
    - Schema changes (look at Prisma/Sequelize/Mongoose models).

**Instructions:**
- Compare logic to standard boilerplate.
- Focus on configuration files and database schemas.
