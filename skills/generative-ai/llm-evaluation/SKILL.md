---
name: llm-evaluation
description: Plan and execute systematic evaluation of LLM applications, prompts, RAG pipelines and agents using representative datasets and measurable quality criteria.
---

# LLM Evaluation

## Objective
Measure application quality before and after changes.

## Evaluation dimensions
- Task correctness
- Evidence faithfulness
- Relevance and completeness
- Structured-output validity
- Tool selection and tool-call correctness
- Robustness to ambiguous and adversarial input
- Latency and throughput
- Token usage and cost
- Safety and privacy behavior

## Procedure
1. Define the use case and acceptance criteria.
2. Build a representative, privacy-safe test dataset.
3. Include positive, negative, edge and adversarial cases.
4. Establish a baseline.
5. Evaluate component-level and end-to-end behavior.
6. Review failures and categorize root causes.
7. Compare model, prompt and retrieval changes.
8. Record versions, settings and results.

## Rules
Do not rely on a single aggregate score.
Use human review for high-impact judgments.
Do not expose personal data in evaluation datasets unnecessarily.

## Output
Return evaluation plan, dataset description, metrics, baseline,
results, failure analysis and release recommendation.
