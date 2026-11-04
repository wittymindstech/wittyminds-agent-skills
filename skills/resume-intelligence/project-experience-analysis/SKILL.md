---
name: project-experience-analysis
description: Analyze software projects described in IT resumes to assess complexity, technologies, individual contribution, implementation depth and production ownership.
---

# Project Experience Analysis

## Objective
Assess what the candidate actually contributed to each project.

## Analyze each project
1. Project purpose and business problem.
2. Project type: academic, personal, internship, professional or enterprise production.
3. Stated technology stack.
4. Architecture and component responsibilities.
5. Backend, frontend and API implementation.
6. Database and integration work.
7. Cloud infrastructure, deployment and CI/CD.
8. Security, testing and reliability.
9. Performance and scale, only where stated.
10. Production support and operational ownership.
11. Candidate's specific contribution and outcomes.

## Ownership categories
- Mentioned / unclear
- Contributed to a component
- Implemented a feature or service
- Owned end-to-end delivery
- Designed or led the solution

## Rules
Do not attribute the entire project to the candidate when the resume describes team work.
Do not infer traffic, scale, revenue, performance improvements or business impact.
List follow-up questions when individual contribution is unclear.

## Output
Return project-wise `project_name`, `purpose`, `project_type`, `technologies`,
`architecture_evidence`, `candidate_contribution`, `ownership_level`, `outcomes`,
`unknowns` and `interview_followups`.
