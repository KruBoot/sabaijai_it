# 💻 สบายใจไอที (Sabaijai IT) - Landing Page

เว็บไซต์หน้าเดียว (Single Page Website) สำหรับร้านขายอุปกรณ์คอมพิวเตอร์และสินค้าไอที ภายใต้สโลแกน **"สบายใจใช้เรา"** ออกแบบด้วยความเรียบง่าย (Minimalist) โทนสี ขาว-ครีม ตัดด้วยสีเขียวพาสเทล พร้อมเอฟเฟกต์ Glassmorphism และ Animation ที่ลื่นไหลตามสไตล์ Modern Material Design 3

## ✨ จุดเด่นของโปรเจกต์ (Features)
- **Single Page Application:** โค้ดทั้งหมด (HTML, CSS, JS) รวมอยู่ในไฟล์เดียว (`index.html`) สะดวกต่อการนำไปใช้งาน
- **No Frameworks:** ไม่พึ่งพาไลบรารีภายนอกหรือ Framework ใดๆ (ใช้เพียง Vanilla CSS/JS) ยกเว้นฟอนต์และไอคอน
- **Modern & Clean UI:** การออกแบบสไตล์ Material Design 3 มีการใช้เงา (Shadow) ความโค้งมน (Rounded Corners) และ Glass Effect
- **Responsive Design:** รองรับการแสดงผลทุกขนาดหน้าจอ (Desktop, Tablet, Mobile)
- **Product Filter:** ระบบจัดหมวดหมู่สินค้า 4 หมวดที่สลับไปมาได้อย่างลื่นไหล
- **Smooth Animations:** เอฟเฟกต์ Fade-in up เมื่อเลื่อนหน้าจอ (Scroll Animation) และ Hover Effect บนการ์ดสินค้า
- **No Backend / No Database:** ทำงานผ่านฝั่ง Frontend 100% ปลอดภัยและโหลดเร็วสุดๆ

## 🛠 เทคโนโลยีที่ใช้ (Technologies)
- **HTML5:** โครงสร้างเว็บ Semantic HTML
- **CSS3:** การตกแต่ง, Flexbox, CSS Grid, Variables และ Animations
- **Vanilla JavaScript:** จัดการระบบ Filter สินค้า, Scroll Animations และ Mobile Menu
- **Google Fonts:** ฟอนต์ภาษาไทย `Kanit`
- **FontAwesome (CDN):** สำหรับไอคอนส่วนต่างๆ ของเว็บไซต์

## 🚀 วิธีการใช้งาน (How to use)
1. ดาวน์โหลดหรือคัดลอกโค้ดไปบันทึกเป็นไฟล์ชื่อ `index.html`
2. ดับเบิลคลิกเปิดไฟล์ `index.html` ด้วยเว็บเบราว์เซอร์ใดก็ได้ (เช่น Google Chrome, Safari, Edge)
3. เว็บไซต์พร้อมใช้งานทันที โดยไม่ต้องติดตั้ง Server ใดๆ

## 📂 โครงสร้างภายในไฟล์ (File Structure Outline)
ตัวไฟล์ `index.html` ถูกแบ่งออกเป็นส่วนหลักๆ ดังนี้:
1. **`<style>` (CSS):** ตั้งค่าสี, รูปแบบตัวอักษร, ส่วนประกอบของ UI, และ Responsive Breakpoints
2. **`<body>` (HTML):**
   - `Navbar`: เมนูนำทางด้านบน
   - `Hero Section`: แบนเนอร์หลักและสโลแกน
   - `About`: ข้อมูลเกี่ยวกับเรา
   - `Products`: ส่วนแสดงสินค้าและปุ่มฟิลเตอร์หมวดหมู่
   - `Contact`: ข้อมูลติดต่อ และ Google Map
   - `Footer`: ลิขสิทธิ์และโซเชียลมีเดีย
3. **`<script>` (JavaScript):** ควบคุมการทำงานของปุ่มหมวดหมู่ และ IntersectionObserver สำหรับจับการเลื่อนหน้าจอ

## ✏️ การปรับแต่งและแก้ไข (Customization)
- **เปลี่ยนสีหลัก:** สามารถแก้ไขตัวแปรสีได้ที่ส่วน `:root` ในบล็อก CSS
- **เพิ่ม/ลด สินค้า:** คัดลอกบล็อก `<div class="product-card">...</div>` และแก้ไข `data-category`, URL รูปภาพ, ชื่อสินค้า, และราคา
- **แก้ไขการติดต่อ:** ไปที่ `<section id="contact">` เพื่อเปลี่ยนเบอร์โทรศัพท์, ลิงก์ Social Media หรือ Iframe ของ Google Map

---
*ออกแบบและพัฒนาโดยตำแหน่ง Senior UI/UX Designer & Front-end Developer*
