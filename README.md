# ควิซ Game Design (13 บท · 212 ข้อ · 5 ตัวเลือก ก–จ)

เว็บ static ไม่ต้อง build — เปิด `index.html` ได้เลย หรือขึ้น GitHub Pages

## ขึ้น GitHub Pages
1. สร้าง repo แล้วอัปโหลดทั้งโฟลเดอร์ (`index.html` + `data/`)
2. Settings → Pages → Branch: `main` / root → Save
3. เปิด `https://<username>.github.io/<repo>/`

## แก้/เพิ่มข้อสอบ
แต่ละบทอยู่ใน `data/wNN.js` รูปแบบข้อ:
`[โจทย์, [ตัวเลือกถูก, ผิด1..ผิด4], [เหตุผลถูก, เหตุผลผิด1..ผิด4]]`
(ตัวเลือกถูกอยู่ลำดับแรกเสมอ — เว็บสุ่มตำแหน่งให้เองทุกครั้ง)
