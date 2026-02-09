# Plan: Test Strategy & Coverage Analysis

**Goal:** Create a documentation suite that defines how the software should be tested.

**Files to Generate:**
1.  **`docs/testing/strategy.md`**:
    - Define the Testing Pyramid (Unit vs Integration vs E2E) specific to this project.
    - List recommended testing libraries based on `package.json`.
2.  **`docs/testing/test-plan.md`**:
    - **Critical Paths:** Identify the top 3 user flows that *must* work (e.g., Login, Checkout, Data Save).
    - **Edge Cases:** List potential failure points found in the logic.
3.  **`docs/testing/commands.md`**:
    - How to run tests locally.
    - How to mock external services (based on API calls found in code).

**Instructions:**
- Analyze existing `*.test.js` or `*_spec.py` files to understand current coverage.
- Look for `try/catch` blocks to identify error handling logic.
