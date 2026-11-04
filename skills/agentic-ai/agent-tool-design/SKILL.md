---
name: agent-tool-design
description: Design reliable tools for AI agents, including function descriptions, input schemas, deterministic behavior, authorization, validation and error contracts.
---

# Agent Tool Design

## Objective
Make tools easy for an agent to select and safe for the backend to execute.

## Guidelines
- Give each tool one clear responsibility.
- Use action-oriented names and specific descriptions.
- Define required and optional parameters.
- Use enums, bounds and formats where possible.
- Keep schemas minimal but unambiguous.
- Validate inputs server-side.
- Apply authentication, authorization and least privilege.
- Make read-only and mutating operations explicit.
- Use idempotency for retryable mutations.
- Return concise structured results.
- Provide actionable errors without leaking implementation secrets.

## Output
Return tool name, description, JSON input schema,
authorization requirements, behavior, output contract and test cases.
