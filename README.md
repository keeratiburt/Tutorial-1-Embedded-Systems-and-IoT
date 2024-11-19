# Tutorial-1-Embedded-Systems-and-IoT


Objectives
1.	ใช้งาน Arduino IDE เบื้องต้นได้
2.	เข้าใจหลักการทำงานของฟังก์ชัน setup และ loop
3.	รู้จัก digitalWrite
4.	รู้จัก pinMode
5.	รู้จัก delay
6.	iู้จัก built-in LED


Hardware
1.	ESP32		    1
2.	Breadboard  1
3.	Computer	  1
4.	microUSB	  1 

Software
1. Arduino IDE v
--------------------
Instruction

การติดตั้งโปรแกรม สำหรับ ESP32
1. ดาวน์โหลด Arduino IDE ได้จากเว็บไซต์ https://www.arduino.cc/en/software แนะนำเวอร์ชัน 2.0.3 จาก github
2. ติดตั้ง ESP32 library โดยคลิกที่ File > Preferences และใส่ลิงค์ลงในช่อง Additional Boards Manager https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
3. คลิกที่ Boards Manager ดังรูป <br>
   <img width="127" alt="image" src="https://github.com/user-attachments/assets/3093df80-92d9-4704-aefd-388fed2a8282"> <br>
4. พิมพ์ "esp32" ลงในช่อง search และติดตั้ง esp32 by Espressif Systems เวอร์ชัน 2.0.1 ดังรูป <br>
   <img width="326" alt="image" src="https://github.com/user-attachments/assets/5e275d7e-a7df-434b-af96-ca0d8533ca19"> <br>
5. โดยดาวน์โหลดไฟล์ชื่อ CP210x_Universal_Windows_Driver.zip ใน Teams
6. ติดตั้ง driver จากไฟล์ที่ดาวน์โหลดมาผ่าน Device Manager โดยการ update driver
7. หลังจากติดตั้ง driver เสร็จสิ้น ให้เชื่อมต่อ esp32 กับคอมพิวเตอร์ด้วยสาย micro USB
8. เลือกบอร์ดที่เรากำลังใช้งาน ดังรูป <br>
![asdfasdf](https://user-images.githubusercontent.com/125423996/218939893-fdf3ef3b-da7b-40d5-90e0-891c3fdd2c4d.JPG) <br>


--------------------
การติดตั้งโปรแกรม สำหรับ ESP8266
1. ตั้งค่า Arduino IDE ได้จากเว็บไซต์ https://www.arduino.cc/en/software
2. ตั้งค่าและติดตั้ง driver เพื่อให้ใช้งาน ESP8266 ได้โดยเข้าดูวิธีการตั้งค่า ESP8266 ได้ที่ลิงค์ https://www.achardkits.com/article/4/ติดตั้งบอร์ด-nodemcu-esp8266-ใช้งานกับ-arduino-ide

