###ติดตั้ง node.js
จากนั้น cd เข้ามายัง พาร์ทนี้
__________________________________
|   application                   |
|   assets                        |
|   system                        |
|   .htaccess                     |
|   index.php                     |
|   composer.json                 |
|   package.json                  |
|   คุณอยู่ตรงนี้     <----------     |
|__________________________________ 

จากนั้นเรียก cmd ขึ้นมาใช้คำสั่งด้านล่าง
$npm install

ระบบจะดาวน์โหลด mode_modules ที่ใช้งานใน โปรเจคให้เอง
เมื่อต้องการดาวน์โหลดไลบรารี่เพิ่มใช้คำสั่ง 

$npm install ชื่อแพกเกจ --save

เสมอ
อย่าลืม config โปรเจคให้เหมาะสมกับงานของคุณเองนะ
ปล. Codeigniter ใช้ Libary Template ในการโหลดวิวด้วยนะ 
ดูการใช้งานเพิ่มเติม https://jeromejaglale.com/doc/php/codeigniter_template
