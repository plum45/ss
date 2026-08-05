# เว็บสรุปวิชาครู 5 มาตรฐาน

โปรเจกต์นี้เป็นเว็บ Static HTML พร้อมอัปขึ้น Vercel ได้ทันที

## วิธีขึ้น Vercel

1. แตกไฟล์ ZIP นี้
2. เข้า [Vercel](https://vercel.com/new)
3. เลือก **Upload** แล้วอัปโหลดทั้งโฟลเดอร์นี้ หรืออัปขึ้น GitHub ก่อนแล้วกด Import
4. กด Deploy โดยไม่ต้องตั้งค่า Build Command หรือ Output Directory

หน้าเริ่มต้นคือ `index.html` และหน้าเนื้อหาแยกเป็น `standard-1.html` ถึง `standard-5.html`.

สถานะ “อ่านเสร็จแล้ว” และ “ทบทวนภายหลัง” ถูกบันทึกไว้ในเบราว์เซอร์ของผู้ใช้แต่ละเครื่อง
จึงไม่ต้องมีฐานข้อมูลหรือ Environment Variables.
