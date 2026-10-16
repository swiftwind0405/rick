---
name: implement
description: Implement a planned change with minimal, reviewable edits.
---

# Implement

## Goal

Make the smallest change that satisfies the approved plan.

## Procedure

1. Re-read the relevant code and local instructions.
2. Implement one coherent slice at a time.
3. Preserve existing public behavior unless the plan changes it.
4. Keep configuration, errors, and observability explicit.
5. Avoid unrelated refactors and generated noise.
6. After each slice, run the narrowest useful check.

## Output

Summarize:

- changed files
- behavior changed
- checks run
- known limitations
