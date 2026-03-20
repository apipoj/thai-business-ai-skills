# Thai Business AI Skills

![Thai Business AI Skills Banner](assets/repo-banner.png)

คลังรวม **AI Skills สำหรับธุรกิจไทย** ที่เน้น **ภาษาไทย, ใช้ง่าย, ไม่ technical, คัดลอกแล้วใช้ได้เลย**

ใช้ได้กับ:
- Claude
- ChatGPT
- Gemini
- AI tools อื่น ๆ ที่รับ prompt หรือ import skill ได้

> เป้าหมายของ repo นี้คือทำให้คนทำงานไทยใช้ AI ได้ง่ายขึ้นในงานจริง ไม่ต้องเรียน prompt engineering ก่อน

---

## ทำไม repo นี้ถึงมีอยู่

คนทำธุรกิจไทยส่วนใหญ่:
- งานเยอะ
- ไม่อยากอ่านอะไรยาว
- ไม่ technical
- อยากได้ของที่ **เปิดแล้วใช้ได้เลย**

ดังนั้น skill ใน repo นี้จะพยายามเป็นแบบนี้:
- **ภาษาไทยก่อน**
- **สั้น ชัด ใช้งานได้จริง**
- **มี prompt พร้อมใช้**
- **มีตัวอย่าง**
- **ลดภาระการคิดของผู้ใช้**

---

## Contents

