---
name: learn
description: Persistent instruction writer for /learn requests and any user instruction to remember, save, always do, or persist reusable behavior/preferences/rules into permanent memory files such as AGENTS.md, SOUL.md, USER.md, MEMORY.md, TOOLS.md, or domain-specific structured files. Use when guidance should apply long-term across sessions; do not use for temporary, ambiguous, sensitive, unsafe, experimental, or one-off instructions.
---

# Learn

Persist reusable user instructions into the right long-term file without duplicating existing guidance.

## Workflow

1. **Extract the instruction**
   - Identify the core rule, preference, workflow, convention, or behavior the user wants applied consistently.
   - Ignore temporary, task-specific, incomplete, unsafe, sensitive, or experimental guidance.

2. **Check for existing entries first**
   - Search relevant files before writing. Common targets:
     - `AGENTS.md` for behavior, rules, workflows, execution logic, tool-use rules, and process conventions.
     - `SOUL.md` for tone, persona, personality, and communication style.
     - `USER.md` for stable user preferences and user profile facts.
     - `MEMORY.md` or `memory/YYYY-MM-DD.md` for dated long-term context and decisions.
     - `TOOLS.md` for local environment/tool details.
     - Domain-specific files when the instruction clearly belongs there.
   - If the instruction already exists, do not duplicate it. Report:
     - File name
     - Line or section
     - Exact quote of the existing instruction

3. **Clarify if needed**
   - If the target file, scope, permanence, or meaning is unclear, ask concise clarification questions before writing.
   - Do not guess ambiguous persistent instructions.

4. **Generalize before saving**
   - Rewrite the instruction so it is clear, concise, context-independent, and reusable across future tasks/sessions.
   - Preserve the user’s intent, not necessarily their exact wording.

5. **Prefer executable or structured representation**
   - If the instruction can be represented, enforced, or executed as code, script, structured data, or explicit logic, use that form.
   - Keep it minimal, correct, maintainable, and directly usable.
   - Otherwise, write a short Markdown rule.

6. **Write the entry**
   - Add a clean standalone entry near the most relevant existing section.
   - Use this format when adding Markdown guidance:

```markdown
### [Short Title]

[Instruction or code/structured representation]

**Rationale (optional):**
[Why this matters and when it applies]
```

7. **Verify and report**
   - Re-read or otherwise inspect the edited file to confirm the entry was written once and in the intended location.
   - Reply with the target file, a brief summary of what changed, and quote the exact text that was added or changed so the user can see the persisted instruction.

## Safety

- Do not persist secrets, credentials, private sensitive details, or unsafe instructions.
- Do not overwrite broad identity/persona files unless the user explicitly requested that scope.
- Prefer adding small targeted entries over rewriting large files.
