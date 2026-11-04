---
name: mcp-development
description: Design and implement Model Context Protocol servers and clients with clear tool schemas, resource boundaries, authentication and safe error handling.
---

# MCP Development

## Objective
Expose useful, narrowly scoped capabilities through MCP-compatible interfaces.

## Design
- Identify the external capability and user need.
- Define tools, resources and prompts only where appropriate.
- Use precise names and descriptions.
- Define strict input schemas and validate arguments.
- Apply authentication and least-privilege authorization.
- Validate and sanitize inputs.
- Return structured, bounded outputs.
- Handle errors without leaking secrets or internal details.
- Add timeouts, rate limits and audit logs.
- Document transport, deployment and version compatibility.

## Security
Never hardcode credentials.
Do not expose unrestricted filesystem, shell or database access.
Treat tool arguments and external content as untrusted.

## Output
Return interface design, schemas, security model,
error handling, deployment notes and tests.
