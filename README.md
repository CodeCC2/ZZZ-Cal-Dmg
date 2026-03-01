# ⚡ ZZZ Cal DMG (Zenless Zone Zero Damage Calculator)



เว็บแอปพลิเคชันสำหรับคำนวณทฤษฎีดาเมจ (Theorycraft) ของเกม **Zenless Zone Zero (ZZZ)** ช่วยให้ผู้เล่นสามารถประเมินและคำนวณตัวเลขความเสียหายแบบ CRIT ที่จะเกิดขึ้นจริงในเกมจากการปรับแต่งสเตตัสต่างๆ ได้อย่างง่ายดาย

> **Disclaimer:** *Reverse-Engineered (โม้เหม็น) จากดาเมจจริงในเกม (ไม่ตรง)* 😂 โปรแกรมนี้จัดทำขึ้นเพื่อเป็นแนวทางในการปั้นตัวละครและคำนวณสเตตัสเบื้องต้นโดย **Avatar Shunguang** ---

## 📸 พรีวิวการใช้งาน (Previews)

คุณสามารถดูตัวอย่างการคำนวณดาเมจในสเตตัสและเงื่อนไขต่างๆ ได้จากรูปด้านล่างนี้:

### Guardian MK II Lv.70 (DEF 857.5)
![Guardian MK II Lv70](https://github.com/user-attachments/assets/7d4f1ef1-ba27-4f24-aa56-8d6022d75fb4)


### Guardian MK II Lv.10 (DEF 101.5)
![Guardian MK II Lv10](https://github.com/user-attachments/assets/37b9f066-e5b4-40d6-9963-053eff3ff3d0)

### Guardian MK II Lv.10 (DEF 101.5) - ใส่จ้าวเพิ่ม DMG 40%
![Guardian MK II Lv10 Buffed]![26](https://github.com/user-attachments/assets/31ca644b-b31c-418a-9626-d05198f16499)


### Wanted Enforcer Lv.70 (DEF 794)
![Wanted Enforcer Lv70]![27](https://github.com/user-attachments/assets/518adf6e-49a4-480a-9a86-103ea71850c0)


---

## 🛠️ ฟีเจอร์หลัก (Features)

ระบบถูกออกแบบมาให้ครอบคลุมตัวแปรหลักที่มีผลกับดาเมจในเกม โดยแบ่งออกเป็น 4 ส่วน:

* **⚔️ สเตตัสโจมตี (ATK):** * เลเวลตัวละคร (Level)
    * พลังโจมตีรวม (Total ATK)
    * ตัวคูณสกิล (Skill Multiplier %)
* **🎯 โบนัส & คริติคอล:** * อัตราคริ (CRIT Rate %)
    * ความแรงคริ (CRIT DMG %)
    * โบนัสความเสียหายรวม (Combat DMG %)
* **🛡️ ศัตรู & ตัวคูณเกราะ:** * พลังป้องกันพื้นฐานของศัตรู (Base DEF)
    * ลด/เจาะเกราะ (Flat PEN)
    * อัตราการเจาะเกราะ (PEN Ratio %)
    * ตัวคูณสตั้น (Stun Multiplier %)
* **🔵 ความต้านทาน (RES):** * การแพ้ธาตุ (Base RES %)
    * การทะลวงต้านทาน (RES Ignore %)
    * ลดป้องกัน (DEF Shred %)
    * มอนสเตอร์รับ DMG เพิ่ม (DMG Taken Inc %)

นอกจากนี้ยังมี **Theorycraft Log** ที่คอยสรุปค่า DEF แท้จริง, RES แท้จริง และตัวคูณต่างๆ เพื่อให้สายวิเคราะห์ข้อมูล (Data Miner) ดูรายละเอียดเชิงลึกได้ง่ายขึ้น

---

## 🚀 วิธีการใช้งาน (Getting Started)

เนื่องจากโปรเจกต์นี้เขียนด้วย HTML, CSS และ JavaScript ล้วน คุณสามารถใช้งานได้ทันทีโดยไม่ต้องติดตั้งไลบรารีเพิ่มเติม
