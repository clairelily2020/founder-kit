---
name: founder-investigate
description: Diagnose an underperforming campaign, launch, landing page, post, email, funnel, or growth experiment. Use when the user asks why something failed, underperformed, converted poorly, got low reach, or produced weak results.
---

# Founder Investigate

Do not guess. Diagnose from symptoms, funnel steps, baselines, hypotheses, and tests.

## Step 1: Get The Numbers

Ask for three numbers first:

1. Actual result.
2. Expected result.
3. Baseline from a similar past effort or industry expectation.

If the user has no numbers, ask for the closest available observable signals.

## Step 2: Map The Funnel

Use the funnel that matches the asset.

Examples:

```text
Post: impressions -> profile clicks -> link clicks -> signup -> activation
Landing page: visitors -> CTA clicks -> form starts -> submissions -> qualified leads
Email: delivered -> opened -> clicked -> replied -> booked
Launch: visits -> signups -> activation -> retained users
```

Find the step with the largest drop compared with baseline.

## Step 3: Build Hypotheses

Create 3 to 5 hypotheses only.

Each hypothesis needs:

- what might be true
- what data would support it
- what data would disprove it
- how to check
- effort and impact

## Step 4: Prioritize Tests

Rank by low effort and high learning value.

## Output

```markdown
## Investigation: {asset}

Symptom:
Actual {X}, expected {Y}, baseline {Z}.

Funnel:
| Step | Actual | Baseline | Gap | Suspicion |
| --- | --- | --- | --- | --- |

Most suspicious step:
{step and reason}

Hypotheses:

H1: {hypothesis}
- If true: {observable prediction}
- How to check: {method}
- Effort: {low/medium/high}
- Impact: {low/medium/high}

Recommended order:
1. {test}
2. {test}
3. {test}

Next action:
{one concrete step}
```

## Rules

- Do not give fixes before identifying the likely failure point.
- Do not list 20 possible causes.
- Do not treat normal variance as failure.
- If tracking is missing, make instrumentation the first finding.
