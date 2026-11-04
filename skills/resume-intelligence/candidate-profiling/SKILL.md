---
name: candidate-profiling
description: Classify an IT candidate's professional profile using demonstrated experience, responsibilities and technical ownership. Use when determining suitable engineering role families and seniority.
---

# Candidate Profiling

## Objective
Identify the candidate's demonstrated role profile without relying only on job title or years of experience.

## Role families
- Fresher / Junior Developer
- Backend Developer
- Frontend Developer
- Full Stack Developer
- Senior Software Developer
- Technical Lead
- Team Lead
- Solution Architect
- Technical Architect

## Evaluate
- Total and relevant professional experience, based on stated dates.
- Backend, frontend, database, cloud and DevOps experience.
- Project complexity and individual contribution.
- Technical design and architecture ownership.
- Production support and operational responsibility.
- Mentoring, team leadership, delivery ownership and customer interaction.

## Rules
- Treat years-of-experience thresholds as configurable guidance, not hard rules.
- Distinguish participation from ownership.
- Return multiple plausible profiles when evidence supports them.
- Explain uncertainty and cite resume evidence.
- Do not infer protected or sensitive personal attributes.

## Output
Return `primary_profile`, `secondary_profiles`, `total_experience_years`,
`relevant_experience_years`, `seniority_assessment`, `classification_evidence`,
`uncertainties` and `confidence`.
