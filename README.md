<div align="center">

# Vendor Blobs – Xiaomi 12T (plato)

<img src="https://img.shields.io/badge/Device-Xiaomi%2012T-blue?style=for-the-badge">
<img src="https://img.shields.io/badge/Codename-plato-orange?style=for-the-badge">
<img src="https://img.shields.io/badge/Platform-MediaTek%20MT6895-green?style=for-the-badge">
<img src="https://img.shields.io/badge/Type-Proprietary%20Blobs-red?style=for-the-badge">

</div>

---

## 📱 Overview

This repository contains proprietary vendor binaries extracted from Xiaomi 12T (plato) stock firmware.

These components are required for proper hardware functionality on AOSP-based custom ROMs.

---

## 📦 What’s included

Vendor blobs provide support for core hardware components, including:

- 🎥 Camera HAL, image processing, and ISP features  
- 🎧 Audio effects, enhancements, and HAL implementation  
- 📺 Display pipeline, composition, and hardware rendering  
- 📡 Connectivity (Wi-Fi, Bluetooth, mobile network stack)  
- 🔋 Power management and thermal control components  
- 🤖 MediaTek APU / AI-related services and libraries  
- 📀 Media codecs and hardware-accelerated playback  
- 📊 Sensors and device hardware abstraction layers  

---

## ⚙️ Usage

This repository is used as part of an Android ROM build system.

It is typically included as: vendor/xiaomi/plato


Integration depends on the ROM tree and extraction method (proprietary-files or prebuilt vendor inclusion).

---

## 🧩 Dependencies

Used alongside:

- Device tree: [`android_device_xiaomi_plato`](https://github.com/SkyX-Arch/android_device_xiaomi_plato)
- Common tree: [`android_device_xiaomi_mt6895-common`](https://github.com/SkyX-Arch/android_device_xiaomi_mt6895-common)
- Custom ROM builds ([crDroid](https://github.com/SkyX-Arch/crdroid-ota) / LineageOS-based ROMs)

---

## ⚠️ Disclaimer

- These are proprietary binaries extracted from official Xiaomi firmware.
- They remain the property of their respective owners.
- Redistribution is intended for ROM development purposes only.
- No modification of original binaries is performed.
- Use at your own risk.

---

## 🚧 Status

Actively maintained and updated when new Xiaomi firmware releases are available.

Focus is on stability, compatibility, and keeping parity with stock vendor behavior.

## Credits

Special thanks to:

* [The LineageOS Project](https://github.com/LineageOS)
* [XagaForge](https://github.com/XagaForge)
* [Archcloudy](https://github.com/archcloudy)
* [Xiaomi MT6895 Devs](https://github.com/xiaomi-mt6895-devs)
