---
name: test-driven-development
description: Use when the user explicitly asks for test-first development or when a bugfix needs a failing regression test before code changes
---

# Test-Driven Development

TDD is selective, not the default for every implementation task.

## When To Use

- the user explicitly asks for TDD, test-first, or red-green-refactor
- a bugfix needs a failing regression test before changing code
- the risk of silent regression is high enough that test-first design is clearly worth the overhead

## When Not To Use

- routine implementation where the user did not ask for TDD
- exploratory spikes or local experiments
- docs, config, or non-code edits

## Process

1. Write one failing test or reproduction for the target behavior
2. Run it and confirm it fails for the expected reason
3. Write the smallest code change that makes it pass
4. Re-run the targeted test and any nearby checks

## Quick Reference

| Situation | Action |
|-----------|--------|
| User says "use TDD" | Load this skill |
| Bugfix needs proof before fix | Use this skill |
| Normal feature work | Do not force TDD by default |

## Common Mistakes

- treating TDD as mandatory for all coding tasks
- writing the implementation before proving the test fails
- claiming a TDD fix worked without a fresh verification run
