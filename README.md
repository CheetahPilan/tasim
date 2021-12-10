# tasim
`Final presentation

ปิลันธน์ อุทัยพิบูลย์ 62340500033 ขั้นตอนการใช้งาน

ใช้คำสั่ง roscore ใน terminal<br/>
เปิด terminal ใหม่ใช้คำสั่ง source catkin_ws/devel/setup.bash<br/>
ใช้คำสั่ง roslaunch tasim nav.launch<br/>
เปิด terminal ใหม่ใช้คำสั่ง source catkin_ws/devel/setup.bash<br/>
ใช้คำสั่ง roslaunch tasim launch.launch<br/>
เปิดโปรแกรม Rviz จะเห็น World และหุ่นยนต์<br/>
ใช้คำสั่ง 2D Nav Goal จากนั้น คลิกตำแหน่งที่ต้องการให้หุ่นไป<br/>
สรุป หลังจากที่ได้ลองทำโปรเจกต์นี้ทำให้มีความเข้าใจในการทำงาน และการใช้งาน 
ROS มากขึ้น ทำงานโดยการเชื่อมต่อ Node เข้าด้วยกัน มีการรับส่งข้อมูลระหว่างกัน 
ได้เรียนรู้เกี่ยวกับการสร้าง world ด้วย gazebo สร้าง Launch file ที่ใช้สำหรัยเปิด 
world รวมถึงการทำ gmapping, navigation ทำให้สามารถกำหนดตำแหน่งที่จะให้หุ่นยนต์เคลื่อนที่ไปตามที่ต่างๆได้
