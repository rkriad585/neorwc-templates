# Plan: API Reference & Integration Guide

**Goal:** Create strictly technical documentation for consuming the API.

**Files to Generate:**
1.  **`docs/api/authentication.md`**:
    - Explain the Auth mechanism (JWT, OAuth, API Key).
    - Example usage with `curl`.
2.  **`docs/api/resources.md`**:
    - Group endpoints by Resource (e.g., Users, Products, Orders).
    - For every endpoint, provide: Method, URL, Body Schema, Response Schema.
3.  **`docs/api/errors.md`**:
    - List standard HTTP error codes used.
    - Example error response JSON.

**Instructions:**
- Scan controllers/routes folders heavily.
- Extract type definitions or schemas if possible.
