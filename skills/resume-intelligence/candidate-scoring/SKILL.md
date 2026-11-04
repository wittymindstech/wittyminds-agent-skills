---
name: candidate-scoring
description: Calculate consistent candidate competency scores using caller-provided role rubrics, weights and evidence ratings. Use when producing a transparent score breakdown.
---

# Candidate Scoring

## Objective
Calculate reproducible scores from validated competency ratings.

## Default evidence scale
0 = Not evidenced; 1 = Basic; 2 = Intermediate; 3 = Advanced; 4 = Strong ownership / expert evidence.

## Formula
For a competency with a maximum rating of 4:
weighted_points = (competency_score / 4) * competency_weight

overall_score = sum(weighted_points)

## Validation
1. Use only the rubric and weights supplied by the caller.
2. Confirm weights are numeric, non-negative and sum to 100 (or normalize only if explicitly requested).
3. Confirm every competency score is within the configured scale.
4. Do not convert missing evidence into a factual claim of no capability.
5. Keep evidence confidence separate from the numeric competency score.
6. Perform arithmetic in deterministic code when available and validate the result.
7. Return the calculation breakdown and any excluded or unavailable items.

## Recommendation bands
Use only caller-configured thresholds. If none are provided, return the numeric score without a hiring label.

## Output
Return `scoring_scale`, `weight_validation`, `competency_breakdown`,
`overall_score`, `thresholds_used` and `calculation_notes`.
