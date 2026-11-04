---
name: technical-competency-assessment
description: Assess demonstrated IT competencies for fresher, developer, lead and architect roles. Use when evaluating technical depth against a configurable role-specific rubric.
---

# Technical Competency Assessment

## Objective
Assess demonstrated technical capability using role-specific criteria and evidence.

## Fresher / junior areas
Programming fundamentals; data structures and algorithms; modular programming; Git/GitHub;
frontend basics; backend and scripting; SQL and NoSQL; REST APIs; debugging and testing;
basic deployment, cloud and server concepts; IDEs, monitoring and relevant certifications.

## Experienced developer areas
Backend languages and frameworks; frontend frameworks; full-stack delivery; API design and
integration; SQL and NoSQL; Kafka and message queues; debugging; production and on-call support;
deployment; performance; customer communication; code reviews and collaboration.

## Architect areas
High-level and low-level design; business-to-technical translation; feasibility and trade-offs;
scalability, availability and low latency; microservices; event-driven systems and queues;
SQL/NoSQL architecture; concurrency; load balancing; deployment strategies; observability;
monitoring; security; cost optimization and documentation.

## Team lead areas
Technical depth; team leadership; mentoring; milestone and delivery management; Agile/Scrum;
customer calls; JIRA and work tracking; estimation; risk management; code reviews and collaboration.

## Evidence scale
0 = Not evidenced in supplied resume.
1 = Skill mentioned or basic exposure.
2 = Limited practical or project exposure.
3 = Clear hands-on implementation evidence.
4 = Strong ownership, design, optimization or mentoring evidence.

## Rules
- Use the rubric and weights supplied by the caller; do not invent weights.
- Distinguish keyword mentions from project evidence.
- Record the project, employment section or source passage supporting each rating.
- Mark missing evidence as `not_evidenced`, not as confirmed lack of skill.
- Keep professional, academic and personal-project evidence distinct.

## Output
For each competency return `name`, `score`, `weight`, `evidence_level`, `evidence`,
`assessment_reason` and `verification_questions`.
