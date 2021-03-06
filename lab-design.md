# ระบบรดน้ำต้นไม้อัตโนมัติ
## วัตถุประสงค์
1 เพื่อศึกษาและพัฒนาการทำงานของโปรแกรมบนไมโครคอนโทรลเลอร์ Arduino UNO R3  
2 เพื่อศึกษาและพัฒนาการทำงานของเซนเซอร์วัดความชื้นในดิน  
3 สามารถพัฒนาเพื่อต่อยอดระบบการทำงานในการรดน้ำต้นไม้อัตโนมัติได้  
## อุปกรณ์
1 บอร์ด Arduino UNO R3 พร้อมสาย USB  
2 เซนเซอร์ตรวจจับความชื้นในดิน  
3 โมดูลรีเลย์ 1 Chanel 250v/10A  
4 Adapter 5v  
5 ปั๊มน้ำ DC 5v  
6 สายแพร Jumper ตัวผู้ ตัวเมีย  
7 ท่อสายยางปั๊มน้ำ 6 mm ยาว 1 เมตร  
## อธิบายวงจร
ชุดเซ็นเซอร์วัดความชื้นโดยสายสีแดงและดำคือไฟเลี้ยง 5 โวลต์กับกราวน์ สายสีเหลืองคือสัญญาที่ส่งกลับไปโดยมีค่าทางสัญญาณ 0-1023 ฉันจะแปลงเป็นค่าเปอร์เซ็นต์ความชื้น 100 ถึงศูนย์ส่วนที่สองคือปกรณ์ Adabter 5 โวลต์ วงจรรีเลย์และปั๊ม แล้วส่งสัญญาณจาก Pin 2 มาควบคุมการทำงานของรีเลย์เพื่อจ่ายไฟให้ปั๊มน้ำ ทั้งนี้สามารถแยกส่วนด้านขวาได้ โดยเอา 5 โวลต์จาก Arduno ไปจ่าย Vcc แทน แล้วให้ Adabter จ่ายไฟให้ปั๊มน้ำอย่างเดียว ขั้วบวกจากแบต เข้าขา COM อย่างเดียว แล้วต่อจาก NO ไปปั๊มแล้วต่อขั้วลบ กลับไปขั้วลบของแบต
## ตัวอย่าง code
const int analogInPin = A0;  
const int Relay = 2;  
int sensorValue = 0; 
int outputValue = 0;  
  
void setup() {  
Serial.begin(9600);  
pinMode(Relay, OUTPUT);  
}  
  
void loop() {  
sensorValue = analogRead(analogInPin);  
outputValue = map(sensorValue, 0, 1023, 100, 0);  
Serial.print(outputValue);  
Serial.println(" %");  
if (outputValue <= 40) {  
digitalWrite(Relay, HIGH);  
}  
else {  
digitalWrite(Relay, LOW);  
}  
delay(500);  
}  
## ศึกษาและค้นคว้าจาก
[APIS - Automated Plant Irrigation System](https://www.instructables.com/APIS-Automated-Plant-Irrigation-System/?=)  
[Arduino Automatic Watering System for Plants Sprinkler](https://www.instructables.com/Arduino-Automatic-Watering-System-For-Plants/)  
[ระบบรดน้ำต้นไม้อัตโนมัติโดยใช้ Arduino ควบคุมงบไม่เกิน 400บ.](https://www.ec-bot.com/article/6/%E0%B8%A3%E0%B8%B0%E0%B8%9A%E0%B8%9A%E0%B8)
