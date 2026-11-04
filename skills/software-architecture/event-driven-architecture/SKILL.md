---
name: event-driven-architecture
description: Design event-driven systems using brokers, queues and streams, including event contracts, delivery guarantees, ordering, retries and observability.
---

# Event-Driven Architecture

## Objective
Design reliable asynchronous communication between system components.

## Evaluate
- Event producers and consumers.
- Event schemas and compatibility.
- Broker or queue selection.
- Delivery semantics and idempotent processing.
- Ordering, partitioning and consumer groups.
- Retry policies and dead-letter queues.
- Backpressure and consumer lag.
- Outbox and inbox patterns.
- Event replay and retention.
- Monitoring, tracing and alerting.

## Rules
Do not claim exactly-once business processing merely because a broker offers delivery features.
Explain duplicate handling and failure recovery.
Choose queues versus streams based on workload requirements.

## Output
Return event flow, schema, broker rationale,
delivery model, failure handling and operational metrics.
