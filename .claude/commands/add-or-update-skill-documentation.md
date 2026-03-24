---
name: add-or-update-skill-documentation
description: Workflow command scaffold for add-or-update-skill-documentation in everything-claude-code.
allowed_tools: ["Bash", "Read", "Write", "Grep", "Glob"]
---

# /add-or-update-skill-documentation

Use this workflow when working on **add-or-update-skill-documentation** in `everything-claude-code`.

## Goal

Adds a new skill or updates documentation for an existing skill. Typically involves creating or modifying SKILL.md files under skills/ or docs/xx/skills/ directories.

## Common Files

- `skills/*/SKILL.md`
- `docs/*/skills/*/SKILL.md`
- `AGENTS.md`
- `README.md`

## Suggested Sequence

1. Understand the current state and failure mode before editing.
2. Make the smallest coherent change that satisfies the workflow goal.
3. Run the most relevant verification for touched files.
4. Summarize what changed and what still needs review.

## Typical Commit Signals

- Create or update SKILL.md under skills/<skill-name>/ or docs/<lang>/skills/<skill-name>/
- Optionally update AGENTS.md or README.md to reflect new skill count or catalog
- Commit with message referencing the skill and a summary of changes

## Notes

- Treat this as a scaffold, not a hard-coded script.
- Update the command if the workflow evolves materially.