Elephone P9000 - OmniROM/AOSP
==============

This branch is for building Twrp or Omni ROM (or Android Marshmallow 6.0 AOSP based roms) ROM. For more information about building the ROM, read our [build manual](manual).

---

Basic   | Spec Sheet
=======
# About Device

![Elephone P9000](http://g03.a.alicdn.com/kf/HTB1.TsuKVXXXXanXXXXq6xXFXXX6/Official-Direct-Elephone-P9000-Helio-P10-MTK6755-2-0GHz-Octa-Core-4GB-RAM-32GB-ROM-5.jpg "Elephone P9000 in black")

Announced on 25th December 2015, the Elephone P9000 (codenamed _"P9000"_) is a flagship smartphone from Elephone. The P9000 now supports CyanogenMod 13.0!

### Specifications

Component Type | Details
-------:|:-------------------------
CPU     | 2.0GHz Octa-Core MT6755 (Helio P10)
GPU     | Mali-T860
Memory  | 4GB RAM
Shipped Android Version | 6.0
Storage | 32GB
Battery | 3000 mAh
Display | 5.5" 1920 x 1080 px
Rear Camera | 13MP (Sony IMX258 Exmor RS), Dual LED Flash, Laser autofocus
Front Camera | 8MP (OV)

---

# Build Information

### Working:
 * Hardware acceleration
 * Wi-Fi
 * Fast charging
 * Offline charging
 * GPS
 * AGPS
 * ANT (fitness trackers .etc)
 * Vibration
 * Audio
 * Auto brightness
 * Doze
 * RAM and ROM
 * Rotation
 * All sensors
 * NFC (payments, pairing .etc)
 * Lazer autofocus
 * Flashlight (statusbar and camera)
 * Bluetooth
 * Camera rear/front (video and photo)
 * Camera HDR
 * Micro SD support
 * RIL for SMS/calls/internet/LTE on 1 and 2 SIM
 * MTP and Mass Storage modes
 * Audio over Bluetooth (music, calls .etc)
 * SELinux enforcement
 * Fingerprint scanner
 * FM radio
 * Wi-Fi tethering

### In progress:
 * Add HOME Button functional
 * Fix flip case

### Thanks to:
 * CyanogenMod team
 * Wuxianlin
 * Ferhung
 * Xen0n
 * Leskal
 * JonnyXDA
 * olegsvs
 * Visi0nary
 * andyrichardson
 * Team M.A.D

To build: 
```
. build/envsetup.sh

lunch omni_p9000-userdebug

make clean && brunch -j5 p9000
```
