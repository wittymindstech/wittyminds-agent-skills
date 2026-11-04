---
name: microservices
description: Design and review microservice architectures, including service boundaries, data ownership, communication, resilience, deployment and observability.
---

# Microservices Architecture

## Objective
Use service decomposition where independent ownership, scaling or deployment justifies the complexity.

## Evaluate
- Domain boundaries and bounded contexts.
- Service responsibilities and ownership.
- API and event contracts.
- Database-per-service and data consistency.
- Synchronous versus asynchronous communication.
- Service discovery and API gateway patterns.
- Timeouts, retries, circuit breakers and bulkheads.
- Distributed tracing and correlation IDs.
- Deployment, rollback and version compatibility.
- Security and service-to-service identity.

## Rules
Do not recommend microservices by default.
Discuss the operational cost compared with a modular monolith.
Avoid shared-database coupling unless explicitly justified.

## Output
Return service boundaries, contracts, data ownership,
failure handling, deployment strategy and trade-offs.
