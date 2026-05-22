# Growth Skill Architecture

Use this when designing a skill system for founder or growth work.

## Principle

A good skill system separates repeatable workflows into small skills instead of one giant prompt.

Each skill should have:

- clear trigger
- narrow job
- input expectations
- output format
- handoff path
- failure mode

## Recommended Skill Set

For a founder growth system:

| Skill | Job |
| --- | --- |
| Router | detect intent and send work to the right skill |
| Office Hours | clarify vague ideas |
| Variants | produce distinct options |
| Review | find issues before shipping |
| Preflight | check final launch hygiene |
| Investigate | diagnose weak results |
| Retro | extract lessons and next commitments |
| Playbook | provide reusable reference patterns |
| Planning | turn goals into milestones |
| Docs | write structured proposals and specs |

## Skill Design Rules

- Keep the main skill short.
- Put long references in separate files.
- Use examples only when they change behavior.
- Avoid private paths or company-specific assumptions in public skills.
- Make output formats explicit.
- Name handoffs, but do not force them.

## Anti-Pattern

One giant "growth expert" prompt usually fails because it mixes strategy, copy, analytics, and execution without knowing which job the user needs.
