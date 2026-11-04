---
name: resume-jd-matching
description: Compare a candidate resume with a job description, mapping requirements to resume evidence and identifying matches, partial matches and evidence gaps.
---

# Resume vs Job Description Matching

## Objective
Assess evidence-based alignment between a resume and a supplied job description.

## Procedure
1. Extract mandatory, preferred and contextual requirements from the JD.
2. Normalize equivalent skill names without changing the requirement.
3. Map each requirement to specific resume evidence.
4. Assess relevance, recency and depth of evidence.
5. Identify partial matches, missing evidence and contradictory evidence.
6. Separate technical, domain, experience, architecture and leadership requirements.
7. Calculate scores only using caller-supplied weights and scoring rules.

## Match labels
- Strong evidence
- Partial evidence
- Not evidenced
- Contradictory evidence
- Not applicable

## Rules
- A keyword match alone is not proof of proficiency.
- Do not assume missing resume evidence means the candidate cannot perform the skill.
- Do not silently relax mandatory JD requirements.
- Explain every important match and gap with evidence.
- Keep general technical capability separate from JD-specific suitability.

## Output
Return `requirements`, `requirement_matches`, `mandatory_coverage`,
`preferred_coverage`, `evidence_gaps`, `weighted_score` and `assessment_summary`.
If no scoring weights are provided, return qualitative matching without inventing a score.
