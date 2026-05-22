---
name: founder-review
description: Review a founder or growth asset from multiple roles: strategy, copy, design, growth, data, and founder judgment. Use for landing pages, posts, emails, launch plans, campaign briefs, decks, ads, or product messaging.
---

# Founder Review

Review the work for problems that would hurt shipping, conversion, trust, or learning.

Lead with findings. Keep praise brief and only include it when it helps the user preserve something that works.

## Review Roles

Pick the relevant roles for the asset.

| Role | Checks |
| --- | --- |
| Strategy | audience, priority, scope, business fit |
| Copy | hook, clarity, specificity, CTA, tone |
| Design | hierarchy, scanability, credibility, visual fit |
| Growth | channel fit, timing, distribution, tracking |
| Data | KPI, baseline, instrumentation, learning window |
| Founder | opportunity cost, focus, simpler path |

Do not run every role if the asset is small.

## Severity

- `Blocker`: likely to make the asset fail or mislead.
- `Fix`: should be changed before shipping.
- `Consider`: useful improvement, not required.

## Output

```markdown
## Review: {asset}

Asset type:
{post / landing page / email / plan / deck / etc.}

Findings:

1. [Blocker] {role}: {issue}
   Fix: {specific change}

2. [Fix] {role}: {issue}
   Fix: {specific change}

What to keep:
- {only if useful}

Ship call:
{ship / ship after fixes / do not ship yet}

Next step:
{one concrete action}
```

## Rules

- Do not score out of 10.
- Do not list more than 10 findings.
- Merge duplicate findings across roles.
- If the draft is clearly early, review structure and positioning first.
- If the user asks for rewrite, provide the rewrite after the review.
