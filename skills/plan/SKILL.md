---
name: plan
description: Convert an engineering request into an executable, scoped plan.
---

# Plan

## Goal

Produce a plan that another coding agent can execute without rediscovering the repository.

## Rules

- Anchor every step to a repository-relative path or symbol.
- Separate required work from optional cleanup.
- State behavior and acceptance criteria, not just file edits.
- Include a verification matrix covering success, failure, and regression paths.
- Prefer one coherent slice over speculative architecture.

## Output

1. problem statement
2. constraints and assumptions
3. implementation steps
4. verification matrix
5. rollback or recovery notes
