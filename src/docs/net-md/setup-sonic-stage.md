---
title: การติดตั้งไดร์เวอร์ NetMD และโปรแกรม SonicStage 4.3 บน window 10 64bit
description: การติดตั้งไดร์เวอร์ NetMD และโปรแกรม SonicStage 4.3 บน window 10 64bit step by step
---

## 1. เตรียมโปรแกรม และไดร์ฟเวอร์

1.1 ดาวน์โหลดโปรแกรม SonicStage 4.3 Click to download
แล้วคลิก Download anyway (อาจจะต้องคลิกสองครั้ง)


1.2 ดาวน์โหลดไดร์เวอร์ 64 bit Click to download
ภาพแสดงทั้งสองไฟล์ที่โหลดลงมาในเครื่องเก็บที่โฟล์เดอร์ Downloads


1.3 unzip แตกไฟล์ SonicStage 4.3.zip และ Sony NetMD driver.zip
โครงสร้างไฟล์ชองโฟล์เดอร์ SonicStage 4.3
```sh
└───SonicStage 4.3
│   ├───Common
│   ├───Device
│   ├───Resource
│   └───SonicStage
│   DSetup.dll
│   ExtendSs.dll
│   SetupSS.exe 👈
│   SetupSS.ini
```

โครงสร้างไฟล์ชองโฟล์เดอร์ SonicStage Sony NET MD Driver
```sh
└───Sony NET MD Driver
│   netmd760.cat
│   NETMD760.inf
│   NETMD760.sys
```


2. ติดตั้งโปรแกรม SonicStage
2.1 เข้าในโฟล์เดอร์ SonicStage 4.3 ที่แตกมาแล้ว ดับเบิ้ลคลิก SetupSS.exe เพื่อทำการติดตั้งโปรแกรม
2.2 คลิก Next หรือ Yes ไปเรื่อยๆ จนถึงหน้าสุดท้าย จะมีข้อความแสดงว่าให้ Restart เครื่องเครื่อง
2.3 คลิกปุ่ม Done เครื่องคอมพิวเตอร์จะ Restart ให้อัตโนมัติ รอจนกว่าเครื่องคอมพิวเตอร์จะ เปิดขึ้นมาพร้อมใช้งาน และทำตามขั้นตอนถัดไป



3. ปิดการลงไดร์เวอร์เฉพาะ signature (disable driver signature enforcement)

3.1 ไปที่มุมล้างซ้ายของหน้าจอ คลิกปุ่มไอค่อน Windows
3.2 พิมพ์ startup
3.3 แล้วคลิกเลือก Change advanced startup settings.





3.4 ให้คลิกปุ่ม Restart now ที่อยู่ใต้ Advanced startup


3.5 คอมพิวเตอร์จะ restart อัตโนมัติ เมื่อเครื่องเปิดขึ้นมาจะแสดงหน้าจอ Choose an option ให้เลือกคลิก Troubleshoot



3.6 คลิกเลือก Advanced Options

3.7 คลิกเลือก Startup Settings



3.8 คลิก Restart




3.9 เมื่อเครื่องคอมพิวเตอร์เปิดขึ้นมาแล้ว ให้กดปุ่มเลข 7 หรือ F7 ที่แป้นพิมพ์


3.10 เครื่องคอมพิวเตอร์จะ restart โดยอัตโนมัติ หลังจากที่คอมพิวเตอร์เปิดขึ้นมา เราก็สามารถติดตั้งไดร์เวอร์ให้กับ NetMD ได้แล้ว


4. เปิดเครื่องเล่น (สำหรับเครื่องเล่นแบบ Deck หรือ Bookshelf ให้เปลี่ยน modeไปเป็น NetMD)
ต่อเครื่องเครื่องเล่นเข้ากับคอมพิวเตอร์ผ่านสาย USB

4.1 ให้ไปทีไอค่อน Window มุมซ้ายล่างของจอ แล้วคลิกขวา ให้เลือก Device Manager


4.2 หน้าจอ Device Manager จะแสดงขึ้นมา ให้เลื่อนหาไอค่อนที่มีข้อความ NetMD ดังรูปด้านล่างนี้



4.3 ให้คลิกขวาที่ไอคอนนี้ แล้วเลือก Update driver



4.4 ในหน้าอัพเดทไดร์เวอร์เลือก Browse my computer for drivers
4.5 เลือกโฟลเดอร์ที่เก็บ Sony NET MD Driver ที่เราได้ดาวน์โหลดและ unzip ไว้แล้ว
4.6 กด OK เพื่อเลือกโฟล์เดอร์
4.7 กด Next เพื่ออัพเดทไดร์เวอร์


4.8 ให้คลิกเลือก Install this driver software anyway


4.9 เมื่อลงไดร์เวอร์เสร็จเรียบร้อยแล้ว จะมีข้อความ Windows has successfully updated your driver


5. เปิด sonic stage (การเปิดใช้งานครั้งแรกจำมีการกกำหนดค่าเริ่มต้นให้คลิก next, next ไปได้เลย)

5.1 เลื่อนเมาส์ไปชี้ตรงข้อความ Transfer



5.2 คลิกเลือก NetMD



5.3 ถ้าในเครื่องมีแผ่น MD ที่มีเพลงอยู่ ตัวโปรแกรมก็จะแสดงเพลงทั้งหมดในแผ่น MD นั้น



5.4 ถ้าจะ copy เพลงจากคอมพิวเตอร์ไปยังแผ่น MD  เพียงลากเพลงไปยังหน้าหน้าต่าง Library ด้านซ้ายมือ
แล้วก็ click ปุ่มลูกศรสีแดง  ได้เลย





## Credit & Reference
- Credits : คุณชาย Teerapong Kuchi Seeker, คุณ Parinya Jaipang , คุณอาทิตย์ สมวาที,
- คุณ Tanapon Sean Pochatan, คุณ Napadon Tang และอีกหลายๆ ท่านในกลุ่ม MINIDISC PLAYGROUND
- ข้อมูลจาก DoSomething ใน youtube (https://youtu.be/euTfzqsm8YQ)
- ข้อมูลจาก https://www.techspace.co.th/kb/entry/412/
- ข้อมูลจาก https://archivisiondirectory.blogspot.com/2011/01/download-netmd-usb-drivers-for-your.html
- ข้อมูลจาก https://www.tenforums.com/tutorials/156602-how-enable-disable-driver-signature-enforcement-windows-10-a.html


