# LE202
# Github
### ขั้นตอนการสมัครสมาชิก Github
เข้าเว็บไซต์ github.com
Sing up
Create your account
ยืนยันตัวตน
Choose free
ตอบคำถามหรือไม่ตอบก็ได้
Complete setup
Github จะส่งเมลไปให้เราเพื่อยืนยันตัวตนอีกครั้ง
กด verify email address ในเมลที่เราได้รับ
## Git & Github
### Git
คือ Version control ที่คอยจัดเก็บความเปลี่ยนแปลงของไฟล์ในโปรเจคของเราหรือของทีมเราไม่ว่าเพื่อนคนไหนจะเปลี่ยนแปลง, เพิ่ม, ลบอะไรในโปรเจคเราก็สามารถที่จะรับรู้ได้ ทำให้รู้ว่า ‘งานที่กำลังทำอยู่ถึงไหนแล้ว’
### Github
คือ เว็ปไซต์ที่ทำให้เราสามารถใช้ Git ร่วมกับคนอื่นได้ หรือพูดง่ายๆก็คือ Git ที่อยู่บนเว็บไซต์ ซึ่งจะทำให้เราสามารถใช้ Git ร่วมกับคนอื่นได้โดยผ่านเว็บไซต์ซึ่งจะมักนิยมใช้กันมาก ในการเก็บ Project Open Source ต่างๆ **ดาวน์โหลด และ ติดตั้งยังไง ?** สำหรับการติดตั้งนั้นก็สามารถเข้าไปดาวน์โหลดในเว็บไซต์ของ Git ได้เลย มีตัวติดตั้งให้ติดตั้งกันง่ายๆ โหลดไฟล์จากหน้าเว็บได้เลย **การสร้างรีโป้** ให้มาที่ปุ่ม + ด้านบนขวาแล้วก็กด New Repioitory หลังจากกดเข้าไปแล้วหน้าเว็บจะพาไปสร้าง Repo ของคุณ ช่อง Repository name : ให้ใส่ชื่ออะไรก็ได้ แต่ตามปกติที่จะใส่กันคือ ชื่อ ของ Project ที่จะทำ ช่อง Description : สามารถใส่รายระเอียดของ Project เข้าไป ( ใส่หรือไม่ก็ได้ ) Radio Button [ Public, Private ] ถ้าต้องการให้คนอื่นสามารถเข้าถึง Repo ของเราได้ ให้เลือก public แต ถ้าหากไม่ต้องการให้เข้าถึง Repo ของเราก็ให้เลือก Private ช่อง Initialize this repository with a README ยังไม่ต้องติ๊กก็ได้ แต่ถ้าใคร่อยากจะติ๊ก ก็เชิญได้ตามสบาย หลังจากทำทุกขั้นตอนแล้สก็ให้ก็ Create repository ได้เลย
### Markdown
Markdown เป็น Lightweight Markup Language ที่ใช้สำหรับจัด Format ของ Plain Text บน Document และแปลงเป็น HTML บนเว็บต่าง ๆ ได้ สร้างขึ้นโดย John Gruber ในปี 2004 มีจุดเด่นที่ Syntax ง่ายต่อการอ่านและการเขียนสุด ๆ เพราะมีหน้าตาคล้ายกับภาษาที่เราใช้กันเลย โดย Markdown มีนามสกุลไฟล์เป็น .md  
1. Headings  
เราจะใช้ # สำหรับทำ Headings ทั้ง 6 แบบ โดยเพิ่มจำนวน # ตามเลเวล Heading ที่เราต้องการ นอกจากแบบตัวอย่างที่ 1.1 เรายังใช้ === และ — เพื่อแบ่งเลเวล Heading ได้เหมือนกัน  
2. Paragraphs (New Line)  
สามารถทำได้โดยการเว้นบรรทัดเปล่า 1 บรรทัดหรือกด Enter 2 ครั้งหลังข้อความ  
3. Horizontal Lines  
นอกจาก — จะใช้แบ่งเลเวล Heading ได้แล้ว ยังใช้สร้างเส้นคั่นแนวนอนได้อีกด้วย แต่ถ้าเหนือเส้นคั่นมีข้อความล่ะก็ เราต้องเว้นบรรทัดลงมาก่อนนะ เส้นคั่นถึงจะแสดง ไม่อย่างนั้น — จะมองว่าข้อความข้างบนเป็น Heading แทน  
4. Text Styles
มาดูวิธีจัดการกับข้อความดีกว่า เราจะทำตัวเอียงและตัวหนา โดยใช้ _ หรือ * ครอบข้อความที่เราต้องการให้เอียง และใช้ __ หรือ ** ครอบข้อความที่เราต้องการให้หนา  
**จุดสังเกต** ถ้าเราใช้ _ หรือ __ เราจะต้องเว้นวรรคข้างหน้าและข้างหลังของเครื่องหมาย _ เพื่อให้ข้อความเป็นตัวเอียง ไม่อย่างนั้น _ จะถูกมองว่าเป็นส่วนหนึ่งของข้อความ  
5. Links
เราจะใช้ [ ] แสดงข้อความที่เราต้องการ คู่กับกับใส่ลิงก์ในวงเล็บ ( ) เพื่อทำการลิงก์  
6. Images
การแทรกรูปภาพของ Markdown จะใช้ Syntax คล้ายกับ Links เลย แต่เพิ่มเครื่องหมายตกใจ ไปข้างหน้าแบบนี้ ![ ]( )  
7. Blockquotes
ไปต่อกันเลย ด้วยการทำ Quote เก๋ ๆ เพียงแค่ใส่ > หน้าข้อความเราที่ต้องการให้เป็น Quote เท่านั้น  
8. Lists
**Unordered Lists**  
การทำ Unordered List ทำได้หลายแบบ  
* มะเขือเทศ
* สับปะรด
- มะเขือเทศ
- สับปะรด
+ มะเขือเทศ
+ สับปะรด  
**Ordered Lists**  
สำหรับ Ordered List เราจะใช้ตัวเลข 1. 2. 3. รันรายการไปเรื่อย ๆ
1. มะเขือเทศ
2. ผักกาด
3. องุ่น
4. สับปะรด  
**Nested Lists**  
ถ้าเราอยากสร้าง List ที่ซ้อนกัน ให้เราเคาะ Space เข้าไปแบบตัวอย่างข้างล่างนี้เลย
* มะเขือเทศ
  * เนื้อสีแดง
  * มีคุณค่าทางอาหาร
    * วิตามินเอ
    * วิตามินซี
