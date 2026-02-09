# Plan: Legacy Code Refactor Analysis

**Goal:** Document the current messy state to plan a clean-up or rewrite.

**Files to Generate:**
1.  **`docs/refactor/technical-debt.md`**:
    - Identify complex functions (Cyclomatic Complexity).
    - Flag "Magic Numbers" or hardcoded strings.
    - List dependencies that are outdated or deprecated.
2.  **`docs/refactor/dependency-graph.md`**:
    - Text-based description of tightly coupled modules.
    - "God Objects" (files that do too much).
3.  **`docs/refactor/roadmap.md`**:
    - Suggested order of refactoring (e.g., "Extract Utils first," "Type strictness second").

**Instructions:**
- Look for large files (>300 lines).
- Look for deeply nested `if/else` statements.
- Look for `TODO` or `FIXME` comments in the code.
