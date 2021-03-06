---
title: คู่มือใช้งาน Web MiniDisc
description: คู่มือใช้งาน Web MiniDisc แบบ step by step
---

## Install a driver with Zadig
ติดตั้งไดร์เวอร์ด้วยโปรแกรม Zadig

- ดาวน์โหลดโปรแกรม Zadig [💾คลิกที่นี่เพื่อดาวน์โหลดโปรแกรม](files/zadig-2.5.zip)
- แตกไฟล์และดับเบิ้ลคลิก **zadig.exe** เพื่อเปิดโปรแกรมขึ้นมา
- โปแกรมจะถามว่าจะให้ตรวจสอบการอัพเดทหรือไหม่ สามารถคลิก No ไปก่อนได้ครับ

![](images/web-mini-disc/update-policy.png)

- รอจนหน้าต่างหลักของโปรแกรมแสดงขึ้นมา

![](images/web-mini-disc/default-window.png)

- ต่อเครื่องเล่น Net MD เข้ากับเครื่องคอมพิวเตอร์ผ่านสาย USB (สำหรับเครื่องเล่นแบบ Deck หรือ Bookshelf ให้เปลี่ยน mode ไปเป็น Net MD ก่อน)
- **!!! สำคัญมาก** สำหรับเครื่องคอมพิวเตอร์ที่ยังไม่เคยติดตั้ง Net MD ไดร์เวอร์มาก่อน ตัวโปรแกรมจะแสดงชื่ออุปกรณ์ เช่น Net MD หรือ Net MD Walkman ให้โดยอัตโนมัติ

![](images/web-mini-disc/auto-select-device.png)

- ถ้าไม่มีอุปกรณ์ (Net MD หรือ Net MD Walkman) แสดงขึ้นมา ให้ทำตามขั้นตอนดังต่อไปนี้
  1. คลิก Options
  2. คลิก List All Devices
  3. คลิกเลือกอุปกรณ์ที่ได้เชื่อมต่อกับเครื่องคอมพิวเตอร์

![](images/web-mini-disc/list-all-devices.png)

- เมื่อได้เลือกอุปกรณ์ที่เชื่อมต่อกับเครื่องคอมพิวเตอร์เป็นที่เรียบร้อยแล้ว ให้คลิกปุ่ม **Install Driver** (สำหรับเครื่องคอมพิวเตอร์ไม่เคยติดตั้งไดร์เวอร์มาก่อน)
  หรือคลิกปุ่ม **Replace Driver** (สำหรับเครื่องคอมพิวเตอร์ที่เคยติดตั้งไดร์เวอร์ไว้แล้ว)

![](images/web-mini-disc/replace-driver.png)

- จะมีหน้าต่างแสดงขึ้นมาหลังจากได้ติดตั้งไดร์เวอร์เป็นที่เรียบร้อยแล้ว

![](images/web-mini-disc/driver-installed-successfully.png)

## Use Web MiniDisc
ใช้งาน Web MiniDisc

- เปิดเบราว์เซอร์ (Chrome, Firefox หรือ Edge) แล้วไปที่ https://stefano.brilli.me/webminidisc/
- ที่เบราว์เซอร์จะแสดงหน้าแรกของ Web MiniDisc ขึ้นมา

![](images/web-mini-disc/home-page.png)

- ใส่แผ่น MD ที่จะเขียนเพลงเข้าไปในเครื่องเล่น
  - คลิกปุ่ม **CONNECT**
  - คลิกอุปกรณ์ที่ต่ออยู่
  - คลิกปุ่ม **Connect**

![](images/web-mini-disc/connect-device.png)

- Web MiniDisc จะแสดง:
  - ชื่อเครื่องเล่นที่เชื่อมต่ออยู่
  - ชื่อแผ่น MD
  - รายชื่อเพลงทั้งหมดในแผ่น MD หรือแสดงเป็นแผ่นเปล่าถ้าไม่เพลงใดๆ เลย

![](images/web-mini-disc/list-all-songs.png)

- คลิกปุ่มสีน้ำเงินขนาดใหญ่ที่มุมล่างขวาของจอ เลือกเพลงที่จะเขียนลงแผ่น MD (สามารถกดปุ่ม CTRL ค้างไว้ แล้วคลิกเลือกหลายเพลงได้)

![](images/web-mini-disc/select-songs.png)

- ปรับค่าในการอัดเพลง
  - เลือกโหมดในการอัดเพลงเป็น SP, LP2 หรือ LP4
  - กำหนดชื่อเพลงว่าจะใช้จากข้อมูลใด เช่น ชื่อไฟล์
  - กดปุ่ม **OK** เพื่อเขียนเพลงลงแผ่น MD
  - เราสามารถกดปุ่ม **SHOW TRACK** เพื่อแสดงรายชื่อเพลงที่ได้เลือกมาทั้งหมดได้

![](images/web-mini-disc/upload-settings.png)

- Web MiniDisc ก็จะเริ่มแปลงเพลงที่ได้เลือกไว้และเขียนลงแผ่น MD
- เราสามารถคลิกเลือก **Notify when completed** เพื่อให้โปรแกรมแจ้งเตือนเมื่อเขียนแพลงทั้งหมดเสร็จแล้ว

![](images/web-mini-disc/recording.png)

- รอจนกว่า Web MiniDisc ได้เขียนเพลงที่ได้เลือกไว้ทั้งหมดลงแผ่น MD
- เข้าไปที่เมนู คลิกจุดเล็กๆ สามจุดที่มุมบนขวาของจอ แล้วคลิก **Exit** เพื่อออกจาก Web MiniDisc
- ถอดสาย USB ที่เชื่อมต่อเครื่องเล่นกับเครื่องคอมพิวเตอร์ และกดเล่นแผ่น MD ที่เครื่องเล่นได้เลย

![](images/web-mini-disc/menu.png)

## Credit & Reference

- คุณ [Puwanai Mahachinorot](https://www.facebook.com/pinghitz) ที่ได้แนะนำ Web MiniDisc
- [Using Web MiniDisc from MiniDisc Wiki](https://www.minidisc.wiki/guides/webminidisc)

