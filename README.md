# 🔐 Android 14 FRP & Lock Screen Bypass — Pixel 6

**Author:** Derek Morris  
**Location:** Merced, California  
**Role:** Security Analyst & Ethical Hacker  
**Published:** 2024  
**Disclosure Type:** Public Educational Research

---

## Overview

This public research documents a verified method to bypass **Factory Reset Protection (FRP)** and the **lock screen** on a Google Pixel 6 running **Android 14**, even with the **bootloader locked** and **USB debugging disabled**.

This exploit demonstrates how sideloading an OTA update with official tools can unintentionally allow full access to a protected device.

---

## 🔧 What’s Affected

- **Device:** Pixel 6 (code name: oriole)  
- **OS Version:** Android 14  
- **Build Fingerprint:** `google/oriole/oriole:14/AP2A.240605.024/11860263:user/release-keys`  
- **Conditions:** FRP active, USB debugging off, bootloader locked

---

## 🛠️ Summary of Exploit

An attacker with basic knowledge of Android tools and physical access to the device can:

- Reset the device into recovery
- Sideload a full OTA image (Android 15 Beta)
- Flash the device using Pixel Flasher
- Bypass the Google account verification and user lock screen
- Regain full access and unlock the bootloader

---

## 🔍 Full Technical Write-Up

Read the complete breakdown with step-by-step instructions, tools required, and conditions for replication:

👉 **[https://ddmcsr25.github.io](https://ddmcsr25.github.io)**

---

## ⚠️ Disclaimer

This information is provided for **educational and responsible security research purposes only**. Do not use this method to gain unauthorized access to any device you do not own or have explicit permission to analyze.

---

## 🧠 Keywords (for search indexing)

FRP bypass Pixel 6, Android 14 exploit, lock screen bypass, sideload OTA unlock, mobile vulnerability research, Google Pixel FRP hack, ethical hacking Android, Android security researcher, bypass verification Android

---

## 📬 About the Author

**Derek Morris** is a security analyst and ethical hacker based in **Merced, California**, with a focus on real-world vulnerability discovery across mobile and system platforms.

