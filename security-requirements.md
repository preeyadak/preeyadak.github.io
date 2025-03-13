 # 12.6.1 | SSRF Protection 🧨

---

### Description
* Verify that the web or application server is configured with an allow list of resources or systems to which the server can send requests or load data/files from.

### ChatGPT
* การกำหนดให้เว็บเซิร์ฟเวอร์หรือแอปพลิเคชันเซิร์ฟเวอร์สามารถส่งคำขอหรือโหลดข้อมูลจากแหล่งที่ได้รับอนุญาตเท่านั้น (Allow List) เพื่อลดความเสี่ยงจากการโจมตีแบบ Server-Side Request Forgery (SSRF)

### Gemini
* การป้องกันการโจมตีแบบ Server-Side Request Forgery (SSRF) โดยการตรวจสอบว่าเว็บหรือแอปพลิเคชันเซิร์ฟเวอร์มีการกำหนดรายการที่อนุญาต (allow list) ของทรัพยากรหรือระบบที่เซิร์ฟเวอร์สามารถส่งคำขอหรือโหลดข้อมูล/ไฟล์จากได้
  
---

### 💭 My Opinion
* เป็นการกำหนดให้เซิร์ฟเวอร์สามารถส่ง Request ไปยังเฉพาะแหล่งที่ได้รับอนุญาตเท่านั้น
  
---

### Simple Daily Life
* **เพื่อนในโซเชียลมีเดีย**
    ปกติ : เราตั้งค่า Facebook หรือ IG ให้เห็นโพสต์ได้เฉพาะเพื่อน
    SSRF Protection : คนแปลกหน้าหรือบัญชีปลอมจะไม่สามารถเข้าถึงข้อมูลส่วนตัวของเราได้
  
