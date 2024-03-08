**Before start flashing.....**
- Backup all your data to any external source. 
- Update your device to latest firmware of your region.
- Gapps included so no need to flash/sideload GApps.

**Clean Flash:**
1. You must have Matrixx recovery installed ( fastboot flash vendor_boot vendor_boot.img && fastboot flash boot boot.img )
2. Boot Matrixx recovery
3. Format Data
4. Plug your phone to pc and Apply update via ADB
5. Run adb sideload ROM.zip
6. Click yes
7. Reboot system and Enjoy

**Rom Update/Dirty flash:**
1. Reboot to recovery
2. Apply update > Apply from ADB
3. Open command prompt & sideload rom using command ```adb sideload <rom_filename>.zip```
4. Reboot
