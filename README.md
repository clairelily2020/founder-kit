# Founder Kit

A public Claude Code / Codex plugin for B2B SaaS founders, indie hackers, and small growth teams.

Founder Kit helps you turn vague ideas into concrete campaigns, generate sharper variants, review work from multiple operating angles, run pre-launch checks, diagnose weak results, and close the loop with retros.

It is built for people who have to think, ship, measure, and adjust without a large team.

## Who It Is For

- Solo founders who own marketing and growth.
- Small SaaS teams without dedicated strategy, copy, data, and growth functions.
- Indie hackers shipping product, content, and distribution at the same time.
- Growth leads who need a structured second brain for campaign decisions.

It is not a generic copy generator. The plugin is more useful when you want a sharper brief, a stronger launch plan, a better review pass, or a clear explanation of why something did not work.

## What Is Inside

Founder Kit includes 10 skills:

| Skill | Use it for |
| --- | --- |
| `founder-stack` | Route founder and growth tasks to the right workflow. |
| `founder-office-hours` | Turn a vague idea into a testable brief with six hard questions. |
| `founder-variants` | Generate different versions of a campaign, post, landing page, or offer. |
| `founder-review` | Review work from strategy, copy, design, growth, data, and founder angles. |
| `founder-preflight` | Run a final launch checklist before publishing. |
| `founder-investigate` | Diagnose weak results with funnel data and falsifiable hypotheses. |
| `founder-retro` | Run a weekly or monthly retro with facts, lessons, and next commitments. |
| `founder-growth-playbook` | Reference proven launch, positioning, community, and open-source growth patterns. |
| `long-term-plan` | Break a long-term goal into milestones, tasks, and schedule. |
| `doc-coauthoring` | Co-write proposals, specs, decision docs, and strategy documents. |

## Workflow

```text
office-hours -> variants -> review -> preflight -> ship -> retro
                                            |
                                            v
                                      investigate
```

The loop is intentionally simple:

1. Pressure-test the idea before spending time.
2. Generate distinct options, not small rewrites.
3. Review from several roles before publishing.
4. Check links, tracking, timing, and obvious failure points.
5. Ship.
6. Diagnose or retro based on real data.

## Example Prompts

```text
I have an idea for a LinkedIn campaign. Help me pressure-test it.
```

```text
Create three different versions of this landing page hero.
```

```text
Review this launch post from strategy, copy, growth, and data angles.
```

```text
This campaign underperformed. Help me diagnose what happened.
```

```text
Run a weekly retro for my founder work.
```

## Why This Plugin Exists

Most AI marketing help jumps straight to output. That is often the wrong move.

Founder Kit adds structure before output:

- define the audience and job
- choose one measurable goal
- create real variants
- review with role-specific judgment
- ship with fewer avoidable mistakes
- learn from results without guessing

It works best when the user brings real context: numbers, drafts, target audience, platform, timeline, constraints, or a concrete business goal.

## Installation

```bash
claude plugin marketplace add https://github.com/clairelily2020/founder-kit.git
claude plugin install founder-kit
```

For local development:

```bash
git clone https://github.com/clairelily2020/founder-kit.git
claude plugin install ./founder-kit
```

## Optional Companion Skills

These are not required, but they pair well with Founder Kit:

| Skill or plugin | Why it helps |
| --- | --- |
| `data-analysis` | Analyze campaign metrics during investigate or retro. |
| `humanizer` | Clean up copy before publishing. |
| `website-design` | Turn landing page strategy into better visual direction. |
| `spreadsheets` | Work with campaign trackers, KPI sheets, and content calendars. |

## Public-Safe Scope

This repository is intentionally generic:

- no private workspace paths
- no personal identity assumptions
- no company-specific playbooks
- no private customer data
- no personal calendar or vault dependency

The skills can still be customized after installation. If you adapt the plugin for a specific company or founder, keep those private details in your own local fork or private skill layer.

## License

MIT. Use it, fork it, and adapt it for your own workflow.