* สับปะรด
  * เนื้อสีเหลือง
  * มีผิวขรุขระ  
9. Code & Code Blocks
**Code**  
เราจะใช้เครื่องหมาย ' ครอบข้อความหรือโค้ดที่เราต้องการ เพื่อให้แสดงผลในรูปแบบของ Code  
แสดงข้อความบนภาษาไพธอน `print("Hello World")`  
ถ้าต้องการให้ข้อความหรือโค้ดอยู่ในลักษณะ Code Block เราจะใช้เครื่องหมาย ``` ครอบข้อความที่ต้องการให้เป็น Code Block  
หรือเพิ่มความเท่ขึ้นไปอีกด้วยการระบุภาษาของโค้ด  
```python
print("Hello World") 
```

```java
public static void main(String args[]) {
System.out.println("Hello, World!");
}
```
10. Task Lists
การทำ Task List เราจะใช้ – [x] สำหรับ Checked ที่ Task นั้น ๆ และใช้ – [ ] สำหรับ Task ที่ไม่ได้ถูก Checked
(Task List รองรับแค่บางเว็บไซต์/แอปพลิเคชันเท่านั้น เช่น GitHub)  
11. Tables
การทำตารางใน Markdown อาจจะต้องใช้จินตนาการนิดหน่อย โดยใช้เราคิดว่า | คือเส้นตารางแนวตั้ง และ — คือเส้นคั่นแนวนอนของหัวตาราง  
#### ช่องทางติดตาม

| ลำดับที่ | ช่องทางติดตาม | ลิงก์ของแต่ละช่องทาง |
| ---- | ---- | ---- |
| 1 | Facebook |  |
| 10 | YouTube |  |
| 100 | Instagram |  |

12. Emojis
นอกจากความสามารถต่าง ๆ ที่เราพูดไปก่อนหน้านี้ Markdown ยังสามารถแทรกอิโมจิได้อีกด้วย  
LE202 :t-rex: | Sunflower :sunflower: | Tomato :tomato:  
สำหรับ Emoji ต่าง ๆ ส่องเพิ่มเติมได้ที่ [ webfx.com ](https://www.webfx.com/tools/emoji-cheat-sheet/) หรือ [ emojipedia.org ](https://emojipedia.org/) (การแสดงผลของอิโมจิขึ้นอยู่กับเว็บไซต์/แอปพลิเคชัน/แพลตฟอร์มที่เราใช้งานด้วยนะ ✨)
### ทบทวนความรู้เกี่ยวกับ ESP-01 microcontroller
**01 digital** การเอาข้อมูลดิจิตอลมสใช้งานคือการนำเอาสัญญาณไฟฟ้ามาแทนด้วยตัวเลข ซึ่งเป็นเลขฐานสอง 1 0 (on, off) มีแรงดันหรือไม่มีแรงดัน การใช้ข้อมูลดิจิตอลไม่ว่าจะในโทรศัพท์หรือคอมพิวเตอร์ ขึ้นอยู่กับแรงดัน การเอาข้อมูลดิจิตอลมาใช้กับอักษร หนึ่งตัวอักษรแทนด้วยตัวเลขเป็นสัญญาณดิจิตอล เช่น A แทนด้วยเลข 41 (เลขฐานสิบหก) 1 ตัวอักษร แทนด้วย 4 บิต ซึ่ง 41 หมายถึง 8 บิต
**02 voltage** แรงดันไฟฟ้าคือความต่างศักย์ไฟฟ้าระหว่างจุดสองจุด สามารถวัดได้มีหน่วยเป็น volt แรงดันไฟฟ้ามีสองประเภท คือกระแสสลับ ไฟบ้าน กระแสตรง มีขั้วบวกกับขั้วลบ มีหลายแหล่งกำเนิดไฟฟ้า
**03 computer** คอมพิวเตอร์มีวิวัฒนาการมานานมาก โดยที่ 60 ปีก่อน คอมพิวเตอร์มีขนาดใหญ่มาก ต่อมามีขนาดเล็กลง และมีความเร็วสูงขึ้นตลอดจนมีความจุที่มากขึ้น
**04 internet** อินเทอร์เน็ตทำให้ทุกอย่างเชื่อมกันได้ทั่วโลกทั้งมีสายและไร้สาย ปัจจุบันมีผู้ใช้บริการอินเทอร์เน็ตมากถึง 4,800ล้านคน และมีเว็บไซต์ไม่ต่ำกว่า 1,800 ล้านเว็บไซต์
**05 program lang** การพัฒนาหรือการเขียนซอฟต์แวร์ให้รันบนคอมพิวเตอร์ เมื่อ 50-70 ปีที่แล้ว เริ่มต้นจากภาษา assembly และภาษา c ต่อมาเริ่มมีการพัณาภาษาเพื่อให้เราสทมารถเขียนโปรแกรมได้ง่ายขึ้น
**06 platformio** โปรแกรมบนคอมพิวเตอร์ขนาดเล็กหรือไมโครคอนโทรลเลอร์ ปัจจุบันมีบริษัทผู้ผลิตไมโครคอนโทรลเลอร์หรือคอมพิวเตอร์ตัวเล็กๆจำนวนมาก platformio ซึ่งเป็นการพัฒนาซอฟต์แวร์มาตรฐานแบบใหม่แบบเปิด ใช้วิธีการเขียนโปรแกรมแบบเดียวแต่สามารถเขียนโปรแกรมลงบนไมโครคอนโทรลเลอร์ได้หลายแบบโดยที่ผู้ใช้สามารถพัฒนาได้หลากหลาย หมายความว่าใช้ไมโครคอนโทรลเลอร์ได้หลากหลายผู้ผลิตและวิธีในการเขียนโปรแกรมสามารถทำได้หลายแบบที่เป็นที่นิยมเขียนแบบ arduino ซึ่งมีมากกว่า 900 แบบที่สามารถนำไปพัฒนาให้เข้ากับบอร์ดได้ นอกจากนี้ก็ยังมี library หรือโปรแกรมที่เอาไปสามารถนำไปประยุกต์ใช้ได้ทันทีไม่ต้องเขียนโปรแกรมใหม่ทั้งหมดมากกว่า 10,000 รายการ ซึ่งเราจะใช้ platformio เป็นเครื่องมือหลักในการเขียนโปรแกรม
### สรุปการทดลอง
**01 run example 1** เป็นการเขียนโปรแกรมด้วย platformio เพื่อไมโครคอนโทรลเลอร์ ใช้ในการทดสอบ มีสองส่วน คือส่วนที่เป็น setup รันครั้งเดียว และส่วนที่เป็น loop เพิ่มตัวแปรเคาท์ขึ้นเรื่อยๆ โดยที่แสดงผลตัวเคาท์ 1วินาที
**02 run example 2** เพื่อรันโปรแกรมบนไมโครคอนโทรลเลอร์ esp-01 โดยที่โปรแกรมมี 2 ส่วน ส่วน setup คือเตรียม set WiFi ให้พร้อมทำงาน และส่วน loop โดยแสดงผลเริ่มต้นว่า "เริ่มต้นสแกนหา WiFi" เมื่อได้ WiFi ก็ให้แสดงผลว่ารอบตัวมี WiFi อยู่เท่าไหร่
**03 run example 3** เป็นการรันโปรแกรมที่ต้องการสัญญาณออกไปภายนอกคอมพิวเตอร์ esp-01 ตัวนี้มี output port และ input port พอร์ตเลข 0 และ 1 ซึ่งการนำพอร์ตไปใช้งานเราจะเสียบผ่าน อะแดปเตอร์ สายพอร์ต 0 สีขาว พอร์ต 1 สีเหลือง เพื่อให้พอร์ต0เห็นได้ด้วยตาจึงต่อ led เปล่งแสง โปรแกรมทำหน้าที่ set ให้พอร์ต 0 เป็น output Loop คือนับเคาท์เพิ่มขึ้นไปเรื่อยๆ ดีเลย์ทุก ครึ่งวินาที 500 millisec ถ้าเคาท์เป็นเลขคี่ให้ on ส่งค่า 1 (HIGH) ไป 0 ถ้าเคาท์เป็นเลขคู่ให้ off ส่งค่า 1 (LOW) ไป 0
**03 run relay** เป็นการเอาโปรแกรมที่ถูกเก็บและรันอยู่ในไมโครคอนโทรลเลอร์ไปรันเพื่อใช้งานจริง โดยใช้รีเลย์ นำไมโครคอนโทรลเลอร์มาเสียบที่รีเลย์ ให้ส่งสัญญาณไปที่คอลโทรลรีเลย์เพื่อเปิด-ปิดสวิทช์
**04 run example 4** เป็นการทดลองนำสัญญาณ input จากภายนอกเข้ามาในไมโครคอนโทรลเลอร์ ส่วน set up โดยเซ็ตให้พอร์ต 0 input (สีขาว) และ port 2 เป็น output (สีเหลือง) ส่วน loop อ่านข้อมูลจากพอร์ต 0 และแสดงผลว่าอ่านได้เท่าไหร่ จากนั้นเช็คว่า ถ้าเป็น 1 ให้ LOW ไปที่พอร์ต 2 (ไฟดับ) ถ้าเป็น 0 ให้ HIGH ไปที่พอร์ต 2 (ไฟติด) ดังนั้นสัญญาณ input จากพอร์ต 0 เป็นตัวควบคุมให้ไฟเปิดหรือปิด
**05 run wifi** เป็นการทดลองโปรแกรมเว็บเซิร์ฟเวอร์ผ่านไวไฟ เนื่องจากต้องต่อกับไวไฟ จึงต้องใส่ชื่อ WiFi ssid และรหัสผ่าน  ส่วน setup ประมาณบรรทัดที่ 15 ถึง 22 ของโปรแกรมเป็นการ connect กับไวไฟที่เราเลือกไว้ หลังจากนั้นก็ setup web server ของเรา ถ้ามีการเชื่อมโยงก็จะแสดงผลว่า "Hello cnt: "โดยที่เราจะเอาเคาท์ตัวเดิมบวกหนึ่งขึ้นเรื่อยๆ
**06 run wifi AP** โปรแกรมนี้เป็นโปรแกรมที่ใช้ wifiแต่ต่างจากตัวอย่างที่ 5 ตรงที่โปรแกรมนี้สร้าง WiFi access ขึ้นมาเอง ในส่วนของโปรแกรมเราต้องกำหนดชื่อ WiFi กำหนด IP address gateway และ subnet เริ่มจากเตรียม web server แล้วก็สร้าง access point โดยการรันคำสั่ง soft access point กำหนด ss ID และ password ลงไป แล้วบอกว่าตั้ง IP เป็นที่เท่าไหร่ จากนั้นเริ่มอัพโหลดโปรแกรมลงในไมโครคอลโทรลเลอร์ 
