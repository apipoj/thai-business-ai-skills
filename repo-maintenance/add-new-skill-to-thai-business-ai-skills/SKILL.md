---
name: add-new-skill-to-thai-business-ai-skills
description: Add a new skill to the Thai Business AI Skills repository in the correct format and location. Use when creating, reviewing, or integrating a new skill for this repo, including deciding whether to write an original skill, link an external skill, or create a Thai business wrapper.
---

# Add New Skill to Thai Business AI Skills

Add new skills to this repository in a way that keeps the library simple, consistent, and useful for Thai business users.

## Output requirements

- Keep the repo Thai-first for user-facing examples and browsing
- Keep `SKILL.md` standard and agent-facing
- Use simple, practical language
- Optimize for non-technical business users
- Do not add unnecessary files or process theater

## Working method

1. Decide whether the skill should exist in this repo
   - Add an original skill only if it solves a real recurring Thai business task
   - Link an external skill if a strong canonical version already exists
   - Create a wrapper if the base capability exists but needs Thai business adaptation
2. Choose the correct category
   - `departments/sales`
   - `departments/marketing`
   - `departments/customer-support`
   - `departments/hr`
   - `departments/operations`
   - `departments/finance`
   - `departments/leadership`
   - `general/...` when it is a shared tool or cross-functional capability
3. Create the skill folder using lowercase hyphen-case
4. Add `SKILL.md` with valid YAML frontmatter containing only:
   - `name`
   - `description`
5. Write `SKILL.md` with these sections unless there is a strong reason not to:
   - `## Output requirements`
   - `## Working method`
   - `## References`
6. Add `references/examples.md`
   - Include Thai example inputs and outputs
   - Include a reusable prompt pattern when helpful
7. Update browse surfaces
   - category `README.md`
   - main `README.md` if the skill should be visible there
8. Add a short one-line description anywhere the skill is listed in the main README
9. Check consistency with the rest of the repo
   - tone
   - naming
   - Thai-first usability
   - no unnecessary jargon

## Decision rules

Prefer the smallest useful addition.

Do not add a new skill when:
- it is too narrow or rarely useful
- it duplicates an existing internal skill
- an external skill already solves the problem better with no Thai-business adaptation needed
- the task is better handled by a category README note instead of a full skill

Prefer adding a real skill when:
- the task is common in Thai business work
- the output benefits from Thai wording or business tone
- users would likely copy and reuse it repeatedly
- it helps non-technical users get better AI results with less effort

## Repo-specific guidance

For this repository:
- Human-facing docs should remain Thai-first
- Example inputs and outputs should usually be in Thai
- Generated output should usually be instructed to be in Thai unless the use case clearly requires English
- Keep README copy user-facing
- Keep maintainer logic in `CONTRIBUTING.md` or this skill, not in the public README surface

## References

Read these before or during implementation as needed:
- `references/checklist.md`
- `references/examples.md`
