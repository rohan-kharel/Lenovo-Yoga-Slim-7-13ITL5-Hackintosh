# Lenovo-Yoga-Slim-7-13ITL5-Hackintosh

OpenCore EFI for the Lenovo Yoga Slim 7 13ITL5

**Specifications**

- Quad Core Intel Core i7-1165G7
- Intel Iris Xe Graphics 8GB
- 16GB RAM
- Intel Wi-Fi 6 AX201
- SAMSUNG MZVLB512HBJQ-000L2 NVMe Drive
- Intel Bluetooth

**Working**

 - Wi-Fi
 - Bluetooth
 - Camera (not in Photo Booth though)
 - Battery readouts
 - Speakers
 - Keyboard and trackpad
 - USB Map

**Not working/Untested**
- Microphone
- SSD
>**Note on SSD:**
>MacOS *must* be installed to either a supported NVMe drive (untested) or to external storage as the NVMe drive in this laptop does not work with macOS. If you wish to enable it anyway, simply open config.plist and remove nvme=-1 from boot-args.
- Graphics acceleration
> **Note on Graphics:**
> Because the display is running in VESA mode and not utilizing  Iris Xe Graphics, macOS will take a while to boot and it will feel sluggish. As there is and never will be support for this iGPU, there is nothing I can do about it.

**Installation**
-
Use [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/) to create installation media and place the provided EFI folder on the  root of your drive. For iCloud Services, use the same guide to [patch your SMBIOS.](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html)

**Tested on:**
-
- macOS Ventura 13
- macOS Sonoma 14

**Screenshots**
-

![Screenshot 2024-04-03 at 11 20 26](https://github.com/rohan-kharel/Lenovo-Yoga-Slim-7-13ITL5-Hackintosh/assets/111512418/ea5ed883-ea2f-4bf8-9c66-3138f41265c2)
