---
name: code-review-process
description: Use when reviewing code changes for correctness, regressions, maintainability, security, testing gaps, and repository standards.
---

# Code Review Process

Prioritize findings over summaries.

## Review Checklist

- Correctness and edge cases.
- Behavioral regressions.
- Security and data handling.
- Test coverage and meaningful assertions.
- Maintainability and unnecessary complexity.
- Compatibility with existing style and architecture.
- Build, lint, and CI implications.

## Output

```markdown
## Findings

- Severity: <critical|high|medium|low>
  File: <path:line>
  Issue: <description>
  Recommendation: <fix>

## Questions

- <question or "None">

## Residual Risk

- <risk or "None identified">
```

If there are no findings, state that explicitly.
