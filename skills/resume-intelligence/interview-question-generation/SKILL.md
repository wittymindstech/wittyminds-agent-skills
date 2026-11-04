---
name: interview-question-generation
description: Generate role-appropriate interview questions grounded in resume projects, claimed skills, job requirements and evidence gaps.
---

# Interview Question Generation

## Objective
Create targeted questions that verify the candidate's stated experience and assess role-relevant capability.

## Question categories
Programming and fundamentals; backend; frontend; databases; APIs; cloud and deployment;
debugging; testing; system design; distributed systems; security; production operations;
architecture; leadership; customer and stakeholder communication.

## Question types
Conceptual, coding, project deep-dive, scenario-based, debugging, system-design and leadership questions.

## Procedure
1. Use the target role and JD, if provided.
2. Prioritize important resume claims that need verification.
3. Ask about specific projects and the candidate's individual contribution.
4. Include realistic scenarios at the appropriate level.
5. Provide expected answer points and evaluation criteria.
6. Avoid duplicate or generic questions unrelated to the supplied evidence.

## Output
For each question return `question`, `category`, `difficulty`, `related_competency`,
`resume_evidence`, `expected_answer_points` and `evaluation_criteria`.
Respect the requested question count.
