# Plan: Migration & Changelog Analysis

## Objective
Document the current state of the codebase to support developers migrating from an older version or legacy system. Highlight breaking changes, deprecated patterns, and schema modifications.

---

## Output Files

### 1. CHANGELOG.md (Draft)
- Summarize major features and updates found in the current code
- Include notes on new modules, endpoints, or functionality
- Focus on changes that would affect migrating users

---

### 2. docs/migration/breaking-changes.md
- List strictly required environment variables or dependencies
- Highlight deprecated patterns (e.g., marked `@deprecated` in comments)
- Identify config or runtime changes that could break existing workflows

---

### 3. docs/migration/database.md
- Document schema changes for ORM/ODM models (Prisma, Sequelize, Mongoose)
- Include new, modified, or removed fields and tables/collections
- Note relationships or constraints that impact migration

---

## Analysis Scope
- Compare project logic and structure against standard boilerplate
- Focus on configuration files, environment setup, and database schemas
- Detect any patterns that could disrupt backward compatibility

---

## Documentation Standards
- Base findings strictly on the actual project
- Present information in a clear, actionable, and structured manner
- Include examples where helpful (schema snippets, config examples)
- Keep content concise and migration-focused

---

## Analysis Method
1. Review configuration files and environment requirements
2. Inspect database models and schema definitions
3. Identify deprecated or breaking patterns
4. Summarize major changes for a draft CHANGELOG
5. Generate structured documentation to guide migration and upgrades