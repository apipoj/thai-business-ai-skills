---
name: thai-meeting-summary-action-items
description: Summarize Thai or mixed-language meeting notes, transcripts, or rough bullets into a clear Thai meeting summary with decisions, action items, and follow-ups. Use when the user needs meeting output that is easier to read, share, or send to a team.
---

# Thai Meeting Summary with Action Items

Turn messy meeting content into a clean Thai summary for business use.

## Output requirements

- Write in Thai
- Prioritize clarity over completeness theater
- Separate facts, decisions, action items, and open questions
- Do not invent owners, deadlines, or decisions when not present
- Explicitly mark unclear items as unclear

## Working method

1. Identify the meeting topic and context
2. Extract the main points discussed
3. Separate confirmed decisions from suggestions
4. Extract action items and owners when available
5. Note unresolved items or dependencies

## Default output structure

Use this structure unless the user asks otherwise:
1. short overall summary
2. key discussion points
3. decisions made
4. action items
5. pending follow-ups

## Action item rules

For each action item, include when possible:
- task
- owner
- due date
- dependency or blocker

If owner or date is missing, state that it was not specified.

## Tone guidance

- concise
- readable by non-technical teams
- suitable to forward internally
- avoid decorative language

## References

For examples and a reusable end-user prompt pattern, see `references/examples.md`.
