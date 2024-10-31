# แนวทางการทำงาน ESP32_ESP-IDF_WiFi-STA cook book
## 1. ระบุตัวอย่างที่ใช้ ว่าเอามาจากตัวอย่างไหน
- Show example -> wifi -> station -> Create project using example station
![Screenshot 2024-11-01 052140](https://github.com/user-attachments/assets/2beaf84b-6a98-4de4-9f14-0b454b192f8c)


## 2. ระบุว่า จะแก้ไขตรงไหนบ้าง เพื่ออะไร 
- แก้ไข WiFi SSID, WiFi Password เพื่อระบุ WiFi ที่ต้องการจะเชื่อมต่อกับ ESP32
![Screenshot 2024-11-01 052608](https://github.com/user-attachments/assets/7b8d9dbb-70d8-4998-8352-70332d929d34)


## 3. แสดงขั้นตอนการทำ project
- แก้ไข เพิ่มข้อมูลรหัส wifi จากข้อ 2.
### หน้าตอนเชื่อม wifi ไม่สำเร็จ
![Screenshot 2024-11-01 053904](https://github.com/user-attachments/assets/8d4b5c12-99ba-4c6f-bc30-5717f91432e3)

- หากไม่สำเร็จให้กด full clean ล้างข้อมูลทั้งหมดแล้วทำใหม่ตรวจเช็คข้อมูลว่ากรอกถูกต้องไหม

## 4. แสดงผลการทำ project
- ### หน้าตอนเชื่อม wifi สำเร็จ
![Screenshot 2024-11-01 053635](https://github.com/user-attachments/assets/215c4815-766d-4c8f-83de-2152dd252147)


## 5. สรุปผลการทำ project 
- ### โปรเจคนี้จะตรวจสอบถ้าการเชื่อมต่อสำเร็จ terminal จะแสดงข้อมูล IP Address ที่ได้รับ
