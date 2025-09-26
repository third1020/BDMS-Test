# BDMS Test Project

วิธีการติดตั้ง

ติดตั้ง Backend (API Server)

To do list (RESTFUL API)
```bash
cd backend
npm install
npm run start:dev
```
API จะทำงานที่ `http://localhost:3000`

```bash
   POST /tasks - สร้างงานใหม่

   GET /tasks - ดูรายการงานทั้งหมด

   GET /tasks/:id - ดูงานรายการเดียว

   PATCH /tasks/:id - อัพเดทงาน

   DELETE /tasks/:id - ลบงาน

   GET /tasks/stats - ดูสถิติงาน

   GET /tasks/overdue - ดูงานที่เกินกำหนด

   GET /tasks/status/:status - ดูงานตามสถานะ

   GET /tasks/priority/:priority - ดูงานตามความสำคัญ

   PATCH /tasks/:id/complete - เปลี่ยนสถานะเป็นเสร็จสิ้น

   PATCH /tasks/:id/in-progress - เปลี่ยนสถานะเป็นกำลังดำเนินการ

   PATCH /tasks/:id/pending - เปลี่ยนสถานะเป็นรอดำเนินการ
```

ติดตั้ง Mobile App(react-native)
```bash
cd react-native
npm install
npx start
```
สแกน QR Code ด้วยแอป Expo Go หรือรันบน Simulator



