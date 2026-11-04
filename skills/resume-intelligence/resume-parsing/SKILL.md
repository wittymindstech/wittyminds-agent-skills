---
name: resume-parsing
description: Extract and structure information from IT resumes. Use when analyzing resume text or document-extraction output to identify experience, skills, projects, education and certifications.
---

# Resume Parsing

## Objective
Create a faithful, structured representation of the supplied resume.

## Procedure
1. Read all supplied resume content before summarizing.
2. Extract candidate-provided name and contact details only when needed for the requested workflow.
3. Extract employment history, titles, employers, dates and stated responsibilities.
4. Extract education and certifications, preserving the names and dates as written.
5. Extract programming languages, frameworks, databases, cloud platforms, DevOps tools and development tools.
6. Extract projects, objectives, technologies, stated contributions and outcomes.
7. Separate professional, internship, academic and personal-project experience.
8. Preserve source wording for important claims and identify the resume section or page when available.
9. Flag missing, ambiguous or inconsistent dates and details.

## Evidence rules
- A skill listed in a skills section is not proof of hands-on proficiency.
- Do not invent employers, dates, qualifications, metrics, technologies or achievements.
- Do not infer age, gender, religion, caste, health, disability or other sensitive traits.
- Mark absent information as `not_provided`; do not treat it as proof the candidate lacks the capability.

## Output
Return valid JSON with `candidate_profile`, `employment_history`, `education`, `certifications`,
`technical_skills`, `projects`, `achievements`, `source_evidence` and `missing_information`.
Use empty arrays for absent collections and `null` for unknown scalar values.
