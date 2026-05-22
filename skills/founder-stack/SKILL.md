---
name: founder-stack
description: Router and overview for the Founder Kit workflow. Use when a founder or growth lead asks for help with a new idea, campaign, launch, review, preflight check, retro, or investigation and the right sub-skill should be selected.
---

# Founder Stack

Use this as the router for founder and growth work.

The goal is to move from vague input to a useful next action without turning every request into generic advice.

## Workflow

```text
office-hours -> variants -> review -> preflight -> ship -> retro
                                            |
                                            v
                                      investigate
```

## Routing

| User intent | Route to |
| --- | --- |
| New idea, campaign, feature, content angle, or launch concept | `founder-office-hours` |
| Multiple versions, A/B options, alternate positioning, platform rewrites | `founder-variants` |
| Review a draft, plan, landing page, post, email, or creative asset | `founder-review` |
| Final check before publishing or launching | `founder-preflight` |
| Weak metrics, failed launch, low conversion, unclear drop-off | `founder-investigate` |
| Weekly, monthly, or post-launch reflection | `founder-retro` |
| Open-source launch, Product Hunt, positioning, community, contributor funnel | `founder-growth-playbook` |
| Long project planning with milestones and tasks | `long-term-plan` |
| Proposal, spec, strategy doc, or decision document | `doc-coauthoring` |

If the route is unclear, ask one concise question.

## Operating Roles

Use these roles inside review, variants, investigate, and retro work.

| Role | What it protects |
| --- | --- |
| Strategy | ICP, business priority, sequencing, resource tradeoffs |
| Copy | hook, clarity, CTA, tone, specificity |
| Design | visual hierarchy, scanability, production quality |
| Growth | channel fit, timing, distribution, tracking |
| Data | metric definition, baseline, instrumentation |
| Founder | scope, opportunity cost, speed, focus |

Do not pretend these are real people. They are lenses for analysis.

## Defaults

- Ask for numbers when the user asks why something failed.
- Ask for one KPI when the user has several goals.
- Recommend a next step, but do not force the whole workflow.
- Keep outputs short enough to act on.
- Prefer concrete decisions over broad frameworks.

## Handoff Rules

- After office-hours, suggest variants if the brief is ready.
- After variants, suggest review if one version is chosen.
- After review, suggest preflight if the asset is close to shipping.
- After preflight, the user ships outside the plugin.
- After results come in, use investigate or retro.
