# 🌿 MySensor Hub — ESP32 Firmware Installer

Web-based installer for the MySensor ESP32 hub, built for use with [Cannabis Planner](https://play.google.com/store/apps/details?id=com.ivangospocic.cannabisplanner) — a 100% offline, privacy-focused grow tracker.

This installer flashes the MySensor firmware directly to your ESP32 board using [ESP Web Tools](https://esphome.github.io/esp-web-tools/) — no software installation required.

---

## 📺 Video Tutorial

Watch the full step-by-step setup, from flashing the firmware to connecting the sensor to the app:

▶️ [Watch on YouTube](https://www.youtube.com/watch?v=27Nmx-xaarU)

---

## 🚀 How to Install

1. **Connect your ESP32** to your computer via USB cable.
2. Open this page in **Google Chrome** or **Microsoft Edge** on a **desktop computer**:
   👉 [https://cannabisplanner.github.io/mysensor-instal/](https://cannabisplanner.github.io/mysensor-instal/)
3. Click **Install Firmware** and select your device's serial/COM port.
4. Wait for flashing to complete (this can take a few minutes).
5. Once done, open the **Cannabis Planner** app on your phone and connect to your sensor from the **Environment** tab.

> ⚠️ **This only works in Chrome or Edge on desktop (Windows/Mac/Linux/ChromeOS).**
> It does **not** work on mobile browsers, or in Firefox/Safari, due to Web Serial API limitations.

---

## 📱 Get the App

Cannabis Planner is available for free on Google Play:

<a href="https://play.google.com/store/apps/details?id=com.ivangospocic.cannabisplanner">
  <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" height="60"/>
</a>

---

## 🔧 Supported Hardware

This firmware is built for standard 4MB ESP32 boards. A separate build for **N16R8** (16MB flash / 8MB PSRAM) modules is in progress.

---

## 🔒 Privacy First

Cannabis Planner works 100% offline — no cloud sync, no accounts, no tracking. All sensor data stays on your device.

---

## ⚠️ Disclaimer

This project is intended for educational and planning purposes only. Users are responsible for complying with local laws and regulations.
