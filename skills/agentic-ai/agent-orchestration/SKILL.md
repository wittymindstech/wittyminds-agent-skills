---
name: agent-orchestration
description: Design agent workflows that plan tasks, select tools, manage state, handle failures and produce validated outcomes.
---

# Agent Orchestration

## Objective
Build controllable agent workflows with explicit responsibilities and boundaries.

## Design
- Define the agent's goal and allowed scope.
- Break complex tasks into verifiable steps.
- Select the simplest suitable tool for each step.
- Define input and output contracts for tools.
- Track state and execution progress.
- Apply timeouts, retries and idempotency where appropriate.
- Validate tool results before using them.
- Provide escalation and human approval for consequential actions.
- Log decisions, tool calls, errors and outcomes.

## Rules
Do not use an LLM for deterministic work when a normal function is more reliable.
Avoid unnecessary agent-to-agent delegation.
Set budgets for steps, tokens, time and tool calls.
Treat tool outputs as untrusted data.

## Output
Return workflow, agent responsibilities, tool contracts,
state model, failure handling and observability plan.
