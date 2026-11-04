---
name: prompt-engineering
description: Design, review and improve prompts for LLM applications, including instruction hierarchy, structured outputs, grounding, tool use and evaluation.
---

# Prompt Engineering

## Objective
Create clear, testable prompts for reliable LLM behavior.

## Practices
- Define role, task, context and success criteria.
- Separate trusted instructions from untrusted user or document content.
- State constraints, refusal boundaries and uncertainty handling.
- Provide representative examples when they improve consistency.
- Specify output schemas and allowed values.
- Require evidence for factual claims when sources are available.
- Define tool-selection criteria and error handling.
- Keep prompts modular and version-controlled.

## Structured output
Use JSON Schema or an equivalent contract where supported.
Validate outputs outside the model and handle malformed or incomplete responses.

## Evaluation
Test normal, ambiguous, adversarial, incomplete and out-of-scope inputs.
Track task success, schema validity, hallucination rate, latency and cost.

## Output
Return the prompt, assumptions, input contract, output contract,
edge cases and a test plan.
