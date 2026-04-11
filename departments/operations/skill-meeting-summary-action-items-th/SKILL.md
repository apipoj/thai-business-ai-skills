---
name: thai-meeting-summary-action-items
description: Turn Thai meeting notes, chat transcripts, and discovery call notes into a concise executive summary, clear action items, owners, deadlines, and follow-up points.
---

# สรุปประชุมเป็น action items สำหรับผู้บริหารไทย

Use this skill when a Thai founder, team lead, or ops manager needs to turn raw meeting notes into something the team can act on immediately.

## When to use

- After a meeting with messy notes or rough bullets
- After a discovery call, internal sync, client meeting, or voice note transcript
- When decisions were made but owners are unclear
- When someone wants a follow-up summary they can paste into LINE or email

## What this skill should produce

Return a short Thai output with:
- executive summary
- key decisions
- action items
- owner for each action item if known
- due date or timing if mentioned
- blockers / risks
- follow-up message if useful

## Core workflow

1. Read the full notes once.
2. Identify decisions, commitments, and next steps.
3. Separate action items from background discussion.
4. Assign owners only when they are clearly mentioned or strongly implied.
5. Preserve deadlines exactly if they appear in the source.
6. If the notes are incomplete, say what is missing instead of guessing.

## Output format

Use this structure:

- **สรุปเร็ว:** 3–5 lines
- **ตัดสินใจแล้ว:** bullets
- **สิ่งที่ต้องทำต่อ:** bullets with owner / next step / due date
- **ความเสี่ยงหรือจุดค้าง:** bullets
- **ข้อความ follow-up:** optional short Thai message

## Quality rules

- Keep the wording crisp and useful for a Thai manager.
- Do not echo the whole transcript.
- Do not invent owners or deadlines.
- Prefer simple Thai over corporate English unless a technical term is clearer in English.
- If the meeting had no clear action items, say that clearly.

## Good source examples

- Rough meeting bullets
- LINE chat recap after a call
- Voice note transcription
- Discovery call notes

## Anti-patterns

Avoid outputs that:
- read like a generic summary
- mix decisions and action items together
- omit owners when they are present
- turn a meeting into a long paragraph
- sound overly formal or templated
