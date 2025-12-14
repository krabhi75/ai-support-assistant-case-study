# Prompt Iterations & Evaluation

## Prompt v1 (Baseline)
Simple system prompt requesting an answer from documentation.

### Issues Observed
- Overconfident tone
- Missing source citations
- Partial answers

---

## Prompt v2 (Source-Grounded)
Added instructions to cite sources and avoid guessing.

### Improvements
- Reduced hallucinations
- Higher user trust

### Remaining Issues
- Occasionally verbose
- Slow responses

---

## Prompt v3 (Production Candidate)
- Explicit fallback instructions
- Concise response guidelines
- Source citation enforced

### Decision
Prompt v3 selected based on evaluation scores and user feedback.
