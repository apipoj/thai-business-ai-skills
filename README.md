# Thai Business AI Skills

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

## เริ่มจากตรงนี้

### สกิลแนะนำสำหรับคนเริ่มใช้
- ฝ่ายขาย: [เขียนข้อความติดตามลูกค้า](departments/sales/skill-follow-up-message-th/SKILL.md)
- การตลาด: [เขียนโพสต์โปรโมตสินค้า/บริการ](departments/marketing/skill-thai-marketing-post/SKILL.md)
- บริการลูกค้า: [ตอบลูกค้าร้องเรียนอย่างสุภาพ](departments/customer-support/skill-thai-complaint-reply/SKILL.md)
- HR: [เขียน JD แบบเข้าใจง่าย](departments/hr/skill-thai-jd-writer/SKILL.md)
- Meetings: [สรุปประชุมพร้อม Action Items](general/meetings/skill-meeting-summary-action-items-th/SKILL.md)
- ผู้บริหาร: [สรุปรายงานให้ผู้บริหารอ่านง่าย](departments/leadership/skill-exec-summary/SKILL.md)
- PowerPoint: [ช่วยทำโครงสไลด์นำเสนอ](general/powerpoint/skill-presentation-outline/SKILL.md)

### External skills ที่แนะนำ
- Excel / xlsx → [Anthropic xlsx skill](https://github.com/anthropics/skills/tree/main/skills/xlsx)
- PowerPoint / pptx → [Anthropic pptx skill](https://github.com/anthropics/skills/tree/main/skills/pptx)
- Word / docx → [Anthropic docx skill](https://github.com/anthropics/skills/tree/main/skills/docx)
- PDF → [Anthropic pdf skill](https://github.com/anthropics/skills/tree/main/skills/pdf)

> แนวทางของ repo นี้คือ: ถ้าสกิลทั่วไปมีของดีอยู่แล้ว เราจะลิงก์ตรงไปที่ต้นฉบับ แล้วค่อยเพิ่มตัวอย่างและ wrapper สำหรับบริบทธุรกิจไทย

---

## วิธีใช้งาน

### แบบที่ 1: ใช้เป็น prompt ธรรมดา
1. เปิดไฟล์ `SKILL.md`
2. คัดลอก prompt
3. ใส่ข้อมูลของคุณ
4. ส่งเข้า Claude / ChatGPT / Gemini
5. ตรวจทานก่อนใช้งานจริง

### แบบที่ 2: ใช้กับระบบที่ import skill ได้
หลาย repo ยอดนิยมจะลิงก์ตรงไปที่ `SKILL.md` เพื่อให้ user เปิดแล้ว import หรือ copy ได้ทันที

ดังนั้น repo นี้จะพยายามวางไฟล์ในรูปแบบนี้:
- `.../skill-name/SKILL.md`

เพื่อให้:
- เปิดอ่านง่าย
- ลิงก์ตรงง่าย
- import ง่าย
- จัดระเบียบง่าย

---

## Browse by department

### ฝ่ายขาย
- [หน้ารวม Sales Skills](departments/sales/README.md)
- [เขียนข้อความติดตามลูกค้า](departments/sales/skill-follow-up-message-th/SKILL.md)

### การตลาด
- [หน้ารวม Marketing Skills](departments/marketing/README.md)
- [เขียนโพสต์โปรโมตสินค้า/บริการ](departments/marketing/skill-thai-marketing-post/SKILL.md)

### บริการลูกค้า
- [หน้ารวม Customer Support Skills](departments/customer-support/README.md)
- [ตอบลูกค้าร้องเรียนอย่างสุภาพ](departments/customer-support/skill-thai-complaint-reply/SKILL.md)

### HR
- [หน้ารวม HR Skills](departments/hr/README.md)
- [เขียน JD แบบเข้าใจง่าย](departments/hr/skill-thai-jd-writer/SKILL.md)

### Operations
- [หน้ารวม Operations Skills](departments/operations/README.md)

### Finance
- [หน้ารวม Finance Skills](departments/finance/README.md)

### Leadership
- [หน้ารวม Leadership Skills](departments/leadership/README.md)
- [สรุปรายงานให้ผู้บริหารอ่านง่าย](departments/leadership/skill-exec-summary/SKILL.md)

---

## Browse by common tools

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

### Research
- [หน้ารวม Research Skills](general/research/README.md)

### Translation / Localization
- [หน้ารวม Translation / Localization Skills](general/translation-localization/README.md)

---

## ประเภทของเนื้อหาใน repo นี้

### 1) Original ALL-IN-AI Skills
สกิลที่เราเขียนเองเพื่อให้เหมาะกับงานธุรกิจไทยจริง ๆ

### 2) Curated External Skills
สกิลจากแหล่งอื่นที่ดีอยู่แล้ว และควรลิงก์ตรงไปใช้ทันที

### 3) Thai Business Wrappers
คู่มือหรือหน้าสรุปที่ช่วยเอาสกิลทั่วไปมาปรับใช้กับบริบทธุรกิจไทย

---

## รูปแบบมาตรฐานของ skill

แต่ละ skill ควรมี:
- ใช้เมื่อไหร่
- ต้องใส่อะไรบ้าง
- Prompt พร้อมใช้
- ผลลัพธ์ที่ควรได้
- ตัวอย่าง input
- ตัวอย่าง output
- ข้อควรระวัง

Template ดูได้ที่:
- [templates/SKILL_TEMPLATE.md](templates/SKILL_TEMPLATE.md)

---

## แนวทางการคัด skill เข้ามา

เรา **ไม่จำเป็นต้องเขียนทุกอย่างใหม่**

กฎง่าย ๆ คือ:
- ถ้ามี skill ต้นฉบับที่ดีอยู่แล้ว → ลิงก์
- ถ้ายังไม่เหมาะกับคนไทย / ธุรกิจไทย → เขียน wrapper
- ถ้าเป็น workflow ธุรกิจไทยโดยตรง → เขียน original skill

---

## เหมาะกับใคร

- เจ้าของธุรกิจ
- ทีมขาย
- ทีมการตลาด
- ทีมบริการลูกค้า
- HR / Admin
- ผู้จัดการและผู้บริหาร
- ฟรีแลนซ์ / ที่ปรึกษา
- ทีมไทยที่อยากใช้ AI ให้ได้งานเร็วขึ้น

---

## ข้อควรระวัง

AI ช่วยเร่งงานได้ แต่ไม่ควรใช้แบบไม่ตรวจทาน โดยเฉพาะเรื่อง:
- ข้อมูลลูกค้า
- ข้อมูลการเงิน
- กฎหมาย / สัญญา
- ข้อมูลภายในบริษัท
- การตัดสินใจเชิงธุรกิจที่มีผลกระทบสูง

---

## License

MIT
