# Enterprise Web NAS Server

## วิธีติดตั้งและเริ่มใช้งาน

### วิธีที่ 1: ติดตั้งและรันแบบ 1-Click (แนะนำสำหรับ Windows)
1. ดับเบิลคลิกไฟล์ **`install.bat`** (สคริปต์จะตรวจสอบและติดตั้ง Node.js LTS, dependencies ทุกตัว, และเตรียมโฟลเดอร์ให้โดยอัตโนมัติ)
2. เมื่อติดตั้งเสร็จ สามารถเลือกเริ่มใช้งานได้ทันที หรือดับเบิลคลิกไฟล์ **`start.bat`** เพื่อเปิดเซิร์ฟเวอร์ในครั้งต่อไป

### วิธีที่ 2: รันผ่าน Terminal / Command Prompt
1. เปิด Command Prompt หรือ PowerShell ในโฟลเดอร์นี้
2. รันคำสั่งติดตั้ง Dependencies:

   npm install

3. รันระบบ:

   npm start

## คุณสมบัติในระบบ
- **Server Control Panel (Electron):** หน้าต่างจัดการเซิร์ฟเวอร์, เลือกไดรฟ์จริงในเครื่อง, กำหนด Port, ดู Log สด
- **Database (SQLite):** ตาราง Users, Password Hash, สิทธิ์ Read/Write, ตั้งค่าสีและไดรฟ์
- **Web Portal:** หน้าล็อกอินแบบ Split-Screen (ซ้ายฟอร์ม ขวาสไลด์โชว์)
- **Built-in Media Player:** เล่นวิดีโอ (MP4, MKV, WebM) และเพลง (MP3, WAV) ได้ทันที
- **Built-in Text Editor:** เปิดอ่านและกดแก้ไข/บันทึกไฟล์ข้อความ (.txt, .js, .json, .html, .css, .md, .sql) ได้ทันที
- **Auto Launch:** เปิดหน้าเว็บในบราวเซอร์อัตโนมัติเมื่อสั่ง start
