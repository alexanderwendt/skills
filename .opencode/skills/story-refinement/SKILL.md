---
name: story-refinement
description: Use when refining, specifying, splitting, or clarifying user stories, epics, acceptance criteria, product requirements, backlog items, or implementation-ready tickets. Use ONLY for specification work, not implementation.
---

# Story Refinement

Use this skill when the user wants to refine ideas, stories, epics, features, requirements, or backlog items into clear, testable, implementation-ready work.

Do not write code, edit implementation files, or start technical implementation while using this skill unless the user explicitly switches from refinement to implementation.

## Workflow

1. Identify the user goal.
2. Clarify the actor, value, and scope.
3. Capture functional and non-functional requirements.
4. Identify assumptions, dependencies, risks, and open questions.
5. Split large work into smaller vertical stories.
6. Write observable acceptance criteria.
7. Mark whether the story is ready for development.

## Story Format

```markdown
## Story

As a <user or system actor>,
I want <capability>,
so that <benefit or outcome>.

## Scope

Included:
- <included behavior>

Excluded:
- <excluded behavior>

## Acceptance Criteria

- Given <context>, when <action>, then <expected result>.

## Dependencies

- <dependency or "None identified">

## Risks

- <risk or "None identified">

## Open Questions

- <question or "None">

## Ready For Development

Yes/No: <answer>
Reason: <brief explanation>
```

Acceptance criteria must be specific, testable, and observable.
