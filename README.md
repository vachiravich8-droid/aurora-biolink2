# Aurora Bio-Link

เว็บ Luxury Bio-Link พร้อมหลังบ้าน (React + Tailwind ผ่าน CDN) ไฟล์เดียว ไม่ต้อง build

## ขึ้น GitHub
1. สร้าง repository ใหม่ที่ github.com (กด New)
2. กด Add file > Upload files แล้วอัปโหลด `index.html`, `render.yaml`, `README.md`, `.gitignore`
3. กด Commit changes

## ขึ้น Render
1. เข้า render.com > New > Static Site
2. เชื่อม GitHub แล้วเลือก repository นี้
3. Build Command: เว้นว่าง (หรือ `echo ok`)
4. Publish Directory: `.`
5. กด Create Static Site รอสักครู่จะได้ลิงก์ `https://ชื่อ.onrender.com`

(หรือใช้ New > Blueprint ให้ Render อ่านจาก `render.yaml` อัตโนมัติ)

## เข้าหลังบ้าน
เลื่อนลงล่างสุด แตะข้อความ © ท้ายหน้า 5 ครั้งติดกัน หรือเติม `#admin` ท้ายลิงก์

## ข้อควรรู้
- บัญชีและข้อมูลทั้งหมดเก็บใน localStorage ของเบราว์เซอร์ ไม่ใช่ฐานข้อมูลกลาง
- เปลี่ยนโดเมนหรือเปลี่ยนเครื่อง ข้อมูลจะไม่ตามไป ใช้แท็บ "เครื่องมือ" สำรอง/นำเข้าข้อมูลได้
- ต้องต่อเน็ตเพื่อโหลดสคริปต์จาก CDN (React, Tailwind, Babel)
