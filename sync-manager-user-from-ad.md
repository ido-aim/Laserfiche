ส่วน Directory server

1\. Remote เข้า server lsf 192.168.0.19

2\. เปิด lsf directory server (webapp)

3\. กดแถบ Account &gt; Users

4\. กดปุ่ม + Users เลือก Windows Active Directory User

5\. ในหน้า Create User กดปุ่ม Register directory user(s) ทางขวามือ

6\. ในช่อง search ให้ใส่รหัสพนักงานที่ต้องการเพิ่มลงไป (หรือใส่ dth ก็ได้ในกรณีที่ต้องการเพิ่มหลายคน)

7\. หลังจากใส่และกด Search จะมีหน้าต่างขึ้นมาให้ใส่ username / password

 user : Administrator

 pass : Dittoops2016

8\. เลือก user ที่จะเพิ่มแล้วกด ok

9\. หน้า Summary เลือก role ที่จะให้กับ user (Manager เป็น Full license)

10\. กด Finish &gt; Ok

ส่วน form

1\. เข้า http://ditto-hq01.dnsalias.org:8889/Forms ด้วย user Admin

2\. ขวาบน Admin &gt; Administration

3\. กดปุ่ม Synchronize users เพื่อทำการนำ user ที่เราเพิ่งเพิ่มใน directory server มายัง form

(บางที users ไม่มาต้องรอสักพักหรือ restart services &gt; laserfiche directory server รอสักพักแล้ว sync ใหม่)

4\. เมื่อ user เข้าที่ named users แล้วให้กดแถบ Team Management ขวามือเพื่อทำการตั้งค่า role ของ user นั้น

5\. เข้าไปที่ ApproverDept เพื่อเพิ่มสิทธิในการอนุมัติ(ในกรณีที่ user เป็น Manager)

6\. กด Add&gt;User ใส่ user ที่ต้องการเพิ่ม เลือก Team manager/Team member

7\. เลือก Roles ตามแผนกของ User และกด Add

ส่วน Repository (ในกรณีเป็นแผนกใหม่ที่ยังไม่มีการสร้างไว้ใน Repository)

1\. เข้า http://ditto-hq01.dnsalias.org:8889/laserfiche (อย่าลืมใส่ :8889) ด้วย user Admin

2\. โฟลเดอร์ด้านซ้ายมือ ให้เลือกโฟลเดอร์ แผนกของ User &gt; คลิกขวา Show Security

3\. ช่อง Add trustee เลือกเพิ่มแผนกนั้นลงไป