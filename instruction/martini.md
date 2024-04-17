**Note: Clean Flash recommended due to QPR2 changes**

**Please note that OOS14 EX01 firmware is included in these builds**

**First Time Install / Clean Flash from OOS/Other Custom ROM**

1. Be on OOS14 and have an unlocked bootloader
2. Download recovery imgs for your device from [HERE](https://sourceforge.net/projects/projectmatrixx/files/Android-14/martini/recovery/)
3. Reboot to bootloader
4. *fastboot flash dtbo dtbo.img
   fastboot flash vendor_boot vendor_boot.img
   fastboot flash boot boot.img
   fastboot reboot recovery*
5. While in recovery navigate to Factory reset -> Format data/factory reset and confim to format the device.
6. When done formatting, go back to the main menu and then navigate to Apply update -> Apply from ADB
7. adb sideload rom.zip (replace "rom" with actual filename)
8 (optional). Reboot to recovery to sideload any add-ons (e.g magisk)
9. Reboot to system & Enjoy

**Update**
1. Reboot to recovery
2. While in recovery, navigate to Apply update -> Apply from ADB
3. adb sideload rom.zip (replace "rom" with actual filename)
4. Reboot to system & Enjoy

**OTA**
1. Download the update from Updater
2. Install it.
3. Reboot and Enjoy

**Note:- If you get error 7 while sideloading:**

1. Download [**super_empty.img**](https://sourceforge.net/projects/projectmatrixx/files/Android-14/martini/recovery/super_empty.img/download)
2. Reboot to fastboot
3. Use command fastboot wipe-super super_empty.img
4. Now you can sideload rom, Don’t forget to format data after sideloading.

