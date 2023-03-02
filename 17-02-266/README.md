
1) กำหนดให้ VPC มี CIDR range 10.0.0.0/8 จงออกแบบ subnet(vswitch) โดยให้เหลือจำนวน Available IPs น้อยที่สุด
 (ออกแบบให้สามารถมีการขยายระบบได้)
![1_1](https://user-images.githubusercontent.com/110074022/222391329-ecb33cac-294a-412c-8b4b-d9d5b02fa282.png)
2) กำหนดให้ VPC มี CIDR range 172.31. 0.0/16 จงออกแบบ subnet(vswitch) โดยให้เหลือจำนวน Available IPs น้อยที่สุด
 (ออกแบบให้สามารถมีการขยายระบบได้)!
 [Uploading 1_2.png…]()
 ==========================
 3) จากคำตอบข้อ 1 และ 2 ให้ตอบคำถามย่อยต่อไปนี้
3.1)ต้องใช้ Service อะไรที่ทำให้ VPC จากข้อที่ 1 และ 2 สามารถรับส่งข้อมูลถึงกันได้

Service ที่ต้องใช้คือ VPC Peering เพื่อนำ Peering-id นำไปกำหนดใน Route Table
