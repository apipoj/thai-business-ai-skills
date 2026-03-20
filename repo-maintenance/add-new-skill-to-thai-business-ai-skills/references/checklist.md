# Checklist - Add New Skill to Thai Business AI Skills

## Before creating the skill

- Is this a real recurring business task?
- Is it useful for Thai users specifically?
- Should this be original, external reference, or wrapper?
- Does a similar skill already exist in the repo?
- Is the category choice correct?

## Files to create

```text
skill-name/
├── SKILL.md
└── references/
    └── examples.md
```

## SKILL.md checklist

- Has `name` and `description` frontmatter
- Description explains both what the skill does and when to use it
- Includes `## Output requirements`
- Includes `## Working method`
- Includes `## References`
- Tells the agent to produce Thai output when appropriate
- Avoids unnecessary explanation

## examples.md checklist

- Includes Thai example input
- Includes Thai example output
- Includes reusable prompt pattern when useful
- Is short enough to stay readable

## README checklist

- Category README updated
- Main README updated if this is a featured or browse-worthy skill
- One-line description added where the skill is linked

## Final quality check

- Naming is consistent
- Folder is hyphen-case
- Tone is practical and not fluffy
- Language is simple enough for non-technical users
- No duplicated internal guidance in public README
