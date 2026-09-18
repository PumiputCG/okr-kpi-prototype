# OKR-KPI — UI Prototype

**TH:** ต้นแบบหน้าจอ OKR-KPI หน้าเดียวจบ ใช้คุยกับผู้ใช้ก่อนลงมือเขียนระบบจริง
**EN:** A single-file UI prototype for the OKR-KPI system — built to have a conversation with users before writing any real code.

`HTML5` · `CSS3` · `Vanilla JavaScript` · `Sarabun`

---

## 🇹🇭 ภาษาไทย

### ทำไมถึงทำแบบนี้

ก่อนจะเขียนระบบ OKR-KPI ตัวจริงด้วย Laravel ผมทำหน้าจอต้นแบบขึ้นมาก่อนเป็นไฟล์ HTML ไฟล์เดียว เปิดจากเบราว์เซอร์ได้เลย ไม่ต้องติดตั้งอะไร

เหตุผลง่ายๆ คือ — อธิบายด้วยปากว่า "ตารางจะหน้าตาประมาณนี้" ไม่เคยได้ผล แต่ส่งไฟล์ให้กดเล่นเอง 5 นาที ได้ feedback กลับมาทันที และแก้ตอนนั้นถูกกว่าแก้ตอนเขียนโค้ดจริงไปแล้วมาก

### สิ่งที่ได้จากต้นแบบนี้

- ตกลงโครงสร้างตารางและลำดับคอลัมน์ได้ก่อนออกแบบฐานข้อมูล
- เห็นว่าผู้ใช้สับสนตรงไหนตั้งแต่ยังไม่มีโค้ดหลังบ้าน
- ใช้เป็นข้อตกลงหน้าตาระหว่างทีมกับผู้ใช้

ระบบตัวจริงอยู่ที่ repo **okr-kpi-system**

### ดูยังไง

เปิด `index.html` ด้วยเบราว์เซอร์ เท่านั้น — ไม่ต้อง build ไม่ต้องติดตั้ง

---

## 🇬🇧 English

### Why build it this way

Before writing the real OKR-KPI system in Laravel, I built the screens as one standalone HTML file that opens directly in a browser with nothing to install.

The reasoning is simple: describing a table out loud never works. Handing someone a file they can click around for five minutes gets you real feedback immediately — and changing your mind at that point costs almost nothing compared to changing it after the code is written.

### What it settled

- The table structure and column order, agreed before the database was designed
- Where users got confused, discovered with no backend in existence
- A shared visual contract between the team and its users

The production system lives in the **okr-kpi-system** repository.

### Viewing it

Open `index.html` in a browser. That's the whole setup.
