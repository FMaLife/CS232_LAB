# CS232_22568_LAB
การทดสอบภาคปฏิบัติ

ข้อที่ 1: ให้นักศึกษาเปิดใช้งาน EC2 instance ประเภท t2.micro ซึ่งติดตั้งระบบปฏิบัติการ Amazon Linux 2023 โดยตั้งชื่อ EC2 instance เป็น ec2xxxxyyyy (แทนที่ xxxx ด้วยเลขสี่ตัวสุดท้ายของรหัสนักศึกษา และ yyyy ด้วยรหัสส่วนตัวของนักศึกษา) นักศึกษาจะต้องตั้งค่าให้สามารถเข้าถึง instance นี้จากสาธารณะได้ จากนั้นให้ SSH เข้าไปที่ instance และรันคำสั่ง Linux CLI หนึ่งคำสั่งเพื่อแสดงการใช้งานเบื้องต้น 
สิ่งที่ต้องส่ง: *ส่งภาพ Capture เพียงภาพเดียว ให้เห็นหน้าจอ Instance Summary ที่แสดงรายละเอียดของ EC2 instance ได้แก่ ชื่อ, ประเภท และ Public IPv4 DNS ของ instance ได้ชัดเจน พร้อมกับหน้าจอที่แสดง terminal ที่เห็นผลลัพธ์ของคำสั่ง Linux CLI ที่รันสมบูรณ์แล้ว พร้อมกับรันคำสั่ง Linux CLI หนึ่งคำสั่งเพื่อแสดงการใช้งานเบื้องต้น
https://chatgpt.com/share/69e4aa7a-0858-839d-b084-891d80ceab97


ข้อที่ 2: ให้นักศึกษาเปิดใช้งาน EC2 instance ประเภท t2.micro ร่วมกับการใช้ user data เพื่อติดตั้ง Web server (httpd) และสร้างเว็บเพจ index.html แบบง่ายด้วยคำสั่ง echo ให้มีข้อความ
<center><h1>This is xxxx instance with the code yyyy that runs the Apache Webserver!</h1></center>  (แทนที่ xxxx ด้วยเลขสี่ตัวสุดท้ายของรหัสนักศึกษา และ yyyy ด้วยรหัสส่วนตัวของนักศึกษา) ตั้งค่า Security group ตามความเหมาะสม และตรวจสอบการเปิดหน้าเว็บผ่าน Web browser  (แทนที่ xxxx ด้วยเลขสี่ตัวสุดท้ายของรหัสนักศึกษา และ yyyy ด้วยรหัสส่วนตัวของนักศึกษา)
สิ่งที่ต้องส่ง: *ส่งภาพ Capture เพียงภาพเดียว ให้เห็นหน้าจอ Instance Summary ที่แสดงรายละเอียดของ EC2 instance ได้แก่ ชื่อ, ประเภท และ Public IPv4 DNS ของ instance ได้ชัดเจน พร้อมกับสคริปต์ user data ของ instance พร้อมกับหน้าเว็บเพจ index.html ใน Web browser ให้เห็น URL ของเว็บเพจชัดเจน
https://chatgpt.com/share/69e4d4db-634c-83a1-b661-c4c470f4e490
