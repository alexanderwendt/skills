# Team Workflow

This project uses one primary opencode agent, `project-manager`, and specialist subagents for focused work.

## Roles

- `project-manager`: coordinates work and owns final delivery.
- `domain-researcher`: researches product and domain context.
- `requirements-analyst`: structures requirements, constraints, and traceability.
- `story-refiner`: turns ideas into implementation-ready stories.
- `software-designer`: designs technical solutions.
- `task-planner`: breaks approved work into executable tasks.
- `java-engineer`: Java implementation.
- `cpp-engineer`: C/C++ implementation.
- `python-engineer`: Python implementation.
- `angular-frontend-engineer`: Angular frontend implementation.
- `test-engineer`: verification strategy and test failure diagnosis.
- `code-reviewer`: final code review.
- `devops-build-engineer`: build, CI, dependencies, and release readiness.
- `architect`: cross-language architecture decisions.

## Workflow

1. Clarify the request.
2. Research domain context if needed.
3. Analyze requirements if business rules or constraints are unclear.
4. Refine stories before implementation.
5. Design non-trivial technical changes.
6. Plan tasks.
7. Implement with the relevant specialist.
8. Verify with tests/builds.
9. Review before delivery.
