TEST HTML&CSS For JDK12
1.ดาวน์โหลดไฟล์รูปภาพวิดีโอมาจัดเก็บใน และสร้างโฟลเดอร์ที่จัดเตรียมเอาไว้่
    • pictures
    • videos

2.เปิดไฟล์งานที่ต้องทำ เพื่อดูตัวอย่างเนื้องานที่ต้องทำ
    • C:\Users\User\jsd12\16_MONTRI_COLMAR\ex_work
    • ไฟล์ตัวอย่างงานที่ต้องทำ "colmar-academy-spec"
3.สร้างไฟล์งาน HTML และ CSS ในโปรเจค
    • โฟลเดอร์โปรเจค "16_MONTRI_COLMAR"  
        • pictrures
        • videos
        • ex_work
        • index.html
        • style.css
4.ดู ไฟล์งาน แล้วดูโครงว่าต้องส่วนไหนก่อน โดยเริ่มแรกจะสร้างส่วนกล่อง <header></header> ที่ส่วน css :Body และ header {} ที่ไฟล์ style.css
        • index.htmal 
            1.สร้าง ข้อมูลที่แสดงในส่วน Header ก่อน
            <header>สร้างข้อมูลที่จะแสดงในส่วนของ Header ก่อน เพื่อให้ขูอมูลนี้แสดง เมื่อเราทำการแก้ไข CSS
                <div id="logo_header" class="logo_header"><img src="../16_MONTRI_COLMAR/pictrures/ic-logo.svg" alt="Logo"></div>
                <div id="n_comany_1" class="n_comany_1">COLMAR</div>
                <div id="n_comany_2" class="n_comany_2">ACADEMY</div>
                <nav>
                    <ul>
                        <li><a href="#">On campus</a></li>
                        <li><a href="#">Online</a></li>
                        <li><a href="#">For companies</a></li>
                        <li><a href="#">Sign in</a></li>
                    </ul>
                </nav>
            </header>
            
        • style.css สร้าง Style ในส่วนของข้อมูล Header ทั้งหมด โดยกำหนดเป็นบล็อคๆ ของข้อมูลนั้นๆ
        body {
            กำหนดค่าความกว้าง ของเว็บ บนหน้าจอ Large Desktop และค่าพื้นฐานต่างๆ 
        }
        heder {
         สร้างบล็อคใหญ่ ให้รองรับ 2 บล็อค  
        }
        