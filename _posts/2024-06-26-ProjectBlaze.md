---
layout: post
title: "ProjectBlaze V3.5 For Poco X5 Pro/RN 12 PROSE - Redwood Device"
date: 2024-06-26 09:56:00 +0700
categories: custom rom
author: 'Thereache[RUSHI]'
---
![BlazeOS Banner](/assets/images/banner/blazeos.jpg)

{% include disclaimer.md %}

**DEVICE :** Poco X5 Pro/RN 12 PROSE<br>
**BUILD DATE :** 26 Jun 2024<br>
**FIRMWARE :** Hyperos OS1.0.4.0.UMSMIXM<br>
**TYPE :** Gapps

**Changelogs**
<ol>
    <li>Update blobs to OS1.0.4.0.UMSMIXM</li>
    <li>redwood: Import LHDC and LDAC blobs</li>
    <li>Update IMS blobs to haydn V816.0.1.0.UKKCNXM</li>
    <li>Update adreno blobs to v744</li>
    <li>Import missing camera blobs</li>
    <li>Import libxlog.so</li>
    <li>Miui Dolby included</li>
    <li>AtomxKernel With Ksu</li>
    <li>Mi Cam (Leica)included</li>
    <li>Firmware is included</li>
    <li>NFC works fine</li>
    <li>Seftynet passed by Default</li>
    <li>Many More Check your self</li>
</ol>

**Known Issue**
<ul>
    <li>You Tell Me With Proper Logs</li>
</ul>

**Prerequisites**
<ul>
    <li>Unlocked Bootloader</li>
</ul>

**Flashing Instruction**
<ul>
    <li>Reboot Fastboot</li>
    <li>Flash boot.img -->> fastboot flash boot boot.img</li>
    <li>Flash dtbo.img -->> fastboot flash dtbo dtbo.img (Optional)</li>
    <li>Flash vendor_boot.img -->> fastboot flash vendor_boot vendor_boot.img</li>
    <li>Reboot Recovery -->> fastboot reboot recovery In the recovery, press Apply Update It will wait for sideload Sideload desired ROM file using -->> adb sideload < ROM > </li>
</ul>

**Screenshots**

![ss](/assets/images/screenshots/jun26/IMG_20240626_091255_413.jpg){: width="576"}{: height="1280"}
![ss](/assets/images/screenshots/jun26/IMG_20240626_091256_010.jpg){: width="576"}{: height="1280"}
![ss](/assets/images/screenshots/jun26/IMG_20240626_091256_107.jpg){: width="576"}{: height="1280"}
![ss](/assets/images/screenshots/jun26/IMG_20240626_091256_171.jpg){: width="576"}{: height="1280"}
![ss](/assets/images/screenshots/jun26/IMG_20240626_091256_358.jpg){: width="576"}{: height="1280"}


Download | Goodix Atomx Kernel

[Download ProjectBlaze-3.3-redwood-20240516-1802-GAPPS-OFFICIAL.zip (2.2 GB)][rom-links]


[Download vendor_boot.img,boot.img,dtbo.img][images]


[rom-links]: https://sourceforge.net/projects/projectblaze/files/redwood/V3.5/ProjectBlaze-3.5-redwood-20240625-1810-GAPPS-OFFICIAL.zip/download

[images]: https://sourceforge.net/projects/projectblaze/files/redwood/Images/


Download | FTS TURBO Kernel

<ul>
    <li>Flash Letest TURBO KERNEL is Mandatory,Becuse of SystumUi Crashing(will be fix in next update)</li>
</ul>


[FTS-ProjectBlaze-3.5-redwood-20240625-0808-GAPPS-OFFICIAL.zip(2.2 GB)][ftsdownload]


[Letest TURBO Kernel][turbokernel]


[FTS-USER Download vendor_boot.img,boot.img,dtbo.img][imagesForftsuser]


[ftsdownload]: https://sourceforge.net/projects/redwoodroms/files/fts/FTS-ProjectBlaze-3.5-redwood-20240625-0808-GAPPS-UNOFFICIAL.zip/download

[turbokernel]: https://telegram.me/garbageofreache/86

[imagesForftsuser]: https://sourceforge.net/projects/redwoodroms/files/fts/flashfiles/
