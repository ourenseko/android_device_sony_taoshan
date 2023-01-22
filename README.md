
Unlock bootloader guide
1
Check if the bootloader can be unlocked on your device
It is only possible to unlock the bootloader for certain releases. To check if it is possible to unlock the bootloader of your device, follow these steps:

In your device, open the dialer and enter *#*#7378423#*#* to access the service menu.
Tap Service info > Configuration > Rooting Status. If Bootloader unlock allowed says Yes, then you can continue with the next step. If it says No, or if the status is missing, your device cannot be unlocked.





more ROMS https://cyanogenmodroms.com/sony/



Install the device drivers and platform tools
If necessary, download and install the USB drivers.
If you are running Windows: Download and install the latest USB drivers. Follow the instructions on the site.
If you’re running OSX or Linux: You can skip this step since no additional drivers are required.
Download and extract the Platform tools zip file.
Select and download the Platform tools for your operating system and extract the zip file. Tip: Take note of the installation path, you may need to access specific files later.
 On your device, turn on USB debugging by going to Settings > Developer options and click to enable USB debugging.
If your device is Android Jelly Bean 4.2 or newer: Developer options are hidden by default. To enable, tap on Settings > About Phone > Build Version multiple times. Then, turn on USB debugging by going to Settings > Developer options.



Connect to Fastboot
Turn off your device.
Connect a USB-cable to your computer.
On your device, press the Fastboot key (Volume up for most devices, see Useful key combinations) at the same time as you connect the other end of the USB-cable.
Windows users: Open the Devices and Printers directory, right-click on the fastboot driver and press Update. Browse and point towards the location of the new android_winbus.inf file.
When your device is connected, open a command window on your computer and go to the platform-tools folder within the Android SDK folder.
Enter the following command:
fastboot devices
Verify that you get an answer back without any errors.


Enter unlock key
WARNING! The command below contains your unlock key. If you perform this step, you will unlock the bootloader. This may void your warranty and/or any warranty from your operator.

Note: In this step you will need the unlock code for your device.

If you still want to unlock the bootloader of your device, enter the following command:
fastboot oem unlock 0x<insert your unlock code>
Verify that you get an answer back without any errors.
Done! You have now unlocked the bootloader of your device.
https://developer.sony.com/develop/open-devices/get-started/unlock-bootloader/how-to-unlock-bootloader/

Copyright 2015 - The CyanogenMod Project

Sony Xperia L
==============

The Sony Xperia L (codenamed _"Taoshan"_) is a mid-range smartphone from Sony Mobile.

It was announced in March 2013.

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | 1.0GHz Dual-Core MSM8230
GPU     | Adreno 305
Memory  | 1GB RAM
Shipped Android Version | 4.1.2
Storage | 8GB
Battery | 1750 mAh
Display | 4.3" 854 x 480 px
Camera  | 8MPx, LED Flash

![Sony Xperia L](http://cdn2.gsmarena.com/vv/pics/sony/sony-xperia-l-01.jpg "Sony Xperia L in black")

This branch is for building CyanogenMod 13.0 (or Android Marshmallow 6.0 AOSP based roms) ROMS.
