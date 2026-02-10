# Plan: API Reference Guide

## Objective
Extract accurate technical details from the codebase and generate a structured, developer-ready API reference.

Documentation must reflect real controllers, routes, and validation logic — not assumptions.

---

## Output Location
All files must be generated inside:

docs/api/

Create one Markdown file per major controller, module, or resource:
- docs/api/users.md
- docs/api/auth.md
- docs/api/products.md
- etc.

---

## Scope of Analysis
- Scan routes/ and controllers/ folders thoroughly
- Identify middleware affecting endpoints
- Extract request validation schemas and types
- Detect common response patterns and wrappers

---

## Required Content Per Endpoint

Each endpoint section must include:

### 1. Endpoint
- **Method:** (GET, POST, PUT, DELETE, etc.)
- **URL:** Full route path
- **Description:** Short technical explanation
- **Authentication Required:** Yes/No

### 2. Parameters

Provide structured tables where applicable:

**Path / Query Parameters**
| Name | Type | Required | Description |

**Request Body (if applicable)**
| Field | Type | Required | Description |

Schemas must reflect actual validation rules or DTOs found in code.

---

### 3. Success Response

- HTTP Status Code
- JSON example based on actual controller response
- Field explanations (if non-obvious)

---

### 4. Errors

List common HTTP error codes used by the endpoint:
- 400 – Validation error
- 401 – Unauthorized
- 403 – Forbidden
- 404 – Not found
- 500 – Internal server error

Include at least one real example error JSON structure used in the project.

---

## Documentation Standards

- Use real route paths from the router configuration
- Do not invent parameters or responses
- Base schemas strictly on implementation
- Keep explanations concise and technical
- Ensure consistency across all resource files

---

## Analysis Method

1. Trace routes to controllers.
2. Extract request validation rules.
3. Inspect response structures.
4. Identify middleware (auth, roles, etc.).
5. Generate clean, resource-based documentation.