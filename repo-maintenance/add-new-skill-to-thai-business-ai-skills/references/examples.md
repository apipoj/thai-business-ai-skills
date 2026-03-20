# Examples - Add New Skill to Thai Business AI Skills

## Example request
เพิ่ม skill ใหม่ชื่อ “เขียนข้อความขอข้อมูลเพิ่มเติมจากลูกค้า” ลงในหมวด sales โดยให้เหมาะกับธุรกิจไทย ใช้มาตรฐานเดียวกับ skill อื่นใน repo นี้ และอัปเดต README ที่เกี่ยวข้องด้วย

## Expected behavior

1. ตรวจว่าควรเป็น original skill หรือไม่
2. เลือก path ที่เหมาะสม เช่น:
   - `departments/sales/skill-request-more-customer-info-th/`
3. สร้างไฟล์:
   - `SKILL.md`
   - `references/examples.md`
4. เขียน frontmatter และ sections ให้ตรงมาตรฐาน
5. อัปเดต `departments/sales/README.md`
6. อัปเดต `README.md` ถ้าควรแสดงใน browse surface
7. เพิ่มคำอธิบายสั้น ๆ ข้างลิงก์ใน README

## Example prompt pattern
ช่วยเพิ่ม skill ใหม่เข้า repo Thai Business AI Skills โดยทำตามกฎของ repo นี้

ข้อมูลมีดังนี้:
- ชื่อ skill: ...
- งานที่ skill นี้ช่วย: ...
- หมวดที่คาดว่าเหมาะ: ...
- ต้องการให้เป็น original skill / wrapper / external reference: ...
- ควรเพิ่มใน README หลักหรือไม่: ...

เงื่อนไข:
- ใช้มาตรฐานเดียวกับ skill อื่นใน repo
- `SKILL.md` ต้องเป็น agent-facing
- `references/examples.md` ต้องมีตัวอย่างภาษาไทย
- อัปเดต README ที่เกี่ยวข้อง
- ถ้า skill นี้ไม่ควรมี ให้บอกเหตุผลตรง ๆ