- [Start Here](#start-here)
- [How to Use](#how-to-use)
- [Featured Skills](#featured-skills)
- [Browse by Department](#browse-by-department)
  - [Sales](#sales)
  - [Marketing](#marketing)
  - [Customer Support](#customer-support)
  - [HR](#hr)
  - [Operations](#operations)
  - [Finance](#finance)
  - [Leadership](#leadership)
- [Browse by Common Tools](#browse-by-common-tools)
  - [Meetings](#meetings)
  - [PowerPoint](#powerpoint)
  - [Excel](#excel)
  - [Word / Docs](#word--docs)
  - [Email](#email)
  - [Research](#research)
  - [Translation / Localization](#translation--localization)
- [External Recommended Skills](#external-recommended-skills)
- [Who This Repo Is For](#who-this-repo-is-for)
- [Important Cautions](#important-cautions)
- [License](#license)

---

## Start Here

ถ้าคุณเพิ่งเข้ามาใน repo นี้ ให้เริ่มจาก:
- ฝ่ายขาย: [เขียนข้อความติดตามลูกค้า](departments/sales/skill-follow-up-message-th/SKILL.md) / [คัดกรอง lead เบื้องต้น](departments/sales/skill-lead-qualification-th/SKILL.md)
- การตลาด: [เขียนโพสต์โปรโมตสินค้า/บริการ](departments/marketing/skill-thai-marketing-post/SKILL.md) / [คิดไอเดียคอนเทนต์ 30 วัน](departments/marketing/skill-content-calendar-30-days-th/SKILL.md)
- บริการลูกค้า: [ตอบลูกค้าร้องเรียนอย่างสุภาพ](departments/customer-support/skill-thai-complaint-reply/SKILL.md) / [สรุปปัญหาจากแชทลูกค้าเป็น ticket summary](departments/customer-support/skill-ticket-summary-from-chat-th/SKILL.md)
- HR: [เขียน JD แบบเข้าใจง่าย](departments/hr/skill-thai-jd-writer/SKILL.md) / [สร้างคำถามสัมภาษณ์ตามตำแหน่งงาน](departments/hr/skill-interview-questions-by-role-th/SKILL.md)
- Meetings: [สรุปประชุมพร้อม Action Items](general/meetings/skill-meeting-summary-action-items-th/SKILL.md)
- ผู้บริหาร: [สรุปรายงานให้ผู้บริหารอ่านง่าย](departments/leadership/skill-exec-summary/SKILL.md)
- PowerPoint: [ช่วยทำโครงสไลด์นำเสนอ](general/powerpoint/skill-presentation-outline/SKILL.md)

---

## How to Use

### แบบที่ 1: ใช้เป็น prompt ธรรมดา
1. เปิดไฟล์ `SKILL.md`
2. อ่านหรือคัดลอกแนวทางหลัก
3. ถ้าต้องการตัวอย่าง ให้เปิด `references/examples.md`
4. ใส่ข้อมูลของคุณ
5. ส่งเข้า Claude / ChatGPT / Gemini
6. ตรวจทานก่อนใช้งานจริง

### แบบที่ 2: ใช้กับระบบที่ import skill ได้
repo นี้พยายามใช้โครงสร้างแบบ standard skill:
- `.../skill-name/SKILL.md`
- `.../skill-name/references/...`

โดย:
- `SKILL.md` = ไฟล์หลักสำหรับ import / อ้างอิง
- `references/` = ตัวอย่าง, prompt pattern, หรือข้อมูลเสริม

---

## Featured Skills

สกิลเด่นที่เหมาะกับการเริ่มต้นใช้งาน:

- [เขียนข้อความติดตามลูกค้า](departments/sales/skill-follow-up-message-th/SKILL.md) — ช่วยติดตามลูกค้าแบบสุภาพ ไม่กดดัน
- [เขียนโพสต์โปรโมตสินค้า/บริการ](departments/marketing/skill-thai-marketing-post/SKILL.md) — ช่วยทำโพสต์การตลาดภาษาไทยแบบใช้งานได้จริง
- [ตอบลูกค้าร้องเรียนอย่างสุภาพ](departments/customer-support/skill-thai-complaint-reply/SKILL.md) — ช่วยลดความตึงเครียดและตอบอย่างมืออาชีพ
- [เขียน JD แบบเข้าใจง่าย](departments/hr/skill-thai-jd-writer/SKILL.md) — ช่วยให้ประกาศรับสมัครชัดเจนขึ้น
- [สรุปประชุมพร้อม Action Items](general/meetings/skill-meeting-summary-action-items-th/SKILL.md) — ช่วยทำสรุปประชุมพร้อมส่งต่อทีม
- [สรุปรายงานให้ผู้บริหารอ่านง่าย](departments/leadership/skill-exec-summary/SKILL.md) — ช่วยย่อยรายงานให้สั้นและคม
- [ช่วยทำโครงสไลด์นำเสนอ](general/powerpoint/skill-presentation-outline/SKILL.md) — ช่วยคิด flow ก่อนลงมือทำ deck

---

## Browse by Department

### Sales
- [หน้ารวม Sales Skills](departments/sales/README.md)
- [เขียนข้อความติดตามลูกค้า](departments/sales/skill-follow-up-message-th/SKILL.md)
- [คัดกรอง lead เบื้องต้น](departments/sales/skill-lead-qualification-th/SKILL.md)
- [สรุป discovery call สำหรับทีมขาย](departments/sales/skill-discovery-call-summary-th/SKILL.md)
- [ตอบ objection ลูกค้าแบบสุภาพ](departments/sales/skill-objection-handling-th/SKILL.md)

### Marketing
- [หน้ารวม Marketing Skills](departments/marketing/README.md)
- [เขียนโพสต์โปรโมตสินค้า/บริการ](departments/marketing/skill-thai-marketing-post/SKILL.md)
- [คิดไอเดียคอนเทนต์ 30 วัน](departments/marketing/skill-content-calendar-30-days-th/SKILL.md)
- [เขียนแคปชันหลายเวอร์ชันตามโทน](departments/marketing/skill-caption-variants-th/SKILL.md)

### Customer Support
- [หน้ารวม Customer Support Skills](departments/customer-support/README.md)
- [ตอบลูกค้าร้องเรียนอย่างสุภาพ](departments/customer-support/skill-thai-complaint-reply/SKILL.md)
- [สรุปปัญหาจากแชทลูกค้าเป็น ticket summary](departments/customer-support/skill-ticket-summary-from-chat-th/SKILL.md)
- [เขียน FAQ จากคำถามที่ถามบ่อย](departments/customer-support/skill-faq-from-repeated-questions-th/SKILL.md)

### HR
- [หน้ารวม HR Skills](departments/hr/README.md)
- [เขียน JD แบบเข้าใจง่าย](departments/hr/skill-thai-jd-writer/SKILL.md)
- [สร้างคำถามสัมภาษณ์ตามตำแหน่งงาน](departments/hr/skill-interview-questions-by-role-th/SKILL.md)

### Operations
- [หน้ารวม Operations Skills](departments/operations/README.md)
- [เขียนประกาศหรือข้อความภายในทีม](departments/operations/skill-internal-announcement-th/SKILL.md)
- [เขียน SOP เบื้องต้นจากขั้นตอนงาน](departments/operations/skill-sop-draft-th/SKILL.md)

### Finance
- [หน้ารวม Finance Skills](departments/finance/README.md)
- [สรุปค่าใช้จ่ายแบบเข้าใจง่าย](departments/finance/skill-expense-summary-th/SKILL.md)
- [เขียนข้อความติดตามการชำระเงินอย่างสุภาพ](departments/finance/skill-payment-reminder-th/SKILL.md)
- [สรุปรายงานตัวเลขสำหรับผู้จัดการหรือผู้บริหาร](departments/finance/skill-management-report-summary-th/SKILL.md)

### Leadership
- [หน้ารวม Leadership Skills](departments/leadership/README.md)
- [สรุปรายงานให้ผู้บริหารอ่านง่าย](departments/leadership/skill-exec-summary/SKILL.md)
- [เขียน decision memo แบบกระชับ](departments/leadership/skill-decision-memo-th/SKILL.md)
- [สรุป weekly management update](departments/leadership/skill-weekly-management-update-th/SKILL.md)

---

## Browse by Common Tools

### Meetings
- [หน้ารวม Meeting Skills](general/meetings/README.md)
- [สรุปประชุมพร้อม Action Items](general/meetings/skill-meeting-summary-action-items-th/SKILL.md)

### PowerPoint
- [หน้ารวม PowerPoint Skills](general/powerpoint/README.md)
- [ช่วยทำโครงสไลด์นำเสนอ](general/powerpoint/skill-presentation-outline/SKILL.md)
- [Anthropic pptx skill](https://github.com/anthropics/skills/tree/main/skills/pptx)

### Excel
- [หน้ารวม Excel Skills](general/excel/README.md)
- [Anthropic xlsx skill](https://github.com/anthropics/skills/tree/main/skills/xlsx)

### Word / Docs
- [หน้ารวม Word / Docs Skills](general/word-docs/README.md)
- [Anthropic docx skill](https://github.com/anthropics/skills/tree/main/skills/docx)

### Email
- [หน้ารวม Email Skills](general/email/README.md)
- [ตอบอีเมลธุรกิจอย่างมืออาชีพ](general/email/skill-professional-email-reply-th/SKILL.md)

### Research
- [หน้ารวม Research Skills](general/research/README.md)

### Translation / Localization
- [หน้ารวม Translation / Localization Skills](general/translation-localization/README.md)

---

## External Recommended Skills

ถ้าคุณต้องการใช้งานด้านเอกสาร ไฟล์ หรือสเปรดชีตโดยตรง สามารถเริ่มจาก skill ต้นฉบับเหล่านี้ได้เลย:

- Excel / xlsx → [Anthropic xlsx skill](https://github.com/anthropics/skills/tree/main/skills/xlsx)
- PowerPoint / pptx → [Anthropic pptx skill](https://github.com/anthropics/skills/tree/main/skills/pptx)
- Word / docx → [Anthropic docx skill](https://github.com/anthropics/skills/tree/main/skills/docx)
- PDF → [Anthropic pdf skill](https://github.com/anthropics/skills/tree/main/skills/pdf)

บางส่วนของ repo นี้จะมีตัวอย่างหรือแนวทางเพิ่มเติมสำหรับการนำ skill เหล่านี้ไปใช้ในบริบทธุรกิจไทย

---

## Who This Repo Is For

- เจ้าของธุรกิจ
- ทีมขาย
- ทีมการตลาด
- ทีมบริการลูกค้า
- HR / Admin
- ผู้จัดการและผู้บริหาร
- ฟรีแลนซ์ / ที่ปรึกษา
- ทีมไทยที่อยากใช้ AI ให้ได้งานเร็วขึ้น

---

## Important Cautions

AI ช่วยเร่งงานได้ แต่ไม่ควรใช้แบบไม่ตรวจทาน โดยเฉพาะเรื่อง:
- ข้อมูลลูกค้า
- ข้อมูลการเงิน
- กฎหมาย / สัญญา
- ข้อมูลภายในบริษัท
- การตัดสินใจเชิงธุรกิจที่มีผลกระทบสูง

---

## License

MIT
