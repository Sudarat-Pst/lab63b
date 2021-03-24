# การทดลองที่1
## วัตถุประสงค์
1.
2.
## อุปกรณ์ที่ใช้
1.Microcontroller
2.อุปกร์สำหรับต่อUSB
3.เสาอากาศสำหรับ Wifi
## แหล่งข้อมูลเพื่อการศึกษา
01 run example 1 https://youtu.be/NLIUsWLEpmg
## วิธีทำการทดลอง
1.ต่อ Microcontroller เข้ากับ serial
2.เข้า Command promt เข้าไปดูตัวอย่างโปรแกรม โดยใช้คำสั่ง cd pattanitor
3.เข้าโปรแกรมที่ 1 : cd 01_Serial-Moni
4.ใช้คำสั่ง vi src/main.cpp จะได้โค้ดที่รันคือ
![image](https://user-images.githubusercontent.com/80880258/112250302-b3cf9280-8c8b-11eb-9be3-db5204331900.png)
5.ใช้คำสั่ง vi platformio.ini จะให้ข้อมูลเกี่ยวกับเป็นผลิตภัณฑ์ของบริทไหน บอร์ดชื่ออะไร เขียนด้วยวิธีไหน
![image](https://user-images.githubusercontent.com/80880258/112250358-cfd33400-8c8b-11eb-8e86-db90c4692e80.png)
6.ทำการอัพโหลดโปรแกรมเข้าสู่ Microcontroller โดยใช้คำสั่ง pio run -t upload
7.ระหว่างอัพโหลดให้กดปุ่ม set ที่ Microcontroller เมื่ออัพโหลดเสร็จให้ใช้คำสั่ง pio device monitor เพื่อดูผลัพธ์จะขึ้นข้อมูลดังนี้
![image](https://user-images.githubusercontent.com/80880258/112250432-f1342000-8c8b-11eb-91f6-e91ade01087c.png)
8.เมื่อกดปุ่มรีเซ็ต โปรแกรมจะเริ่มรีเซ็ตและเริ่มนับจากหนึ่งใหม่อีกครั้ง
![image](https://user-images.githubusercontent.com/80880258/112250458-fdb87880-8c8b-11eb-9566-69e73d4110a8.png)

