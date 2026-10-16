---
name: review
description: Review an engineering change for correctness, regressions, and operational risk.
---

# Review

Review in this order:

1. correctness against the requested behavior
2. failure and boundary cases
3. security and data exposure
4. concurrency, retries, idempotency, and cleanup
5. compatibility and migration risk
6. maintainability and unnecessary complexity
7. verification quality

Report findings by severity with file and line references where possible. If there are no findings, say what was checked and what remains unverified.
