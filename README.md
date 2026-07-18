# AiWan CoC Automation Helper (爱玩Coc免费版)

An open-source automation utility for Clash of Clans (CoC), designed to assist players with automated task execution, resource management, and gameplay optimization.

---

## 📢 Important Declaration
* **Developer Status**: The official developer of this application is **Aiwan**.
* **Open Source Commitment**: This software is completely open-source and **will never become a paid product**. It is free to use, modify, and distribute under its open-source license.
* **Translation Support**: This English guide, user interface translation, and build package were created to help English-speaking users navigate and understand the application.

---

## 🛠️ Key Features

The application utilizes high-performance computer vision, optical character recognition (OCR), and Android accessibility frameworks to automate routine tasks:

1. **Computer Vision & Image Recognition**
   * Uses **OpenCV** to scan and identify game interface elements, buildings, and troop structures dynamically.
   * Matches built-in image templates to locate and interact with game buttons and layouts.

2. **Optical Character Recognition (OCR)**
   * Powered by a localized **Tesseract OCR** engine to read on-screen text, upgrade timers, and resource levels.

3. **Intelligent Automation Engine**
   * Integrates an advanced **Lua Script VM** to execute modular bot routines safely.
   * Leverages Android Accessibility Services or root commands to inject touch inputs, gestures, and keystrokes.

4. **Network & Remote Utilities**
   * Supports remote device synchronization via TCP/UDP connections.
   * Allows database logging and automated email alerts via integrated SMTP/IMAP configurations.

---

## ⚙️ Requirements & Permissions

To operate properly as a background automation controller, the application requires several high-level Android permissions:
* **Accessibility Service**: Required for reading screen contents and simulating touch/swipe gestures on non-rooted devices.
* **Superuser/Root (Optional)**: Can be used to inject inputs directly if the device is rooted.
* **System Overlay (Draw over other apps)**: Displays the floating control bubble to quickly start, pause, or configure the bot in real-time.
* **Foreground Service / Battery Optimization Bypass**: Prevents Android from killing the background service during long automation sessions.

---

## 📥 Setup & Required Tools

You only need **two tools** to get started:

1. **The Game Assistant APK**: Download and install the application APK (`爱玩Coc免费版_蓝图标.apk`) on your Android device or emulator.
   * During the first launch, grant the required **Accessibility** and **Display over other apps (Overlay)** permissions when prompted.
2. **NP Manager (NP管理器)**: Install **NP Manager** to easily manage your Android files, configure game directories, and move your game accounts back and forth.

