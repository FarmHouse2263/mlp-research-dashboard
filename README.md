# MLP Research Classifier

หน้าเว็บสรุปผลการจำแนกบทความวิชาการจาก `MODELMLP.ipynb` ทำเป็น static site พร้อม workflow สำหรับเผยแพร่ด้วย GitHub Pages

## เผยแพร่ด้วย GitHub Pages

1. สร้าง GitHub repository ใหม่ แล้วอัปโหลดไฟล์และโฟลเดอร์ทั้งหมดในชุดนี้ (รวม `.github/workflows/pages.yml`) ไปไว้ที่ root ของ repository
2. ตั้งค่า repository ให้ใช้ GitHub Actions สำหรับ Pages หาก GitHub แสดงตัวเลือก Source ใน **Settings → Pages** ให้เลือก **GitHub Actions**
3. push ไปยัง branch `main` หรือเรียก workflow **Deploy static page to GitHub Pages** ด้วยตนเองจากแท็บ Actions
4. รอ workflow สำเร็จ แล้วเปิด URL ของ Pages ที่แสดงใน deployment

หน้าเว็บอ่านได้โดยตรงจาก `index.html` และใช้ `confusion_matrix.png` ซึ่งดึงจาก output ที่ฝังอยู่ในโน้ตบุ๊กต้นฉบับ
