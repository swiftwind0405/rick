# rick

rick is a personal agent harness for engineering work. It is designed to be used from Codex or other coding agents, with a small set of composable skills and a consistent evidence-first workflow.

## Principles

- Understand the repository before changing it.
- Prefer the smallest safe change that solves the user’s goal.
- Use end-to-end verification for behavior; avoid low-value test churn.
- Keep decisions, commands, and evidence visible.
- Stop safely when requirements or permissions are ambiguous.

## Skills

- repo-inspect: map a repository and identify constraints
- plan: turn a request into an implementation plan
- implement: make focused code changes
- review: perform a risk-oriented review
- verify: run targeted checks and record evidence
- release: prepare commits, changelog, and handoff

Each skill is self-contained in skills/<name>/SKILL.md.
