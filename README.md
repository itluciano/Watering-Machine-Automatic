![](/images/banner.png)

# ![](/images/welcome.png) Welcome
สวัสดีครับ วันนี้กลุ่มผม Waterning Plants System ได้จัดทำระบบรดน้ำต้นไม้อัตโนมัติขึ้น เพื่อตอบสนองต่อความต้องการให้กับผู้ที่ต้องการความสะดวกสบายในการรดน้ำต้นไม้
โดยสามารถดูการแจ้งเตือนได้จาก Smartphone 

---


# ![](/images/use.png) How to use
วิธีใช้นั้นง่าย ๆ นะครับ ต่อสาย usb 2.0 เข้ากับ NODEMCU ESP8266 เท่านี้เครื่องรดน้ำต้นไม้ของเราก็จะทำงานตามโปรแกรมที่สั่งไว้แล้วครับ
นั้นก็คือ ความชื้นต่ำกว่า 40% จะทำการรดน้ำต้นไม้ แต่ถ้าอยากปรับค่าตามสภาพแวดล้อมต่าง ๆ ก็สามารถแก้ไขได้ผ่านไฟล์ Motor_Control.ino
และสามารถรับการแจ้งเตือนการทำงานจาก application blynk ได้ 

** หมายเหตุ จำเป็นต้องต่อ Internet เข้ากับ NODEMCU ESP8266 ผ่าน Wifi ด้วยครับ

[Full Documentation](https://github.com/itluciano/Warterning-Plants-System/wiki)

---

# ![](/images/blynk.png) Application Blynk
ในส่วนของ application ที่ใช้ ชื่อว่า Blynk นั้น สามารถรับการแจ้งเตือนว่าควรรดน้ำต้นไม้แล้วหรือยัง
มีหน้าจอ Monitor ไว้บอกค่าของเซนเซอร์ที่เป็นจำนวนเต็ม และความชื้นในดิน บอกเป็นเปอร์เซ็นต์

## Screen Short Monitor
![](/images/monitor.jpg)

## Screen Short Blynk Notify
![](/images/notification.jpg)

### Pump ON
![](/images/on.jpg)

### Pump OFF
![](/images/off.jpg)

---
 
# ![](/images/library.png) Library Requirements 
* [Blynk Library](https://github.com/blynkkk/blynk-library)
* [LCD_I2C Library](https://github.com/fdebrabander/Arduino-LiquidCrystal-I2C-library)

---

# ![](/images/tools.png) Tools
* Node MCU ESP8266
* LCD_I2C
* 1 Channel Relay
* Soil Moisture Sensor
* LED Tube
* Water Pump 5V
* USB 2.0
* Powerbank
* Breadboard
* Water Source
* Plant

---

# ![](/images/picture.png) More Pictures
แสดงถึงด้านหน้าและด้านข้างของอุปกรณ์

## Front View
![](images/front.jpg)

## Side View
![](images/side.jpg)

---

# ![](/images/video.png) Video Presentation
https://www.youtube.com/watch?v=RtBW8Imnios
---

# ![](/images/poster.png) Poster Project
![](/images/Poster.png)

---

# ![](/images/member.png) Team Members
<table>
	<tr align="center">
		<td><a href="https://github.com/Krittanai1999" target="_blank"><img src="Member Profile/seen.jpg"></a></td>
		<td><a href="https://github.com/Chaninpp" target="_blank"><img src="Member Profile/ton.jpg"></a></td>
		<td><a href="https://github.com/itluciano" target="_blank"><img src="Member Profile/jack.jpg"></a></td>
		<td><a href="https://github.com/aoffis" target="_blank"><img src="Member Profile/aoff.jpg"></a></td>
	</tr>
	<tr align="center">
		<td>Krittanai Pahonkan</td>
		<td>Chanin Pholpho</td>
		<td>Narongrit Thongdee</td>
		<td>Nattapong Sainak</td>
	</tr>
	<tfoot align="center">
		<td>Student ID: 61070003</td>
		<td>Student ID: 61070035</td>
		<td>Student ID: 61070047</td>
		<td>Student ID: 61070054</td>
	</tfoot>
</table>

---

# ![](/images/teacher.png) Assistant Teachers
<table>
	<tr align="center">
		<td><img src="Assitant Teacher/Aj Aong.jpg" width='200'></a></td>
		<td><img src="Assitant Teacher/Aj Panwit.jpg" width='200'></a></td>
	</tr>
	<tfoot align="center">
		<td>รศ.ดร. กิติ์สุชาต พสุภา</td>
		<td>รศ.ดร. ปานวิทย์ ธุวะนุติ</td>
	</tfoot>
</table>

---

**โครงงานนี้เป็นส่วนหนึ่งของวิชา 06016315 Computer Programming (COMPRO)** 

**คณะเทคโนโลยีสารสนเทศ สถาบันเทคโนโลยีพระจอมเกล้าเจ้าคุณทหารลาดกระบัง (สจล.)**  
