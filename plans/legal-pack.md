# Plan: Open Source Compliance Kit

**Goal:** Generate the standard governance files required for a healthy Open Source project.

**Required Files:**
1.  **`LICENSE`**: 
    - Detect the license from `package.json` (MIT, Apache 2.0, GPL). 
    - If unknown, generate a placeholder MIT License and add a "TODO" note.
2.  **`CONTRIBUTING.md`**:
    - "How to clone."
    - "How to run tests."
    - "Pull Request Process."
3.  **`CODE_OF_CONDUCT.md`**:
    - Generate a standard Contributor Covenant v2.1 text.
4.  **`SECURITY.md`**:
    - Instructions on how to report vulnerabilities (e.g., "Email security@example.com").

**Instructions:**
- Use standard legal text where possible.
