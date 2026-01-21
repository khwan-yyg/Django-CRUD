## ระบบจัดการพนักงาน (Employee Management CRUD)
เป็นเว็บแอปพลิเคชัน CRUD ที่พัฒนาด้วย Django สำหรับการจัดการข้อมูลพนักงาน ใช้ Bootstrap 5 ในการตกแต่งหน้าเว็บ และฐานข้อมูลเริ่มต้นเป็น SQLite 

ฟีเจอร์
- เพิ่มข้อมูลพนักงานใหม่
- แสดงรายชื่อพนักงานทั้งหมด
- แก้ไขข้อมูลพนักงาน
- ลบข้อมูลพนักงาน
- รองรับการใช้งานบนมือถือด้วย Bootstrap

เทคโนโลยีที่ใช้
- Backend: Django 5 / Python 3
- Frontend: HTML, Django Templates, Bootstrap 5
- Database: SQLite (ค่าเริ่มต้น)

## Install dependencies

```sh
pip install -r requirements.txt
```

## Run migrations
  
```sh
python manage.py migrate
```

## Run Server
  
```sh
python manage.py runserver
```