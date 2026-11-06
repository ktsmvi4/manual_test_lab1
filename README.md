# 🧪 Manual Testing Laboratory 1 — Web Registration Form

Repository นี้เป็นคลังเก็บเอกสารและผลการทดสอบระบบฟอร์มลงทะเบียนสมาชิกใหม่ (`index.html`) ด้วยกระบวนการ **Manual Software Testing** ตามมาตรฐาน Testing Lifecycle ครบถ้วนทั้ง 4 ขั้นตอน

---

## 📁 Repository Structure
* **`index.html`** : ซอร์สโค้ดฟอร์มลงทะเบียนที่ได้รับการปรับปรุงการ validation แล้ว[cite: 8]
* **`Test_case_lab1.csv`** : ชุด Test Suite / Test Database ทั้ง 7 เคส (Positive, Negative & Boundary Values)[cite: 8]
* **`Summary_report.pdf`** : เอกสารสรุปผลการทดสอบ และ Bug Report ฉบับสมบูรณ์จาก Notion[cite: 8]

---

## 📈 Test Execution Summary
* **Total Test Cases:** 7 Cases
* **Pass Rate:** 100% (7 Passed / 0 Failed)
* **Defect Logged & Fixed:** 1 Issue (TC-06: Full Name Special Character Validation)
* **Status:** Resolved & Retested Passed

---

## 🛠️ Testing Coverage & Techniques
1. **Positive Testing:** ทดสอบการกรอกข้อมูลที่ถูกต้องตามเงื่อนไข
2. **Negative Testing:** ทดสอบการเว้นช่องว่าง และการใส่อักขระที่ไม่ได้รับอนุญาต
3. **Boundary Value Analysis (BVA):** ทดสอบขอบเขตตัวเลขในฟิลด์อายุ (`min=18`, `max=60`)
4. **Defect Management:** การออก Bug Report, ติดตามการแก้ไขโค้ด Regex `pattern`, และทำการ Re-test เพื่อปิดตั๋ว
