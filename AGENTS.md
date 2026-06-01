# Agent Team Instructions

This repository uses a project-local opencode software development team.

## Operating Model

- `project-manager` is the default and only primary agent.
- Specialist agents are subagents and should be used for focused work.
- Read relevant shared documentation before planning or implementing.
- Keep decisions, assumptions, and open questions in `docs/` when they affect future work.
- Prefer small, verifiable changes.
- Do not implement during story refinement unless the user explicitly asks to move from specification to implementation.

## Standard Flow

1. Clarify intent and scope.
2. Use `domain-researcher` when product/domain knowledge is missing.
3. Use `requirements-analyst` when business rules, constraints, or traceability are unclear.
4. Use `story-refiner` to produce implementation-ready stories.
5. Use `software-designer` for non-trivial technical design.
6. Use `task-planner` to break approved work into executable tasks.
7. Use the relevant language/frontend engineer for implementation.
8. Use `test-engineer` for verification planning and test failures.
9. Use `code-reviewer` before final delivery.

## Shared Docs

- Team workflow: `docs/team/README.md`
- Handoffs: `docs/team/handoff-template.md`
- Definition of done: `docs/team/definition-of-done.md`
- Product research: `docs/product/domain-research.md`
- Requirements: `docs/requirements/requirements.md`
- Architecture decisions: `docs/architecture/decisions.md`
