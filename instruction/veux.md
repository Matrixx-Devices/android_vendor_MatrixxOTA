**Before start flashing.....**
- Backup all your data to any external source. 
- Update your device to latest firmware of your region.
- Gapps included so no need to flash/sideload GApps.

**Clean Flash:**
1. You must have Matrixx recovery installed ( fastboot flash vendor_boot vendor_boot.img && fastboot flash boot boot.img )
2. Reboot to Matrixx recovery
3. Plug your phone to PC and select Apply update via ADB
4. Run "adb sideload <rom_filename>.zip"
5. Select "yes" if signature failed prompted
6. Factory Reset / Format Data
7. Reboot to system and Enjoy

**Rom Update/Dirty flash:**
1. Reboot to recovery
2. Apply update > Apply from ADB
3. Open command prompt & sideload rom using command adb sideload <rom_filename>.zip
4. Reboot to system
