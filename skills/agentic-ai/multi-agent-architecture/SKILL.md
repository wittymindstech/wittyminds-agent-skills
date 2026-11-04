---
name: multi-agent-architecture
description: Design multi-agent systems with clear specialist responsibilities, communication contracts, shared state, orchestration and evaluation.
---

# Multi-Agent Architecture

## Objective
Use multiple agents only when specialization or independent execution provides measurable value.

## Design steps
1. Define the overall task and decomposition.
2. Identify specialist responsibilities.
3. Define an orchestrator or coordination pattern.
4. Define message schemas and shared-state boundaries.
5. Define which agent may call which tools.
6. Validate intermediate outputs.
7. Handle retries, timeouts, loops and conflicting results.
8. Define human review points.
9. Evaluate end-to-end quality and cost against a single-agent baseline.

## Patterns
Sequential handoff, parallel specialist analysis, supervisor-worker,
router, critic-reviewer and event-driven coordination.

## Rules
Avoid duplicate responsibilities and unrestricted tool access.
Do not treat another agent's output as inherently correct.
Use deterministic validation for schemas and calculations.

## Output
Return agent roles, interaction flow, contracts, state ownership,
failure modes, security boundaries and evaluation plan.
