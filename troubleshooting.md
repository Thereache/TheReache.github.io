---
title: Troubleshooting
description: You Find any Bug Dm Me With Log
---

# Troubleshooting

During your use of my builds, you may encounter some unexpected issues.

I can't do much about these unless appropriate logs are given.

(Please note that I will not assist if any modification is made to the ROM: For example, if a different kernel is flashed, if random Magisk modules are installed, or if the ROM is flashed with a different recovery. Don't forget to only report problems related to the operation of the device, do not accept reports about personalization features that do not work.).

## Report an issue

To properly report an issue, the following logs must be provided:

- `logcat` (System Log).
- `dmesg` (Kernel Log).

### Logcat

To grab a `logcat` it is required to have `USB debugging` enabled:

* Go into `Settings` -> `About Phone` and press 7 times the `Build Number`.
* Go into `Settings` -> `System` -> `Developer options` and enable `USB Debugging`.
* Open an `ADB & Fastboot tools` window on your PC and run this:

``` bash
    adb logcat -d > logcat.txt
```

* If a radio buffer log is requested, run this too:

``` bash
    adb logcat -db radio > radio.txt 
```

### Dmesg

Grabbing a `dmesg` requires root access. Fortunately, userdebug builds of LineageOS can access a root shell enviroment out-of-the box:

* Go into `Settings` -> `About Phone` and press 7 times the `Build Number`.
* Go into `Settings` -> `System` -> `Developer options` and enable `USB Debugging` and `Rooted debugging`.
* Open a `ADB & Fastboot tools` window on your PC and run this:

``` bash
    adb root # Enables root shell
    adb shell dmesg > /sdcard/dmesg.txt
    adb shell pull /sdcard/dmesg.txt
```

### Send the logs
Attach the logs (you can find them inside the `ADB & Fastboot tools` folder) in the bug report message.

[Back](./)
