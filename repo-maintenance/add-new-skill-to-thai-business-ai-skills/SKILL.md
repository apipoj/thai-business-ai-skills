---
name: add-new-skill-to-thai-business-ai-skills
description: Add a new skill to the Thai Business AI Skills repository in the correct format and location. Use when creating, reviewing, or integrating a new skill for this repo, including deciding whether to write an original skill, link an external skill, create a Thai business wrapper, or reject a duplicate.
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

1. Define the real job-to-be-done
   - State what task the user is trying to complete
   - State what output the skill should produce
   - State which business pain point it reduces
2. Generate keyword variants before checking the repo
   - Thai direct phrase
   - Thai alternative phrase
   - English direct phrase
   - English alternative phrase
   - broader business function
   - neighboring task names
3. Check for duplicates before creating anything
   - Search folder names
   - Search `name:` in frontmatter
   - Search `description:` text
   - Search main `README.md`
   - Search category `README.md`
   - Search `references/examples.md` in nearby skills when necessary
4. Decide the right outcome
   - create a new original skill
   - expand an existing skill
   - add a new example/use case to an existing skill
   - link an external skill
   - reject the request as duplicate or too narrow
5. Choose the correct category
   - `departments/sales`
   - `departments/marketing`
   - `departments/customer-support`
   - `departments/hr`
   - `departments/operations`
   - `departments/finance`
   - `departments/leadership`
   - `general/...` when it is a shared tool or cross-functional capability
6. Create the skill folder using lowercase hyphen-case
7. Add `SKILL.md` with valid YAML frontmatter containing only:
   - `name`
   - `description`
8. Write `SKILL.md` with these sections unless there is a strong reason not to:
   - `## Output requirements`
   - `## Working method`
   - `## References`
9. Add `references/examples.md`
   - Include Thai example inputs and outputs
   - Include a reusable prompt pattern when helpful
10. Update browse surfaces
   - category `README.md`
   - main `README.md` if the skill should be visible there
11. Add a short one-line description anywhere the skill is listed in the main README
12. Check consistency with the rest of the repo
   - tone
   - naming
   - Thai-first usability
   - no unnecessary jargon

## Duplicate decision rules

Treat the new request as a duplicate or near-duplicate when:
- it produces almost the same output as an existing skill
- it differs mainly by wording, not by job-to-be-done
- it is only one scenario of a broader existing skill

Prefer adding an example to an existing skill when:
- the new request is a common sub-case of an existing skill
- the user would benefit more from a stronger example than from a new folder

Prefer a wrapper when:
- the base capability exists elsewhere
- the missing piece is Thai business language, tone, or workflow adaptation

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
- Keep maintainer logic in `CONTRIBUTING.md`, this skill, or `repo-maintenance/`, not in the public README surface

## References

Read these before or during implementation as needed:
- `references/checklist.md`
- `references/examples.md`
- `references/pain-point-index.md`
