# SA:MP Mobile Client v2.10 (x64) - Bug Fix Edition

A modified and optimized source code for the **SA:MP Mobile Client v2.10 (x64)** for GTA: San Andreas. This repository focuses on fixing known crashes, improving stability on modern Android devices, and resolving existing bugs from the original client.

---

## 📸 Screenshots / รูปภาพตัวอย่าง


| Main Menu / หน้าแรก | Gameplay / บรรยากาศในเกม | Chat Input / ระบบพิมพ์แชท |
| :---: | :---: | :---: |
| <img src="screenshots/menu.png" width="250" alt="Main Menu"> | <img src="screenshots/gameplay.png" width="250" alt="Gameplay"> | <img src="screenshots/chat.png" width="250" alt="Chat UI"> |

> 💡 *Tip: Create a `screenshots` folder in your repository root and upload your images as `menu.png`, `gameplay.png`, and `chat.png`.*

---

## 📢 Initial Release Notes (บันทึกการอัปเดตฉบับเต็ม)

### 🇺🇸 English Version
We are excited to announce the first official release of the optimized **SA:MP Mobile Client v2.10 (x64)**. This build focuses entirely on fixing critical bugs, improving stability on modern devices, and enhancing the overall multiplayer experience for GTA: San Andreas on Android.

#### 🛠️ What's New & Fixed
* **Full 64-bit (x64) Support:** Optimized code compilation for modern 64-bit processors, ensuring smooth performance and lower battery consumption.
* **Android 13 & 14 Compatibility:** Fixed crashes on startup and permission errors specifically found on newer Android versions.
* **Crash & Freeze Fixes:** Resolved random crashes during heavy texture rendering, stream distance loading, and server connection handshakes.
* **Improved Keyboard & Chat:** Fixed issues where the virtual keyboard would fail to pop up or get stuck. Chat input scaling is now responsive across various screen aspect ratios.
* **Network Optimization:** Upgraded packet handling to minimize desync, player warping, and random disconnections on mobile networks.

---

### 🇹🇭 ภาษาไทย
ยินดีต้อนรับเข้าสู่การเปิดตัวอย่างเป็นทางการของ **SA:MP Mobile Client v2.10 (x64)** รุ่นปรับปรุงใหม่และแก้ไขบั๊กทั้งหมด ตัวเกมนี้ถูกพัฒนาขึ้นเพื่อเน้นความเสถียร แก้ไขปัญหาเกมเด้ง และรองรับระบบปฏิบัติการ Android รุ่นใหม่ๆ 

#### 🛠️ รายการแก้ไขและฟีเจอร์ใหม่
* **รองรับ 64-bit (x64) สมบูรณ์แบบ:** ปรับแต่งซอร์สโค้ดให้ทำงานร่วมกับชิปประมวลผลยุคใหม่ได้อย่างลื่นไหล ลดอาการกระตุกและประหยัดแบตเตอรี่มากขึ้น
* **รองรับ Android 13 และ 14:** แก้ไขอาการเกมเด้งทันทีหลังกดเข้าเกม (Crash on Startup) และปรับปรุงระบบขอสิทธิ์เข้าถึงไฟล์ให้ถูกต้อง
* **แก้ไขอาการเกมเด้งและค้าง:** แก้ไขบั๊กการโหลดโมเดล/พื้นผิว (Textures) และลดปัญหาเกมหลุดขณะกำลังเปลี่ยนฉากหรือเชื่อมต่อเซิร์ฟเวอร์
* **ปรับปรุงระบบแชทและแป้นพิมพ์:** แก้ไขบั๊กแป้นพิมพ์ไม่เด้งขึ้นมา และปรับขนาดช่องพิมพ์แชทให้พอดีกับหน้าจอมือถือทุกสัดส่วน (ไม่ยืดหรือเบี้ยว)
* **ระบบเครือข่ายที่เสถียรขึ้น:** ปรับปรุงการรับส่งข้อมูล (Packet) เพื่อลดอาการปิงแกว่ง ตัวละครวาร์ป หรือหลุดออกจากเซิร์ฟเวอร์โดยไม่ทราบสาเหตุ

---

## 🖥️ System Requirements / ข้อกำหนดระบบขั้นต่ำ

### 🇺🇸 English
* **Minimum OS:** Android 9.0 (Pie) or higher.
* **Architecture:** 64-bit CPU (ARM64-v8a) strictly required. **32-bit devices are not supported.**
* **RAM:** 3 GB minimum (4 GB or higher recommended for high-texture servers).
* **Storage:** 2.5 GB of free space for internal game data.

### 🇹🇭 ภาษาไทย
* **ระบบปฏิบัติการขั้นต่ำ:** Android 9.0 (Pie) ขึ้นไป
* **สถาปัตยกรรม:** จำเป็นต้องใช้ซีพียูระบบ 64-bit (ARM64-v8a) เท่านั้น **ไม่รองรับมือถือระบบ 32-bit**
* **หน่วยความจำ (RAM):** ขั้นต่ำ 3 GB (แนะนำ 4 GB ขึ้นไปสำหรับเซิร์ฟเวอร์ที่มีมอดหรือพื้นผิวความละเอียดสูง)
* **พื้นที่จัดเก็บข้อมูล:** พื้นที่ว่างอย่างน้อย 2.5 GB สำหรับข้อมูลตัวเกมและดาต้า

