# Keyboard Firmware
This repository contains the OTA (Over-The-Air) firmware update packages for the custom wireless keyboard.

## ✨ Features
* **Quad-Mode Connectivity**: USB, Bluetooth LE, Logitech Unifying, and Logitech Bolt.
* **Web VIA Support**: On-the-fly keymap and macro configuration via Web Serial API.
* **OTA DFU**: Seamless wireless firmware updates without disassembling the keyboard.

## 🚀 How to Perform an OTA Update

### Method 1: Using nRF Device Firmware Update (Mobile App)
1. Download the latest `XXXX_boot_app_dfu_package_VX.X.X.zip` package from the folder to your phone.
2. Put the keyboard into DFU Bootloader mode (`Fn + R_Alt + T`, or trigger via VIA).
3. Open the **nRF Device Firmware Update** app (iOS/Android), connect to the keyboard (XXXX_DFU), and tap the **Upload** button to upload the `zip` file.