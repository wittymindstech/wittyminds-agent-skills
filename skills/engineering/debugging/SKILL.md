---
name: debugging
description: Investigate software defects systematically using logs, metrics, traces, reproduction steps, hypotheses, tests and root-cause analysis.
---

# Debugging

## Procedure
1. Capture the symptom, impact, environment and time window.
2. Gather relevant logs, metrics, traces and recent changes.
3. Reproduce the issue safely where possible.
4. Form and prioritize hypotheses.
5. Test one hypothesis at a time.
6. Identify root cause rather than only the visible symptom.
7. Implement the smallest safe correction.
8. Add regression tests.
9. Monitor after deployment.
10. Document root cause and prevention actions.

## Rules
Do not invent log entries or claim a root cause without evidence.
Protect secrets and personal data in diagnostic output.
Do not run destructive commands without explicit authorization.

## Output
Return symptom, evidence, hypotheses,
root cause or unknown status, remediation, tests and prevention.
