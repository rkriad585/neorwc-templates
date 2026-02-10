# Plan: API Reference & Integration

## Objective
Produce a complete, strictly technical API reference that enables frontend, mobile, or third-party developers to integrate with the system confidently without needing access to the source code.

Documentation must reflect the actual implementation, not assumptions.

---

## Scope of Analysis
- Scan controllers/, routes/, handlers/, and middleware/ folders
- Review validation schemas and type definitions
- Inspect auth logic and request/response handling
- Identify shared response wrappers or error utilities
- Detect API versioning strategy (if any)

---

## Output Location
All documentation must be generated inside:

docs/api/

Create structured Markdown files grouped by resource.

---

## Deliverables Structure

### 1. docs/api/overview.md
Explain:

- Project purpose (technical summary only)
- Base URL and API versioning strategy
- Content type (JSON, XML, multipart, etc.)
- Authentication method (JWT, OAuth2, API Key, Session, etc.)
- Global middleware behavior (rate limiting, logging, CORS)

Include:
- Base request example
- Global response format (success & error wrapper)

---

### 2. Resource-Based Endpoint Files

Group endpoints by domain resource:

Examples:
- docs/api/users.md
- docs/api/products.md
- docs/api/orders.md

For each endpoint, provide:

- **Method**
- **URL**
- **Description**
- **Authentication required (Yes/No)**
- **Request Headers**
- **Path Parameters**
- **Query Parameters**
- **Request Body Schema**
- **Response Schema**
- **Example Request**
- **Example Success Response**
- **Example Error Response**
- **Possible HTTP Status Codes**

Schemas should be extracted from:
- Validation layers
- Type definitions (TypeScript, DTOs, Pydantic, etc.)
- ORM models (if applicable)

---

## Authentication Documentation

Clearly explain:

- Token format (Bearer, Cookie, API key header)
- Token lifecycle (login, refresh, expiration)
- Role/permission system (if implemented)
- Protected route mechanism
- Common auth-related errors

Include:
- Login example
- Authenticated request example

---

## Error Handling Documentation

Provide:

- Standard HTTP status codes used (200, 201, 400, 401, 403, 404, 500, etc.)
- Unified error response structure
- Example error JSON or XML
- Validation error format
- Internal server error format

---

## Required Output Standards

- Use real route paths and actual controller logic
- Do not invent endpoints
- Do not describe generic REST theory
- Extract schemas directly from the codebase
- Keep documentation precise and integration-focused
- Include code examples using curl or fetch

---

## Analysis Method

1. Scan routing entry points.
2. Trace routes to controllers/handlers.
3. Extract request validation schemas.
4. Identify response format patterns.
5. Analyze authentication middleware.
6. Group endpoints logically by resource.
7. Generate structured, implementation-accurate documentation.

---

## Constraints

- Avoid high-level marketing descriptions.
- Avoid speculative documentation.
- Base everything strictly on implementation.
- Keep language technical and integration-ready.