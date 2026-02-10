# Plan: Legacy Refactor

## Objective
Document the current state of legacy or messy code to plan a structured cleanup or rewrite. Identify technical debt, risky patterns, and dependencies that hinder maintainability.

---

## Output Files

### 1. docs/refactor/technical-debt.md
- **Complex Functions:** Identify high cyclomatic complexity functions
- **Magic Numbers / Hardcoded Strings:** Flag constants or strings that should be configurable
- **Outdated / Deprecated Dependencies:** List libraries or modules needing updates
- **Other code smells:** Long functions, deep nesting, or excessive parameters

---

### 2. docs/refactor/dependency-graph.md
- Description of tightly coupled modules
- Highlight "God Objects" or files doing too much
- Text-based or ASCII module dependency map
- Identify risky module interactions

---

### 3. docs/refactor/roadmap.md
- Recommended order of refactoring steps
- Prioritization guide (e.g., "Extract utilities first," "Enforce type safety second")
- Suggested cleanup patterns or strategies
- Notes on backward compatibility or testing requirements

---

## Analysis Scope
- Identify large files (>300 lines)
- Detect deeply nested `if/else` blocks or complex loops
- Track `TODO` and `FIXME` comments
- Scan for repeated patterns, code duplication, and tightly coupled modules

---

## Documentation Standards
- Base findings strictly on the actual code
- Include file references, line numbers, or examples where helpful
- Keep explanations precise, actionable, and technical
- Focus on maintainability, readability, and long-term improvements

---

## Analysis Method
1. Scan all project files for size, nesting, and cyclomatic complexity
2. Identify hardcoded values and deprecated dependencies
3. Map module dependencies and coupling
4. Detect code smells and risky patterns
5. Generate structured reports with suggested cleanup priorities and roadmap