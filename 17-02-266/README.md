
1) กำหนดให้ VPC มี CIDR range 10.0.0.0/8 จงออกแบบ subnet(vswitch) โดยให้เหลือจำนวน Available IPs น้อยที่สุด
 (ออกแบบให้สามารถมีการขยายระบบได้)
![1_1](https://user-images.githubusercontent.com/110074022/222391329-ecb33cac-294a-412c-8b4b-d9d5b02fa282.png)
2) กำหนดให้ VPC มี CIDR range 172.31. 0.0/16 จงออกแบบ subnet(vswitch) โดยให้เหลือจำนวน Available IPs น้อยที่สุด
(ออกแบบให้สามารถมีการขยายระบบได้)
![1_2](https://user-images.githubusercontent.com/110074022/222392603-d84fa76e-260a-42e1-91f5-8a4923606a66.png)

******************************************************************************************************************************
6) Hypervisor มีกี่ประเภทแต่ละประเภทคืออะไรบ้าง แล้วประเภทไหนที่ Computerของเราใช้งานในการเปิด emulator

**มี 2 Type**
Type I : **เป็นการแบ่งระบบ OS โดยไม่ผ่านตัวกลาง (Host OS) ทำให้แต่ละ OS ที่ถูกแบ่งให้กับ Guest นั้นสามารถเข้าถึงระบบได้อย่างเต็มที่ ตามขนาดและขอบเขตที่ได้กำหนดไว้**

Type II : **เป็นประเภทที่เราได้ใช้กันอยู่ประจำ เช่นการจำลอง OS บน OS ที่เราใช้อยู่ เช่น จำลอง Android บน Windows เป็นต้น จะเห็นได้ว่าเราสามารถจำลองระบบได้แต่ยังคงต้องผ่าน OS ที่เราใช้งานอยู่ ทำให้ประสิทธิภาพที่ได้ออกมานั้น ไม่เต็มที่**

ประเภทไหนที่ Computerของเราใช้งานในการเปิด emulator : **Hypervisor Type II**

******************************************************************************************************************************
8) ให้ตอบคำถามต่อไปนี้เกี่ยวกับ Debian

8.1)Debian คืออะไร **Debian เป็นระบบปฏิบัติการที่เป็นการพัฒนาขึ้นจากจากคนที่อยู่ใน Community อย่างเสรี ไม่มีบุคคลอยู๋เบื้องหลังในการพัฒนา**

8.2)version stable ล่าสุดมีชื่อเล่นว่าอะไร **Debian 11.6 "Bullseye"**

8.3)Package Manager ต้องใช้คำสั่งอะไร 
**- apt -> apt update , apt install , apt upgrade ,etc.**
**- cat /etc/os-release , cat /etc/debian_version**

8.4)หากต้องการติดตั้ง git ควรใช้คำสั่งอะไร  **apt install git**



******************************************************************************************************************************
9) ให้ตอบคำถามต่อไปนี้เกี่ยวกับ Alpine
 
9.1)Alpine คืออะไร  **Alphine เป็น Linux Distribution ที่มีขนาดเล็ก ไม่เกิน 8 mb และใช้พื้นที่โดยรวมไม่เกิน 180 mb ถูกใช้อยู่ใน Container มีความปลอดภัยสูง**

9.2)version stable ล่าสุดมีคือ version อะไร **3.17**

9.3)Package Manager ต้องใช้คำสั่งอะไร
**apk -> apk update , apk add , apk upgrade ,etc.
cat /etc/os-release , cat /etc/alpine-release**

9.4)หากต้องการติดตั้ง git ควรใช้คำสั่งอะไร
**apk add git**


******************************************************************************************************************************
10) ให้ตอบคำถามต่อไปนี้เกี่ยวกับ Amazonlinux

10.1)Amazonlinux คืออะไร  **Amazonlinux เป็น Linux Distribution ที่ถูกพัฒนาขึ้นโดย Amazon web service มีความเสถียรสูง และมีประสิทธิภาพสูง เหมาะสำหรับApplication ที่ทำงานบน Amazon EC2**

10.2)version stable ล่าสุดมีชื่อเล่นว่าอะไร  **Amazon Linux 2 2022.09.1**

10.3)Package Manager ต้องใช้คำสั่งอะไร
**yum -> yum update , yum install , yum upgrade ,etc.
cat /etc/os-release , cat /etc/system-release**

10.4)หากต้องการติดตั้ง git ควรใช้คำสั่งอะไร  **yum install git**
******************************************************************************************************************************
