# Asus-TUF-FX504GE Monterey Hackintosh
### NOTE : I WON'T NOT RESPONSIBLE FOR ANY PROBLEM IF U MESS MY GUIDE.
#### Use Original Bluetooth (BLinjector , BLfirmware) kext for other MacOS , MacOS Monterey bluetooth kext temporarily solution only（Alpha version）.

![Screenshot 2021-06-13 at 12 41 31 PM](https://user-images.githubusercontent.com/85815874/121795795-971d7800-cc46-11eb-9afa-556592a81087.png)
 <p align="center">
  ** My Dekstop with About This Mac **
</p>              
                                      
Read this  in other language : [English](README.md) , [Malay](https://github.com/wilsomwong/Asus-TUF-FX504GE-Hackintosh/blob/main/MacOS%20Monterey/README/README_mly.md) , [Chinese (Simplified)](https://github.com/wilsomwong/Asus-TUF-FX504GE-Hackintosh/blob/main/MacOS%20Monterey/README/README_zh_cn.md) , [Chinese (Traditional)](https://github.com/wilsomwong/Asus-TUF-FX504GE-Hackintosh/blob/main/MacOS%20Monterey/README/README_zh_tw.md)
#### ** Other language update information will delay.

## Hardware (My Spec)
- CPU (Processor) : Intel Core i5-8300H CoffeeLake 8th
- GPU (Internal Graphics Card) : Intel Graphics UHD630
- dGPU (External Graphics Card) : Nvidia GTX1050Ti (4GB GDDR5 VRAM)
- RAM : DDR4 12GB 2400MHz
- Storage : 1TB HDD + 256GB SSD
- Screen : 15.6" Full HD 60Hz (1920 x 1080) 
- SoundBoard : Realtek ALC255
- WIFI / Bluetooth : Intel Wireless AC9560
- BIOS System : Dualboot MacOS Monterey + Windows 10
- Touchpad : ELAN I2C (HID)

## What's Working ?
- [x] iGPU with disabled dGPU
- [x] WiFi (100% Working) / Ethernet (I didn't try but i think it's working)
- [x] Bluetooth (kext only for Monterey)
- [x] Audio/Mic Input, Output (100 % working on lastest Opencore EFI)
- [x] 3.5mm Headphone Jack 
- [x] ACPI Display brightness with hot keys / slider
- [x] Battery Management
- [x] Sleep & Wake 
- [x] WebCam 
- [x] 3 ports Usb 3.1 & HDMI port (HDMI working in latest Opencore EFI)
- [x] Native hotkey support with Fn keys
- [x] Touchpad and gestures (Available in lastest OpenCore EFI) 
- [x] Hotspot with USB Tethering (Available in lastest OpenCore EFI) 
- [x] System Update 

## Not Working
- Nvidia GTX1050Ti (Not suppoted)

## In processing for test working & Fix the problem list 
- [ ] System Update (Has some problem , gonna fix later)
- [ ] Bluetooth (Cannot Open Bluetooth after sleep , wait until Stable version come out ..)
- [ ] WebCam (Not Working after sleep)
- [ ] AppleTV , AppleMusic and others (DRM problem , No solution until now)

## BenchMark
![Screenshot 2021-06-13 at 12 52 06 PM](https://user-images.githubusercontent.com/85815874/121795848-0f843900-cc47-11eb-8b66-eff358a82c7d.png)

## Credits
- Special Thanks to Acidanthera for most of the Kexts.
- Thanks to OpenCore Bootloader.
- Thanks to daliansky for Airportitlwm and Bluetooth kext.
- Thanks to alexandred for VoodooI2C.
- Thanks to RehabMan for ACPI patching guides.
- Thanks to hackintosh-stuff for ComboJack support for ALC255.
- Thanks to Facebook Page called "Hackintosh" , "我和我的黑苹果“.

## Last Thing ..
- I'm glad about community can help us to solve what can't working !! 
- If any problem solved , Pls inbox me email for help me to update my folder in GITHUB.
#
[![GitHub version](https://img.shields.io/badge/OpenCore-0.7.0(Monterey)-brightgreen)](https://github.com/wilsomwong/Asus-TUF-FX504GE-Hackintosh/tree/main/MacOS%20Monterey/OpenCore%207.0%20EFI)
[![GitHub version](https://img.shields.io/badge/OpenCore-0.7.1(Monterey)-brightgreen)](https://github.com/wilsomwong/Asus-TUF-FX504GE-Hackintosh/tree/main/MacOS%20Monterey/OpenCore%207.1%20EFI)
[![GitHub version](https://img.shields.io/badge/OpenCore-0.8.3(Ventura)-brightgreen)](https://github.com/wilsomwong/Asus-TUF-FX504GE-Hackintosh/tree/main/MacOS%20Ventura)
[![Gitter](https://badges.gitter.im/Hackintosh-for-Asus-TUF-FX504/community.svg)](https://gitter.im/Hackintosh-for-Asus-TUF-FX504/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
