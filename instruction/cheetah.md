**Before start flashing.....**

- Always have backup of your internal storage
- Get ready to provide logs/crash url and steps to reproduce the bug along with bug reports

----

First Time Install
(Note: These releases include firmware)
- Download boot, dtbo, vendor_kernel_boot, vendor_boot & rom
- Reboot to bootloader
- fastboot flash boot boot.img
- fastboot flash dtbo dtbo.img
- fastboot flash vendor_kernel_boot vendor_kernel_boot.img
- fastboot flash vendor_boot vendor_boot.img
- fastboot reboot recovery
- While in recovery, navigate to Factory reset -> Format data/factory reset and confirm to format the device.
- When done formatting, go back to the main menu and then navigate to Apply update -> Apply from ADB
- adb sideload rom.zip (replace "rom" with actual filename)
7 (optional). Reboot to recovery (fully) to sideload any add-ons (e.g magisk)
- Reboot to system

Update via Recovery
- Reboot to recovery
- While in recovery, navigate to Apply update -> Apply from ADB
- adb sideload rom.zip (replace "rom" with actual filename)
- (optional). Reboot to recovery to sideload any add-ons (e.g magisk)
- Reboot to system 

Update via Updater
- Naviagate to Settings, System & then Updater
- Click local update
- Click the zip you want to install
- Reboot system

**Root:** same process for clean/dirty
- Download and Install Magisk apk
- Unzip the factory image from here for example (https://developers.google.com/android/images), Extract the IMGs folder, copy the init_boot file to your Pixel device.
- Patch init_boot.img file, Open Magisk app on your device, tap on install and tap again on “Select and Patch a file” and browse the init_boot.img file you’ve just copied. It will patch the file and save it in the same folder. Now you’ve to transfer patched init_boot.img file to your PC to flash it using an adb command.
- Reboot the device in Fastboot
- On your PC, open the plaform tools folder, hold the Windows button and right click in the folder and select open command here. Type the following commands to flash the patch boot file, below is an example; fastboot flash init_boot magisk_patched-25200_xgjAS.img
- Once complete and no errors are returned type fastboot reboot
- You can verify root access by downloading the root checker app from the Google Play Store. Store.
