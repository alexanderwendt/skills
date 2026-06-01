---
name: testing-verification
description: Use when identifying, planning, running, or explaining build, lint, unit, integration, e2e, or manual verification steps.
---

# Testing Verification

Use this skill to make verification explicit.

## Verification Steps

1. Identify changed areas.
2. Find relevant project commands from docs or config files.
3. Prefer the smallest relevant checks first.
4. Run broader checks when risk or scope justifies it.
5. Report commands run, results, and unverified risks.

## Output

```markdown
## Verification

- Command: `<command>`
  Result: <passed|failed|not run>
  Notes: <brief notes>

## Untested Risk

- <risk or "None identified">
```
