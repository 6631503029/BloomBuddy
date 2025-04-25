ชื่อ - นามสกุล (Full Name): Phorn Potjanasuj
รหัสนักศึกษา (Student ID): 6631503029
ชื่อแอป (App Name): BloomBuddy
Framework ที่ใช้ (Framework Used): React Native / Expo go
ลิงก์ GitHub Repository: [[ใส่ลิงก์ที่นี่ | Insert link here](https://github.com/6631503029/BloomBuddy)]
ลิงก์ไฟล์ติดตั้ง (APK/IPA): [ใส่ลิงก์ที่นี่ | Insert link here]

1. การออกแบบแอป | App Concept and Design (2 คะแนน / 2 pts)
1.1 ผู้ใช้งานเป้าหมาย | User Personas

Personal 1:  
- ชื่อ: นุ่น  
- อายุ: 20 ปี  
- อาชีพ: นักศึกษาปี 2  
- ความต้องการ: ต้องการจำได้ว่ารดน้ำต้นไม้ต้นไหนไปแล้วบ้าง

Personal 2:  
- ชื่อ: ลูกจัน  
- อายุ: 20 ปี  
- อาชีพ: นักศึกษาปี 2   
- ความต้องการ: อยากใช้แอปที่บอกว่าต้นไม้ไหนถึงเวลารดน้ำ,ใส่ปุ๋ย หรือเปลี่ยนกระถาง
  
1.2 เป้าหมายของแอป | App Goals
- ให้ผู้ใช้สามารถ ดูแลต้นไม้ได้อย่างมีระบบ
- ช่วยเตือนเวลาที่ควรรดน้ำ/ใส่ปุ๋ย/เปลี่ยนกระถาง
- ลดโอกาสต้นไม้เฉาตายจากการลืมดูแล
- บันทึกข้อมูลต้นไม้แต่ละต้นได้อย่างละเอียด
  
1.3 โครงร่างหน้าจอ / Mockup
ใส่รูปภาพ หรือคำอธิบายแต่ละหน้าหลัก 3 หน้า | Attach image or describe 3 main pages
![My Plants](https://github.com/user-attachments/assets/6c64969d-0cf2-4ae6-8cb7-ef3a3a45712d)
![Care Schedule](https://github.com/user-attachments/assets/09ddca44-0cf3-4321-bf31-7211bf5cda9c)
![Add Plant](https://github.com/user-attachments/assets/cf7724ec-bf6c-4e10-81db-d02d85118b22)
![Add PLant](https://github.com/user-attachments/assets/7282aae4-0848-4515-a21e-056c9d07816d)

1.4 การไหลของผู้ใช้งาน | User Flow
เปิดแอป > เข้าหน้าหลัก My Plants > เลือก "+" > ใส่รายละเอียดต้นไม้ > กด save > ดูต้นไม้ที่ต้องรดน้ำหน้า Care Schedule

2. การพัฒนาแอป | App Implementation (4 คะแนน / 4 pts)
2.1 รายละเอียดการพัฒนา | Development Details
เครื่องมือที่ใช้ / Tools used:
- React Native
- Expo go
  
2.2 ฟังก์ชันที่พัฒนา | Features Implemented
Checklist:
- [x] เพิ่มและแก้ไขข้อมูลการต้นไม้ได้
- [x] ดูวันที่ต้องรดน้ำต้นไม้ได้
- [x] มีหน้ารวมต้นไม้ที่บันทึก
- [ ] มีแจ้งเตือน

2.3 ภาพหน้าจอแอป | App Screenshots
แนบภาพหรือ URL (Attach images or image links):
![My Plants](https://github.com/user-attachments/assets/6c64969d-0cf2-4ae6-8cb7-ef3a3a45712d)
![Care Schedule](https://github.com/user-attachments/assets/09ddca44-0cf3-4321-bf31-7211bf5cda9c)
![Add Plant](https://github.com/user-attachments/assets/cf7724ec-bf6c-4e10-81db-d02d85118b22)
![Add PLant](https://github.com/user-attachments/assets/7282aae4-0848-4515-a21e-056c9d07816d)

3. การ Build และติดตั้งแอป | Deployment (2 คะแนน / 2 pts)
3.1 ประเภท Build | Build Type
[x] Debug
[ ] Release

3.2 แพลตฟอร์มที่ทดสอบ | Platform Tested
[ ] Android
[x] iOS

3.3 ไฟล์ README และวิธีติดตั้ง | README & Install Guide
แนบไฟล์หรือคำอธิบายการติดตั้งแอป | Insert steps
1. ดาวน์โหลดไฟล์ .apk
2. เปิดในอุปกรณ์ IOS
3. ติดตั้งผ่าน File Manager
4. การสะท้อนผลลัพธ์ | Reflection (2 คะแนน / 2 pts)
- UI เป็นมิตรกับผู้ใช้งาน
- ลดอัตราต้นไม้ตายจากการลืมดูแล
- ยังไม่มีระบบสำรองข้อมูลหรือ Sync กับ Cloud
- ในอนาคตอยากพัฒนาให้ใช้ AI ช่วยแนะนำการดูแลพืชแต่ละชนิดได้
  
5. การใช้ AI ช่วยพัฒนา | AI Assisted Development (Bonus / ใช้ประกอบการพิจารณา)
5.1 ใช้ AI ช่วยคิดไอเดีย | Idea Generation
Prompt ที่ใช้:  "ขอไอเดียสร้างแอป react native ที่สามารถเก็บข้อมูล database ผ่าน local ได้"
ผลลัพธ์:  ได้ไอเดียแอปต่างๆ แต่เลือกแอปเกี่ยวกับดูแลต้นไม้มา

5.2 ใช้ AI ช่วยออกแบบ UI | UI Layout Prompt
Prompt ที่ใช้:  "ช่วยเสนอแนวคิดเพิ่มหน่อย ทั้งชื่อแอป และ screens สัก 3 หน้า"
ผลลัพธ์:  ได้ชื่อแอปมา และ โครงสร้างแต่ละหน้าว่าควรมีฟีเจอร์อะไรบ้าง

5.3 ใช้ AI ช่วยเขียนโค้ด | Code Writing Prompt
Prompt ที่ใช้:  can you craete src folder and make My Plants Screen (Home)
Displays a list of trees that the user has added, each card displays (tree name, image (from camera or gallery), date of last watering, "Watered" button), FAB (Floating Action Button) For adding new trees. create Add/Edit Plant Screen
There is a form to enter the tree details: name, photo, description,watering frequency (how many days), category (e.g., flowering plants, ornamental plants, edibles), and the "Save" button.
Care Schedule Screen
- Calendar or list by day
- It shows which plants need to be watered today/tomorrow.
- Connect with Notification API
ผลลัพธ์:  ได้หน้า screens มา 3 หน้า แต่ยังไม่สมบูรณ์ แค่โครงร่างคร่าวๆ

5.4 ใช้ AI ช่วย debug | Debug Prompt
Prompt ที่ใช้:  "make every bottom can click"
ผลลัพธ์:  AI ทำโค้ดให้ใหม่

5.5 ใช้ AI ช่วย Deploy | Deployment Prompt
Prompt ที่ใช้:  "How to build Flutter app as APK and test on Android?"
ผลลัพธ์:  คำสั่ง flutter build apk --release พร้อมวิธีติดตั้ง
