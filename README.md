คุณกำลังทำงานใน GitHub Repo: thanabartb-ops/W

เป้าหมาย:
ซ่อมหน้า GitHub Pages ให้ใช้ W//FORGE Control Center เป็นหน้าแรก โดยเก็บไฟล์เดิมทั้งหมดอย่างปลอดภัย

ดำเนินการรวดเดียวตามลำดับนี้:

1. ตรวจสอบว่า Repo ปัจจุบันคือ `thanabartb-ops/W`
2. ดึงสถานะล่าสุดจาก Branch `main`
3. สร้าง Branch ใหม่ชื่อ:
   `thanabartb-ops-patch-1`

4. ตรวจไฟล์ต่อไปนี้:
   - `index.html`
   - `index-15.html`
   - โฟลเดอร์ `assets/`
   - ไฟล์ ZIP ทั้งหมด

5. สำรอง `index.html` เดิมโดยคัดลอกไปที่:
   `archive/index-bank-contour-v0.1.html`

6. ถ้า `index-15.html` เป็นหน้า W//FORGE ONE — BANK VISUAL DNA CONTROL SITE:
   - คัดลอกเนื้อหาทั้งหมดของ `index-15.html`
   - ใช้แทนเนื้อหาใน `index.html`

7. ห้ามลบ:
   - `index-15.html`
   - `assets/`
   - ไฟล์ ZIP
   - ไฟล์ข้อมูลเดิม
   - Repo อื่น
   - ประวัติ Git

8. ห้าม Redesign
9. ห้ามเพิ่ม API Key หรือ Secret ลงใน Client-side
10. ห้ามเปิด Render Gate
11. ห้ามเพิ่มระบบสร้างภาพลงเว็บไซต์
12. รักษา Dark Premium / Forge Violet / Local-first structure เดิม

13. ตรวจ HTML:
   - ไม่มี syntax error
   - เปิดบนมือถือได้
   - ไม่มี horizontal overflow
   - navigation ใช้งานได้
   - JavaScript ไม่มี error สำคัญ
   - หน้าแรกโหลดได้จาก GitHub Pages

14. ตรวจหา Secret เช่น:
   - `sk-`
   - `xai-`
   - `API_KEY`
   - `OPENAI_API_KEY`
   - token จริง
   ถ้าพบให้หยุดและรายงาน ห้าม Commit Secret

15. Commit ด้วยข้อความ:
   `fix: restore WFORGE control center as GitHub Pages entry`

16. Push Branch:
   `thanabartb-ops-patch-1`

17. เปิด Pull Request ไปยัง `main`

PR Title:
`Restore W//FORGE Control Center as Pages entry`

PR Description:
- Backup original index.html
- Promote existing W//FORGE Control Center to root index.html
- Preserve assets and archived files
- No redesign
- No secrets added
- Render Gate remains locked

18. ตรวจ Diff ของ Pull Request
19. ตรวจ GitHub Pages และ GitHub Actions
20. ห้าม Merge อัตโนมัติ

ทำงานทันทีโดยไม่ถามคำถาม เว้นแต่:
- ไม่มีสิทธิ์เขียน Repo
- ไม่พบ `index-15.html`
- พบ Secret จริง
- ไฟล์ W//FORGE เสียหรือไม่ใช่ HTML ที่ใช้งานได้

เมื่อเสร็จ ให้รายงานเฉพาะ:
- Branch
- Commit SHA
- Pull Request
- Files changed
- Pages status
- PASS หรือ FAIL