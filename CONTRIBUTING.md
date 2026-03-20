# Contributing

ขอบคุณที่ช่วยพัฒนา Thai Business AI Skills

เป้าหมายของ repo นี้คือทำให้ **คนทำงานไทยที่ไม่ technical** ใช้ AI ได้ง่ายขึ้นในงานจริง ดังนั้นทุก contribution ควรยึดหลักนี้ก่อนเสมอ

## หลักการสำคัญ

- ภาษาไทยก่อน
- ใช้ง่ายก่อน
- งานจริงก่อน
- ไม่เขียนให้ดูฉลาดเกินจำเป็น
- ถ้ามีของดีอยู่แล้ว ให้ลิงก์แทนการเขียนใหม่

## Skill แบบไหนที่ควรเพิ่ม

ควรเป็น skill ที่:
- ใช้ในงานธุรกิจจริงบ่อย
- คนทั่วไปเข้าใจได้
- ลดเวลางานที่ซ้ำ ๆ หรือคิดยาก
- ใช้กับ Claude / ChatGPT / Gemini ได้
- ไม่ต้องมีพื้นฐาน technical สูง

ตัวอย่างที่ดี:
- เขียนข้อความติดตามลูกค้า
- สรุปประชุมพร้อม action items
- เขียน FAQ จากคำถามที่ถามบ่อย
- เขียน SOP จากขั้นตอนงาน

ตัวอย่างที่ยังไม่ควรรีบเพิ่ม:
- skill ที่เฉพาะทางเกินไป
- skill ที่ซ้ำกับของภายนอกแบบแทบไม่ต่าง
- skill ที่ต้อง setup ซับซ้อนมาก
- skill ที่อ่านยากหรือใช้ยากสำหรับคนทั่วไป

## รูปแบบมาตรฐาน

รายละเอียดเชิง maintainer ที่ย้ายออกมาจาก `README.md` อยู่ในไฟล์นี้ เพื่อให้หน้า README หลักเน้นผู้ใช้งานทั่วไปมากกว่า

หากต้องการให้ agent หรือ contributor เพิ่ม skill ใหม่ตามมาตรฐานของ repo นี้ ให้ใช้ skill นี้เป็นตัวนำทาง:

- `repo-maintenance/add-new-skill-to-thai-business-ai-skills/SKILL.md`

ใช้โครงสร้างนี้:

```text
skill-name/
├── SKILL.md
└── references/
    └── examples.md
```

### SKILL.md
ต้องมี YAML frontmatter:

```md
---
name: skill-name
description: Explain what the skill does and when it should be used.
---
```

และเนื้อหาควรเป็น:
- agent-facing
- สั้นและชัด
- ไม่ยาวเกินจำเป็น

### references/examples.md
ใช้เก็บ:
- ตัวอย่าง input
- ตัวอย่าง output
- prompt pattern
- note เสริมที่ไม่ควรยัดใน `SKILL.md`

## กฎการเขียน

### ภาษา
- ใช้ภาษาไทยเป็นหลัก
- ถ้าจำเป็นต้องมีอังกฤษ ให้ใช้เท่าที่จำเป็น
- เลี่ยง jargon ถ้าคนธุรกิจทั่วไปไม่จำเป็นต้องรู้

### โทน
ควรเป็น:
- ชัด
- ตรง
- อ่านง่าย
- ใช้ได้จริง

ไม่ควรเป็น:
- ฟุ้ง
- เทคนิคจ๋า
- ยาวโดยไม่จำเป็น
- อวด prompt engineering

### Naming
- ชื่อ folder ใช้ lowercase + hyphen
- ชื่อใน frontmatter ควรสั้นและสื่อความหมาย
- ถ้าเป็น Thai business skill ให้ขึ้นต้นด้วย `thai-` เมื่อเหมาะสม

## เลือกว่าจะ “เขียนใหม่” หรือ “ลิงก์”

ใช้กฎนี้:
- ถ้ามี skill ต้นฉบับที่ดีอยู่แล้ว → ลิงก์
- ถ้าต้องแปลให้เข้ากับธุรกิจไทย → ทำ wrapper
- ถ้าเป็น workflow ไทยโดยตรง → เขียน original skill

## Checklist ก่อนส่ง PR

- [ ] skill นี้ใช้กับงานจริงได้บ่อยพอ
- [ ] ภาษาไทยอ่านง่าย
- [ ] `SKILL.md` เป็นมาตรฐานและไม่ยาวเกินไป
- [ ] มี `references/examples.md`
- [ ] ไม่มีข้อมูลมั่วหรือเดาเกินจริง
- [ ] ถ้ามี external skill ที่ดีกว่า ได้พิจารณา link แล้ว
- [ ] README หรือหมวดที่เกี่ยวข้องถูกอัปเดตแล้ว

## หมายเหตุ

repo นี้เน้นคุณภาพมากกว่าปริมาณ

เพิ่มช้าได้ แต่ต้องอ่านง่าย ใช้จริงได้ และเหมาะกับธุรกิจไทย


## Skill demand and pain-point research

ก่อนเพิ่ม skill ใหม่ ควรอ้างอิง pain point หลักของธุรกิจจากไฟล์นี้ด้วย:

- `repo-maintenance/add-new-skill-to-thai-business-ai-skills/references/pain-point-index.md`
