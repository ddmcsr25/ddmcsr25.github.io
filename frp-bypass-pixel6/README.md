# 🔐 Android 14 FRP & Lock Screen Bypass (Pixel 6)
**Author**: Derek Morris  
**Location**: Merced, California  
**Role**: Security Analyst & Ethical Hacker  
**Date Reported**: July 2024  
**Disclosure Type**: Responsible Disclosure  
**Issue Tracker ID**: [352333773](https://issuetracker.google.com/issues/352333773)

---

## 📌 Summary

This research documents a **critical vulnerability** that allows attackers to **bypass Factory Reset Protection (FRP)** and the **user lock screen** on the **Pixel 6 running Android 14**, even when:

- USB debugging is **disabled**
- The bootloader is **locked**
- FRP is **active**

Using legitimate tools such as **Pixel Flasher** and **OTA sideloading**, this bypass was successfully tested and submitted to Google through the **Android Security Rewards (ASR)** program.

---

## 📱 Affected Devices

- **Device**: Pixel 6 (`codename: oriole`)
- **OS**: Android 14  
- **Build Fingerprint**: `google/oriole/oriole:14/AP2A.240605.024/11860263:user/release-keys`
- **Exploit Method**: Physical access + ADB sideload with full OTA flashing

---

## 💥 Impact

Attackers with physical access and basic knowledge of Android tools can:

- Completely bypass FRP and the user-set PIN/password
- Install any firmware or custom ROM
- Access all user data
- Unlock the bootloader without authorization
- Enroll the device into the Android Beta Program for persistent access

---

## 🧪 Exploit Steps (Abbreviated)

1. Boot the Pixel 6 into recovery.
2. Enable “Apply update from ADB.”
3. Use Pixel Flasher with Android 15 Beta OTA image.
4. Flash the device via sideload using Pixel Flasher.
5. Bypass FRP + lock screen, and gain full access.

➡️ **Full step-by-step technical breakdown** is available on the blog:  
👉 [Read the Blog Post](https://frp-bypass-derek.blogspot.com/2025/07/bypassing-frp-and-lock-screen-on-pixel.html)

---

## 🏆 Disclosure & Recognition

- **Reported to**: Google Android Security Team  
- **Issue Tracker**: [FRP bypass vulnerability #352333773 (Google)](https://issuetracker.google.com/issues/352333773)
- **Rewarded via ASR**: ✅ (Proof on file – see attached PDF)

---

## ⚠️ Disclaimer

This information is shared **for educational purposes only** and with responsible disclosure intent. Do not use this exploit on devices you do not own or have explicit authorization to test.

---

## 📣 Help Recognize Ethical Research

If you believe security researchers deserve acknowledgment for responsible disclosure:

- ⭐ Star this repo
- 🔁 Share the blog post
- 🗣️ Use hashtag `#FRPbypassPixel6`

---

## 🔗 Related

- [Bug Hunters - Android & Google Devices VRP Rules](https://bughunters.google.com/about/rules/6171833274204160/android-and-google-devices-security-reward-program-rules)
