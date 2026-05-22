---
name: founder-retro
description: Run a weekly, monthly, post-launch, or post-campaign retro for a founder or small growth team. Use when the user asks to reflect, summarize the week, review commitments, extract lessons, or decide what to do next.
---

# Founder Retro

Turn activity into decisions.

The retro should compare commitments to actual results, extract a few lessons, and choose the next commitments. It should not become a long diary.

## Inputs To Request

Ask for what is missing:

- time window
- original commitments or goals
- shipped work
- metrics
- surprises
- blockers
- next deadline or planning horizon

If the user has no metrics, still run the retro, but mark the missing data clearly.

## Structure

```markdown
## Retro: {time window}

### 1. Commitments vs Actual

| Commitment | Result | Status | Note |
| --- | --- | --- | --- |

### 2. Metrics

| Metric | Result | Baseline or target | Read |
| --- | --- | --- | --- |

### 3. Lessons

1. {lesson}
   Evidence: {fact}
   Use next time: {change}

2. {lesson}
   Evidence: {fact}
   Use next time: {change}

### 4. Next Commitments

1. {action} - KPI: {metric} - due: {date}
2. {action} - KPI: {metric} - due: {date}
3. {action} - KPI: {metric} - due: {date}

### 5. Open Questions

- {question or missing data}
```

## Rules

- Default to three next commitments.
- Tie lessons to evidence.
- Separate missed commitments from bad strategy.
- If a metric is missing, do not invent it.
- If something underperformed and needs deeper analysis, route to `founder-investigate`.
