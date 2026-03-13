## ⚡️ The Complete Prompt Engineering for AI Bootcamp (2026): [Section 5 : Standard Text Model Practice]
---
## 🧠 1 Big idea
- ✨ การ promp ให้ได้ผลลัพท์ที่ดีที่สุดควรจะคำนึงถึงหลักการ 5 ข้อ template เป็นพื้นฐาน การนำเทคนิคการเพิ่ม role ใน propm จะช่วยให้ได้ผลลัพท์ที่ตรงกับที่ต้องการมากขึ้น
--- 
## 🎯 2 Keyterm
- Persona/ELI5 สวมบทบาท (Role) หรือสั่งให้ "อธิบายเหมือน 5 ขวบ" เพื่อปรับระดับเนื้อหา
- Output Control กำหนด Format (JSON/MD) และความยาว (Length) ให้ชัดเจน
---
## 🛠️ 3 What changed in my thinkinng 
- เปลี่ยนมุมมองวิธีในการ promp ให้ได้ผลลัพท์จากแต่ก่อนจะเป็นการ promp กว้างๆ ให้เฉพาะเจาะจงมากขึ้นเช่น การใช้ technic ต่าง ๆ เช่น [Roles in Prompts](https://learnprompting.org/docs/basics/roles)
```
ช่วยอธิบายเกี่ยวกับ Axios CVE-2025-27152 Detail
```
✅
```
Act as a Senior Backend Developer and Security Researcher.  (Direction/Role)
Task: ช่วยอธิบายช่องโหว่ Axios CVE-2025-27152 โดยเน้นผลกระทบที่เกิดขึ้นกับ NestJS Framework version 10 
Requirements:
อธิบาย Root Cause ของช่องโหว่นี้แบบกระชับ (Technical Breakdown)  (Divide Labor)
บอกวิธี Remediation หรือการ Patch ในโปรเจกต์ NestJS  (Evaluate Quality - คุมเนื้อหาที่จำเป็น)

Provide Unit Test: ขอตัวอย่างโค้ดโดยใช้ Jest เพื่อจำลอง Attack Vector และพิสูจน์ว่า Patch แล้ว (Fix Verification)  (Specific Format)
```
---
## 🛠️ 4 Summary of prompts I created
- ใช้หลักการกำหนด 5 ข้อ template 
  การกำหนด role "Act as a Senior Backend Developer and Security Researcher" เพื่ือให้ได้ผลลัพท์ที่ตรงกับงานของเรา อธิบาย task สิ่งที่ต้องการ ใช้การบอกให้แยก task ออกมาเป็นส่วนๆ เช่นอธิบาย rootcase / provide unnit test
---
## 🗂️ 🔗 Resources & Docs
  - 🧠 [AI Prompt Database](https://brightpool.notion.site/fe947b16fe894c3e8a8a19a6b81aec2c?v=95d47a12393a43a79690d74aad38fd7b)
  - 💻 [Source code used in the course](https://github.com/BrightPool/udemy-prompt-engineering-course)
  - 📚 [AI Resource Hub](https://docs.google.com/spreadsheets/d/1IQ3VVwphfuvOFMpdjWbz8ZZzwxCfEFAVqpqEBUNViaM/edit?pli=1&gid=1314763676#gid=1314763676)

--- 