# tasim
`Final presentation

ปิลันธน์ อุทัยพิบูลย์ 62340500033 ขั้นตอนการใช้งาน

ใช้คำสั่ง roscore ใน terminal
เปิด terminal ใหม่ใช้คำสั่ง source catkin_ws/devel/setup.bash
ใช้คำสั่ง roslaunch tasim nav.launch
เปิด terminal ใหม่ใช้คำสั่ง source catkin_ws/devel/setup.bash
ใช้คำสั่ง roslaunch tasim launch.launch
เปิดโปรแกรม Rviz จะเห็น World และหุ่นยนต์
ใช้คำสั่ง 2D Nav Goal จากนั้น คลิกตำแหน่งที่ต้องการให้หุ่นไป
สรุป หลังจากที่ได้ลองทำโปรเจกต์นี้ทำให้มีความเข้าใจในการทำงาน และการใช้งาน 
ROS มากขึ้น ทำงานโดยการเชื่อมต่อ Node เข้าด้วยกัน มีการรับส่งข้อมูลระหว่างกัน 
ได้เรียนรู้เกี่ยวกับการสร้าง world ด้วย gazebo สร้าง Launch file ที่ใช้สำหรัยเปิด 
world รวมถึงการทำ gmapping, navigation ทำให้สามารถกำหนดตำแหน่งที่จะให้หุ่นยนต์เคลื่อนที่ไปตามที่ต่างๆได้
