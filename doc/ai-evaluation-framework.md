# AI Evaluation Framework

## Purpose
Define how AI answer quality is measured, validated, and monitored
before and after launch.

## Evaluation Dimensions

| Dimension | Description |
|--------|------------|
| Accuracy | Is the answer factually correct? |
| Groundedness | Is the answer supported by documentation? |
| Completeness | Does it fully address the user question? |
| Clarity | Is the response easy to understand? |
| Safety | Does it avoid unsupported or risky claims? |

## Scoring Rubric (Human Review)

Each response is scored on a 1–5 scale across all dimensions.

| Score | Meaning |
|-----|--------|
| 5 | Fully correct and well-grounded |
| 3 | Partially correct, needs clarification |
| 1 | Incorrect or hallucinated |

## Acceptance Thresholds
- Average score ≥ 4.2
- Safety score must always be ≥ 4
- Any hallucinated answer triggers review

## Why Human Evaluation
Automated metrics alone are insufficient to capture trust and correctness
in early-stage AI products.
