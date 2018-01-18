# What is Git ???

## Git
คือ Version Control แบบ Distributed ตัวหนึ่ง เป็นระบบที่ใช้จัดเก็บและควบคุมการเปลี่ยนแปลงที่เกิดขึ้นกับไฟล์ชนิดใดก็ได้ ไม่ว่าจะเป็น Text File หรือ Binary File (จากนี้จะขอเรียก Text File หรือ Binary File รวมกันว่า Source Code)

## คำสั่งพื้นฐานต่างๆที่ใช้เป็นประจำเกี่ยวกับ Git
คำสั่งต่างๆ ที่ใช้ภายใน git สามารถรันได้ผ่าน Terminal หรือ Cmd ที่มีการลง git ไว้ภายในเครื่อง
* 1. $git config เป็นคำสั่งที่ใช้แสดงและกำหนดข้อมูลของผู้ใช้เพื่อระบุตัวตน และคุณสมบัติอื่นๆ ของ Git เช่น                                         
  $git config --global user.name "Saharat Chanthip"                                        
  $git config --global user.email "5835512024@psu.ac.th"
* 2. $git init เป็นคำสั่งที่ใช้สร้างระบบของ Git ขึ้นมาภายใต้โฟลเดอร์หรือ Path นั้น โดยจะสร้างโฟลเดอร์ .git ขึ้นมาเพื่อใช้เก็บ สำรองข้อมูล การเปลี่ยนแปลงและคุณสมบัติอื่นๆ ของ Git
* 3. $git status เป็นคำสั่งที่ใช้ตรวจสองสถานะของ Source Code ในระบบของ Git ซึ่งจะแสดงสถานะดั่งที่ได้อธิบายข้างต้นไปแล้ว
* 4. $git add เป็นคำสั่งที่ใช้เพิ่มการเปลี่ยนแปลงของ Source Code เข้าไปที่สถานะ Staged เหมือนดังในห้องที่ทำการ Add ไฟล์ README.md เข้ามาใน git
* 5. $git commit เป็นคำสั่งที่ใช้ยืนยัน Source Code ที่อยู่ในสถานะ Staged เข้าไปเก็บไว้ที่ Local Repository เช่น  
 $git commit -m "first commit"
* 6. $git remote เพิ่ม URL ของ Remote Repository เข้าไปยังคุณสมบัติของ Git โดยชื่อว่า origin เช่น
 $git remote add origin https://github.com/SaharaT024/HomeWork01.git
* 7. $git push เป็นคำสั่งที่ใช้ส่งการเปลี่ยนแปลงของ Source Code ที่เก็บอยู่บน Local Repository ขึ้นไปยัง Remote Repository เช่น
 $git push -u origin master 

## คำสั่งอื่นๆที่ใช้ใน Terminal หรือ Cmd 
* $cd คือการเข้าไปใน Folder นั้นๆตามที่เราต้องการ เช่น
  cd github 
  แต่ถ้าต้องการออกจาก Folder นั้นๆ ก็เพียงแค่พิม cd อย่างเดียวก็จะสามารถออกมาได้
* $clear คือ การล้างหน้าคำสั่งต่างๆที่พิมไว้ใน Cmd ทำให้หน้าจอวางเปล่าเหลือแค่บรรทัดที่รับคำสั่ง
