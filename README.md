# 🍲 Foodran - วันนี้กินอะไรดี?

Foodran คือ Web Application (PWA) แบบ Lightweight สำหรับสุ่มเมนูอาหารไทยยอดฮิต (ที่หากินง่าย) ออกแบบมาให้มี UI/UX ที่สะอาดตา สไตล์ Modern Minimalist และทำงานได้เหมือนแอปพลิเคชันมือถือ (Native App) จริงๆ 

จุดเด่นของโปรเจกต์นี้คือการใช้ **Google Sheets** เป็นฐานข้อมูล ทำให้สามารถเพิ่มหรือลดเมนูอาหารได้ตลอดเวลาผ่านมือถือ โดยไม่ต้องกลับมาแก้โค้ดหรือ Deploy ใหม่

## ✨ Features (ฟีเจอร์เด่น)

- 📱 **PWA Ready:** รองรับการติดตั้งลงบน Home Screen (iOS/Android) ใช้งานได้เหมือนแอปจริง ไม่มีแถบ URL กวนใจ
- 🎨 **Minimalist UI:** ดีไซน์สะอาดตา พร้อม Loading Splash Screen และ Animation การสุ่มที่ลื่นไหล
- 📊 **No-Backend (Google Sheets CMS):** ใช้ Google Sheets เป็นฐานข้อมูล อัปเดตเมนูอาหารได้แบบ Real-time
- ⚡ **Lightweight:** ไฟล์เดียวจบ ไม่พึ่งพา Framework หรือ Build tools ที่ซับซ้อน โหลดเร็วสุดๆ
- 📳 **Haptic Feedback:** รองรับระบบสั่นบนมือถือ Android เมื่อกดปุ่มสุ่ม เพิ่มประสบการณ์การใช้งานที่สมจริง

## 🛠️ Tech Stack

- **Frontend:** HTML5, Vanilla JavaScript
- **Styling:** Tailwind CSS (via CDN)
- **Database/CMS:** Google Sheets (Publish as CSV)
- **PWA:** `manifest.json` & Service Worker

## 🚀 How to Setup (วิธีติดตั้งและใช้งาน)

1. **Clone repository:**
   ```bash
   git clone [https://github.com/yourusername/foodran.git](https://github.com/yourusername/foodran.git)