---

## 🛠️ Key Fixes & Enhancements
* **Crash Fixes:** Resolved frequent crashes during gameplay and server connection transitions.
* **Android 13/14 Support:** Updated build configurations to target modern Android API levels seamlessly.
* **Architecture:** Full 64-bit (x64) compatibility with optimized memory management.
* **UI & Keyboard Fixes:** Improved chat input responsiveness and fixed layout stretching on various screen aspect ratios.
* **Network Stability:** Reduced desync and packet loss issues on high-ping mobile networks.

---

## 🚀 Getting Started

### Prerequisites
* Android Studio (Latest Version recommended)
* Android NDK & SDK (Matching target API levels)
* Java Development Kit (JDK) 11 or higher

### Build Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com
   ```
2. Open the project in **Android Studio**.
3. Sync Gradle and ensure all dependencies are downloaded.
4. Build the APK using `Build > Build Bundle(s) / APK(s) > Build APK(s)`.

---

## 📂 How to Install Data (วิธีติดตั้งดาต้า)

To run the game properly after installing the built APK, you need to set up the GTA:SA and SA-MP data folders on your Android device:

1. **Download Data:** Obtain the compatible GTA:SA (v2.10) game data files (`texdb`, `audio`, etc.).
2. **Extract Files:** Extract the data zip folder.
3. **Move to Internal Storage:** Move the game data folder to the following path:
   * `/Android/data/com.rockstargames.gtasa/` (or your specific client package name folder).
4. **Configure Settings:** Edit the `settings.ini` file inside the `samp` folder to change your **Player Name**, **Server IP**, and **Port**.
5. **Permissions:** Ensure the installed APK has **Storage/Files and Media** permissions allowed in Android Settings.

---

## 🧩 Plugins & Cheats Setup / วิธีเปิดใช้งานปลั๊กอินและสคริปต์เสริม

### 🇺🇸 English
This client supports customized ASI loaders and Cleo scripts. To activate modifications or developer cheat tools, follow these steps:
1. Locate the `com.rockstargames.gtasa` (or your custom package) folder in `/Android/data/`.
2. Inside the root game folder, look for or create a folder named `cleo` or `plugins`.
3. **For Cleo Scripts (.csa / .csi):** Place your script files directly into the `cleo` folder.
4. **For Plugins (.asi / .so):** Put the compiled library files inside the `libs` or `plugins` subdirectory depending on your project configuration.
5. Enable cheat menu in-game by swiping down from the top center of the screen (if Cleo script is present).

*⚠️ **Disclaimer:** Using automated scripts or gameplay cheats on public servers may result in temporary or permanent bans by server administrators.*

### 🇹🇭 ภาษาไทย
ตัวไคลเอนต์นี้รองรับระบบ ASI Loader และ Cleo สคริปต์สําหรับนักพัฒนา หากต้องการเปิดใช้งานมอด ปลั๊กอินเสริม หรือเครื่องมือทดสอบ (โปรแกรมโกง) ให้ทำตามขั้นตอนดังนี้:
1. ไปที่โฟลเดอร์ตัวเกมของคุณใน `/Android/data/com.rockstargames.gtasa/`
2. สร้างหรือเปิดโฟลเดอร์ที่ชื่อว่า `cleo` หรือ `plugins` ไว้ในโฟลเดอร์หลักของเกม
3. **สำหรับการใช้งาน Cleo สคริปต์ (.csa / .csi):** ให้นำไฟล์สคริปต์ไปวางไว้ในโฟลเดอร์ `cleo`
4. **สำหรับการใช้งานปลั๊กอิน (.asi / .so):** ให้นำไฟล์ไลบรารีไปวางไว้ในโฟลเดอร์ `libs` หรือ `plugins` ตามโครงสร้างที่คุณตั้งค่าไว้ในซอร์สโค้ด
5. วิธีเปิดเมนูสูตรโกงในเกม (ถ้าติดตั้งสคริปต์ Cleo ไว้): ให้ใช้นิ้วลากหน้าจอจากตรงกลางด้านบนลงข้างล่างอย่างรวดเร็ว

*⚠️ **คำเตือน:** การเปิดใช้งานสคริปต์ช่วยเล่นหรือโปรแกรมโกงในเซิร์ฟเวอร์สาธารณะ อาจส่งผลให้คุณโดนแบนจากผู้ดูแลระบบของเซิร์ฟเวอร์นั้นๆ ได้*

---

## 👥 Development Team & Credits
* **Development Team:** [ALEEFDEV / MAYDEV]
* * **Team:** [Girl Developer / Lux Developer]
* **Rockstar Games** - Creators of GTA: San Andreas.
* **SA:MP Team** - Original SA:MP multiplayer modification for PC.
* **Mobile Community Developers** - For the foundational mobile port source code.
* **Contributors** - Bug fixes, x64 compilation optimization, and modern Android compatibility updates.

---

## 💬 Community & Support
Join our community to get the latest updates, report bugs, or get help with the setup:

[![Discord Shield](https://shields.io)](https://discord.gg/thdevelopercommu)

*Note: Replace `https://discord.gg` with your actual Discord server link.*

---

## 📜 License & Disclaimer
This project is for educational and development purposes only. All rights to GTA: San Andreas belong to Rockstar Games, and SA:MP rights belong to the SA:MP Team.
