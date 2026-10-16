---
name: verify
description: Verify a change with targeted, repeatable evidence.
---

# Verify

## Strategy

- Start with the narrowest check that can falsify the change.
- Prefer integration or E2E checks for behavior spanning boundaries.
- Run the full suite only at the end or when explicitly required.
- Capture exact commands and meaningful output.
- Distinguish a failed check from an unavailable environment.

## Output

Return a verification report:

- command
- purpose
- result
- artifact or log location
- remaining risk
