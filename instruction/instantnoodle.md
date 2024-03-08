**Before start flashing.....**
- Backup all your data to any external source. 
- Update your device to OOS 13.1
- Gapps included so no need to flash/sideload GApps

**Clean Flash:**
1. Have an unlocked bootloader & Latest OOS 13.1 flashed to both slots.
2. Download recovery and ROM for your device
3. Reboot to bootloader
4. fastboot flash recovery recovery.img
fastboot reboot recovery
5. While in recovery, navigate to Apply update -> Apply from ADB
6. adb sideload ROM.zip.
7. Format data, reboot to system & Enjoy !

**Rom Update/Dirty flash:**
1. Reboot to recovery 
2. adb sideload rom.zip (replace "rom" with actual filename) 
3. Reboot to system

