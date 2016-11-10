#ใบงานที่ 5
##เรื่อง การใช้งานคำสั่ง Console.WriteLine()
##วัตถุประสงค์
1). เพื่อให้นักศึกษาบอกวิธีการใช้คำสั่งแสดงผลบน Text Mode ในภาษา C# ได้
2). เพื่อให้นักศึกษาสามารถปรับแต่งคำสั่งแสดงผลทางหน้าจอตามต้องการได้

##ขั้นเตรียมการทดลอง
1). สร้าง Project ตั้งชื่อเป็น Lab5 เพื่อทดลองการใช้งานคำสั่ง Console.WriteLine()
ลำดับขั้นการทดลอง
(หมายเหตุ ในรูปประกอบที่มี namespace เป็น Lab4 รบกวนแก้เป็น Lab5 ด้วยครับ)
2). ทดลองเรื่องจำนวนของอาร์กิวเมนต์ในคำสั่ง Console.WriteLine()

 2.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic1.png)

  2.2). รันโปรแกรม และบันทึกผลที่ได้

ผลที่ออกมาได้ จะมีคำว่า This is text 1 บรรทัดถัดไป คือ This is text 2 บรรทัดที่3 คือ this is text 3
![](https://github.com/rungtip214/LAB-05/blob/master/img/Capture01.PNG?raw=true)

 2.3). แก้โปรแกรมตามรูปด้านล่างนี้
 
  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic2.png)

 2.4). รันโปรแกรม และบันทึกผลที่ได้

ผลที่ออกมาได้ คือ เลข 3 อยู่ในตำแหน่งที่ 0 และเลข 6 อยู่ในตำแหน่งที่ 1

![](https://github.com/rungtip214/LAB-05/blob/master/img/Capture02.PNG?raw=true)




###คำถาม 5.1 เครื่องหมาย { }  ในคำสั่ง Console.WriteLine() มีลักษณะการใช้งานอย่างไร

ใช้งานโดยการดึงข้อมูลในตำแหน่งนั้นๆออกมา เช่น กำหนดให้ Console.WriteLine( "{0} {1}", 5, 9); โดยเลข 5นั้น หมายความว่าเป็นข้อมูลตำแหน่งที่0 และเลข 9นั้น หมายความว่าเป็นข้อมูลตำแหน่งที่ 1 ดังนั้น ผลที่ออกมา คือ 5 9

###คำถาม 5.2  ถ้ามีการใช้ตัวเลขใน { } ที่กระโดด เช่น {0} {2} {3} จะใช้งานได้หรือไม่ อย่างไร จงอธิบาย

ใช้ไม่ได้ในกรณีที่ข้อมูลมีไม่ถึงกำหนด เช่น Console.WriteLine(" {0} {2} {3}", 3, 6); จะได้รูปดังนี้

![](https://github.com/rungtip214/LAB-05/blob/master/img/Capture03.PNG?raw=true)
 
 2.5). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic3.png)

 2.6). รันโปรแกรม และบันทึกผลที่ได้
 
สามารถนำข้อมูลในตำแหน่งนั้นๆมาใช้ซ้ำได้ ดังรูปนี้

![](https://github.com/rungtip214/LAB-05/blob/master/img/Capture04.PNG?raw=true)

3). ทดลองเรื่องการกำหนดความกว้างของอาร์กิวเมนต์

  3.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic4.png)

  3.2). รันโปรแกรม และบันทึกผลที่ได้

จากการทดลอง การเว้นบรรทัดสามารถทำได้โดยการเว้นในเครื่องหมาย ""ได้ และยังสามารถเว้นวรรคโดยการกำหนดในเครื่องหมาย { , } จะได้รูปดังนี้

![](https://github.com/rungtip214/LAB-05/blob/master/img/Capture05.PNG?raw=true)

###คำถาม 5.3 การกำหนดความกว้างของอาร์กิวเมนต์ด้วยเครื่องหมาย { , }  ในคำสั่ง Console.WriteLine() มีรูปแบบการใช้งานอย่างไร

สามารถใช้งานให้เว้นวรรคโดยการระบุตำแหน่งของข้อมูล และตำแหน่งการเว้นวรรคที่ต้องการ


4). ทดลองเรื่องการกำหนดรูปแบบของอาร์กิวเมนต์
  4.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic5.png)

  4.2). รันโปรแกรม และบันทึกผลที่ได้
![](https://github.com/rungtip214/LAB-05/blob/master/img/Capture06.PNG?raw=true)

5). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของอาร์กิวเมนต์
  5.1). แก้โปรแกรมตามรูปด้านล่างนี้
 
 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic6.png)

  5.2). รันโปรแกรม และบันทึกผลที่ได้
  
  ![](https://github.com/rungtip214/LAB-05/blob/master/img/Capture07.PNG?raw=true)

6). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์
  6.1). แก้โปรแกรมตามรูปด้านล่างนี้

 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic7.png)

  6.2). รันโปรแกรม และบันทึกผลที่ได้
  
  ![](https://github.com/rungtip214/LAB-05/blob/master/img/Capture08.PNG?raw=true)

## แบบฝึกหัด จงระบุ output ของบรรทัดคำสั่งต่อไปนี้

```csharp
1.  string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
2.    Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
3.    Console.WriteLine("Hello " + "World");
4.    Console.WriteLine("Here comes a slash \\");
5.    Console.WriteLine("|{0, 10}|", 999);
6.    Console.WriteLine("|{0,-10}|", 000);
7.    Console.WriteLine("The value: {0}.", 500);
8.    Console.WriteLine("The value: {0:C}.", 500);
9.    Console.WriteLine("{0,-10:F4}", 12.3456789);
10.   Console.WriteLine("{0,-10:C}", 12.3456789);
11.   Console.WriteLine("{0,-10:E3}", 12.3456789);
12.   Console.WriteLine("{0,-10:x}", 65535);
13.   Console.WriteLine("{0,-10:X}", 65535);
14.   int i; 
      Console.WriteLine("Value\tSquared\tCubed"); 
      for(i = 1; i < 10; i++) 
          Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i); 
15.    Console.WriteLine("{0:#.###}.", 1234.56789);
```
