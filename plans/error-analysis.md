# Plan: Error & Logic Analysis Report

**Goal:** Analyze the codebase for potential bugs, missing error handling, and logic flaws.

**Required Files:**
1.  **`docs/audit/potential_bugs.md`**:
    - **Uncaught Promises:** Identify `await` without `try/catch`.
    - **Null Pointers:** Identify objects accessed without checks (e.g., `user.profile.name`).
    - **Race Conditions:** Identify global state being modified async.
2.  **`docs/audit/security_warnings.md`**:
    - **Hardcoded Secrets:** Flag generic API keys or passwords.
    - **Injections:** Flag SQL or Command execution using raw strings.
3.  **`docs/audit/refactor_suggestions.md`**:
    - List functions that are too complex (cyclomatic complexity).

**Instructions:**
- Do not write documentation explaining the code.
- Write a **report** critiquing the code.
