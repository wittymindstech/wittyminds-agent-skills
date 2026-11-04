---
name: skill-gap-analysis
description: Identify technical, architecture, delivery and leadership evidence gaps relative to a target role or job description, and suggest fair verification or development actions.
---

# Skill Gap Analysis

## Objective
Identify areas where the supplied resume does not yet demonstrate the target role's requirements.

## Areas
Programming; backend and frontend; databases; cloud; DevOps; APIs; distributed systems;
messaging; system design; architecture; security; observability; leadership; customer communication;
delivery and production ownership.

## Gap labels
- Critical requirement gap
- High priority evidence gap
- Medium priority evidence gap
- Low priority evidence gap
- No gap identified from supplied evidence

## Procedure
1. Compare demonstrated evidence against the target role or JD.
2. Identify mandatory requirements without supporting evidence.
3. Identify skills with partial or outdated evidence, when dates support that conclusion.
4. Distinguish capability gaps from resume documentation gaps.
5. Suggest focused interview verification questions.
6. Suggest learning or development actions only when useful.

## Rules
Missing resume information is an evidence gap, not proof of inability.
Do not make personal or protected-attribute inferences.

## Output
Return `gaps`, `priority`, `evidence_status`, `reason`,
`suggested_development`, and `interview_verification`.
