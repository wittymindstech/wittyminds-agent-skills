---
name: python-fastapi
description: Build maintainable Python backend services and FastAPI applications with typed schemas, validation, testing, security and operational readiness.
---

# Python and FastAPI

## Practices
- Use supported Python versions and pinned dependencies.
- Organize code into routers, services, schemas and repositories where appropriate.
- Use Pydantic models for request and response validation.
- Apply dependency injection and clear configuration boundaries.
- Handle errors consistently.
- Use async only where it provides value and dependencies support it.
- Add authentication, authorization and input validation.
- Write unit and integration tests.
- Add structured logging, health checks and metrics.
- Containerize and document deployment.

## Rules
Never commit secrets.
Do not block the event loop with synchronous work in async endpoints.
Use database transactions and connection lifecycle management correctly.

## Output
Return implementation plan, project structure,
API contracts, validation, tests and deployment notes.
