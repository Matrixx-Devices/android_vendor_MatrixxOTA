**Before start flashing.....**
- Backup all your data to any external source
- If using custom rom, Make sure you're using OOS 12 base
- If you're on OOS, update to OOS 12
- Gapps included so no need to flash/sideload GApps

**Clean Flash:**
1. Download recovery image
2. Reboot to bootloader & connect your phone to PC
3. type command ```fastboot flash recovery recovery.img```
4. Reboot to recovery & Factory reset > Format data/factory reset
5. Back to recovery home page & tap > Apply update > Apply from ADB
5. Now sideload rom using command ```adb sideload <rom_filename>.zip```
7. Now reboot to system.

**Rom Update/Dirty flash:**
1. Reboot to recovery
2. Apply update > Apply from ADB
3. Open command prompt & sideload rom using command ```adb sideload <rom_filename>.zip```
4. Reboot
