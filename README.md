# Flutter Login App (Windows Build)
# แอป Flutter Login (สำหรับ Windows)

---

## 🚀 Features / คุณสมบัติ
- User login with validation  
  ระบบล็อกอินพร้อมการตรวจสอบข้อมูล  
- Windows desktop executable (`flutter_login.exe`)  
  ไฟล์รันบนวินโดวส์ (`flutter_login.exe`)  
- Required DLL for execution (`flutter_windows.dll`)  
  ต้องใช้ DLL สำหรับการทำงาน (`flutter_windows.dll`)  
- Built with **Flutter** and **Dart**  
  พัฒนาโดยใช้ **Flutter** และ **Dart**

---

## 📂 Project Structure / โครงสร้างโปรเจกต์


---

## ⚙️ Requirements / ความต้องการระบบ
- Windows 10/11 (x64)  
- Flutter SDK (if you want to build from source)  
  Flutter SDK (หากต้องการคอมไพล์ใหม่จากซอร์สโค้ด)  
- Dart SDK  

---

## ▶️ How to Run / วิธีการใช้งาน
1. Download both files:  
   ดาวน์โหลดไฟล์ทั้งสองนี้:  
   - `flutter_login.exe`  
   - `flutter_windows.dll`  
2. Place them in the **same folder**.  
   ให้วางไว้ใน **โฟลเดอร์เดียวกัน**  
3. Double-click `flutter_login.exe` to launch the app.  
   ดับเบิ้ลคลิก `flutter_login.exe` เพื่อเปิดโปรแกรม  

---

## 🛠️ Build From Source / การคอมไพล์จากซอร์สโค้ด
If you want to rebuild the project:  
หากต้องการคอมไพล์โปรเจกต์ใหม่:  

1. Install [Flutter](https://flutter.dev/docs/get-started/install).  
   ติดตั้ง [Flutter](https://flutter.dev/docs/get-started/install)  
2. Run the following commands:  
   รันคำสั่งดังนี้:  
   ```bash
   flutter pub get
   flutter build windows
