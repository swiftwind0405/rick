---
name: repo-inspect
description: Build a reliable map of a repository before making changes.
---

# Repo inspect

## Goal

Understand the repository enough to identify the correct change surface, constraints, and verification path.

## Procedure

1. Read the top-level README, AGENTS.md, package manifests, and CI configuration.
2. Identify the application entry points, main modules, scripts, and test/e2e commands.
3. Search for the symbols, routes, or files named by the request.
4. Trace the smallest relevant execution path.
5. Record assumptions and unknowns before proposing changes.

## Output

Return:

- repository shape
- relevant files and symbols
- existing conventions
- likely change surface
- verification commands
- risks and open questions

Do not modify files during inspection unless explicitly requested.
