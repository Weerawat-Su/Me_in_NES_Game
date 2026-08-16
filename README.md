# COM EN NPU Boss Battle (NES Homebrew)

เกมแนว Retro Shoot 'em Up (Boss Battle) สำหรับเครื่องเล่นเกม Famicom / Nintendo Entertainment System (NES) พัฒนาด้วยภาษา C โดยใช้ไลบรารี `neslib` และออกแบบสำหรับรันบน **8bitworkshop IDE**

---

## 🎮 Features / ฟีเจอร์เด่นภายในเกม
* **Multi-Pattern Boss Attacks:** บอสมีรูปแบบการโจมตีที่หลากหลายและท้าทาย:
  * กระสุนเดี่ยวและกระสุนกระจาย (Spread Shots)
  * ระบบมิสไซลติดตามผู้เล่นระยะสั้น (Homing Missiles)
  * รูปแบบการเคลื่อนไหวและโฉบโจมตีสลับเฟส (Boss Phasing & Movement)
* **Custom 5x5 Boss Sprite:** กราฟิกบอสขนาดใหญ่ 40x40 พิกเซล (ใช้ 25 Tiles ใน VRAM) พร้อมระบบชนและ Hitbox ที่แม่นยำ
* **Retro UI System:** ระบบแสดงผลแถบเลือดบอส (HP) และพลังชีวิตผู้เล่นผ่าน VRAM Buffer แบบเรียลไทม์

---

## 🕹️ Controls / วิธีการควบคุม
* **D-Pad (ซ้าย / ขวา):** เคลื่อนที่ยานของผู้เล่น
* **Button A:** ยิงกระสุน

---

## 🛠️ Tech Stack & Requirements / เครื่องมือที่ใช้
* **Language:** C (MOS 6502 Target)
* **Libraries:** `neslib`, `vrambuf`, `bcd`, `apu`
* **Development Environment:** [8bitworkshop NES IDE](https://8bitworkshop.com/)

---

## 🚀 How to Run / วิธีการนำไปรัน
1. เปิดโปรเจกต์ใน [8bitworkshop IDE](https://8bitworkshop.com/) หรือเครื่องมือคอมไพล์ C สำหรับ NES (เช่น CC65)
2. นำโค้ดเกมไปวางในไฟล์หลักของโปรเจกต์
3. Build รอมเพื่อสร้างไฟล์ `.nes`
4. นำไฟล์รอมไปเปิดเล่นผ่าน NES Emulator ที่รองรับ (เช่น FCEUX, Mesen, หรือ Nestopia)

---
*พัฒนาขึ้นสำหรับโปรเจกต์เกมเรโทรและระบบสมองกลฝังตัว 🚀*
