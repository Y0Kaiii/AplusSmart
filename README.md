# A+ Smart Solution (Commission & PO Management)

**A+ Smart Solution** เป็นโปรแกรมเดสก์ท็อปสำหรับจัดการและคำนวณค่าคอมมิชชั่นของฝ่ายขาย และจัดการใบสั่งซื้อ (Purchase Order) ของฝ่ายจัดซื้อ สร้างขึ้นด้วยภาษา Python และใช้ฐานข้อมูล PostgreSQL

---

## ✨ คุณสมบัติหลัก (Features)

* **ระบบ Login:** แยกตามแผนกและสิทธิ์การใช้งาน (Sale, Purchasing, HR, Manager, Director)
* **ฝ่ายขาย (Sales):**
    * บันทึกข้อมูล Sales Order (SO)
    * นำส่งข้อมูลเพื่อขออนุมัติและคำนวณค่าคอม
    * ดูประวัติการบันทึกและสถานะ
* **ฝ่ายจัดซื้อ (Purchasing):**
    * รับ SO เพื่อสร้างใบสั่งซื้อ (PO)
    * ส่ง PO เพื่อขออนุมัติตามลำดับขั้น
    * พิมพ์ใบปะหน้าสำหรับ SO/PO
* **ฝ่ายบุคคล (HR):**
    * ตรวจสอบและเปรียบเทียบข้อมูล SO เทียบกับข้อมูลจาก Express
    * ยืนยันข้อมูลและเลือกตัวคูณต้นทุน (Cost Multiplier)
    * ประมวลผลและคำนวณค่าคอมมิชชั่น
    * ดู Dashboard และรายงานสรุป
    * บันทึกข้อมูลประจำปี (Annual Archive) ไปยังไฟล์ Excel
* **ฝ่ายบริหาร (Manager/Director):**
    * ดูภาพรวมและ Dashboard
    * อนุมัติ/ปฏิเสธใบสั่งซื้อ (PO)

---

## 🛠️ เทคโนโลยีที่ใช้ (Tech Stack)

* **ภาษา (Language):** Python
* **หน้าจอ (GUI):** CustomTkinter, Tkinter
* **จัดการข้อมูล (Data Handling):** Pandas
* **ฐานข้อมูล (Database):** PostgreSQL
* **สร้างไฟล์เอกสาร (Document Generation):** ReportLab (สำหรับ PDF), OpenPyXL (สำหรับ Excel)

---

## 🚀 วิธีการติดตั้งและใช้งาน (Installation & Setup)

###  Prerequisites (สิ่งที่ต้องมีก่อนติดตั้ง)
- Python 3.10+
- PostgreSQL Database Server

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Aprimeplus/AplusSmart.git](https://github.com/Aprimeplus/AplusSmart.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd AplusSmart
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Run the application:**
    ```bash
    python main_app.py
    ```

---
📸 ภาพหน้าจอ (Screenshots)
<img width="482" height="655" alt="image" src="https://github.com/user-attachments/assets/afbeec7b-15ac-4a2f-9357-dad90e1c704e" />

<img width="1897" height="1011" alt="image" src="https://github.com/user-attachments/assets/ceabfa4e-5074-4a76-b07b-2b618459a416" />

<img width="1912" height="1013" alt="image" src="https://github.com/user-attachments/assets/f2d752fa-81eb-4c6f-8876-9589b465f2f1" />

<img width="1919" height="928" alt="image" src="https://github.com/user-attachments/assets/8d0da970-630d-413e-8e48-2cef14f276ab" />

<img width="1904" height="1016" alt="image" src="https://github.com/user-attachments/assets/3456692c-40e8-4a47-b924-34efbf4d56d7" />


