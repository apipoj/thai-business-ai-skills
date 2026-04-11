---
name: thai-renewal-expiry-triage
description: Extract expiring subscriptions, credentials, and contracts from messy Thai LINE, email, invoice, or note text, then turn them into a short action list with urgency and next steps.
---

# Renewal / Expiry Triage from Thai Messages

Use this skill when a Thai business operator needs to read a messy renewal notice, vendor message, or internal note and quickly decide what is expiring, how urgent it is, and what to do next.

## When to use

- A LINE message mentions renewal, due dates, expiry, or suspension risk
- An email or invoice contains support / license / domain / SSL / contract dates
- An admin note is too messy to scan manually
- A team member needs a quick expiry summary before handing it to the owner

## What this skill should produce

Return a concise Thai triage summary with:
- the expiry item
- category
- due date or timing
- urgency level
- business impact
- next action

## Categories to look for

Prefer these buckets when relevant:
- SSL / certificate
- domain
- subscription
- support contract
- software license
- credential / password rotation
- vendor agreement
- other renewal item

## Core workflow

1. Read the full text once.
2. Extract every item that looks like it can expire, renew, or lapse.
3. Identify any exact dates, durations, or deadlines.
4. Rank urgency:
   - **critical** = outage, lockout, service stop, or immediate loss risk
   - **soon** = needs action within days / this week
   - **later** = still relevant but not urgent yet
5. Write the next action in plain Thai.
6. If the text is unclear, say what is missing instead of guessing.

## Output format

Use this structure:

- **สรุปเร็ว:** one short Thai sentence
- **รายการที่ต้องทำ:** bullet list of expiry items
  - **ประเภท:**
  - **กำหนด:**
  - **ความเร่งด่วน:**
  - **ผลกระทบ:**
  - **next action:**

## Quality rules

- Do not turn this into a generic summary.
- Do not invent dates.
- Do not over-explain.
- Keep the wording useful for a Thai owner or admin who must act fast.
- If there are no expiry items, say that clearly.

## Good examples of source text

- "แจ้งต่ออายุ SSL หมดอายุ 14 เม.ย. ถ้าไม่ต่อเว็บจะเข้าไม่ได้"
- "Support contract ลูกค้า A หมดอายุสิ้นเดือนนี้ รบกวน confirm renew"
- "Google Workspace 10 users จะครบกำหนดสัปดาห์หน้า"
- "รบกวนเปลี่ยนรหัสผ่าน admin ภายในวันนี้"

## Example output

- **สรุปเร็ว:** พบ 2 รายการที่ต้องต่ออายุภายในสัปดาห์นี้
- **รายการที่ต้องทำ:**
  - **ประเภท:** SSL certificate
    - **กำหนด:** 14 เม.ย. 2026
    - **ความเร่งด่วน:** critical
    - **ผลกระทบ:** เว็บอาจเข้าไม่ได้
    - **next action:** ต่ออายุทันทีและแจ้ง owner
  - **ประเภท:** Subscription
    - **กำหนด:** สัปดาห์หน้า
    - **ความเร่งด่วน:** soon
    - **ผลกระทบ:** ผู้ใช้อาจถูกตัดสิทธิ์
    - **next action:** ยืนยันจำนวน user และต่ออายุ

## Anti-patterns

Avoid outputs that:
- sound like a long report
- focus on marketing language
- ignore the deadline
- merge unrelated notes into one vague paragraph
