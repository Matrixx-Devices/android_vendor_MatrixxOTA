**Before start flashing.....**
- Backup all your data to an external source to prevent data loss.

**Update firmware:**
- If you're on OOS 11/12, update to OOS 13/14 before proceeding
- Now download firmware-Flasher 14.0.0.1901(EX01) [**HERE**](https://sourceforge.net/projects/projectmatrixx/files/Android-15/lemonadep/Utility/)
- Extract Firmware-Flasher zip
- Reboot to bootloader & connect your phone to PC
- Double click on __Update-firmware.bat__

**Clean Flash:**
1. Reboot to recovery & Factory reset > Format data/factory reset
2. Back to recovery home page & tap > Apply update > Apply from ADB
3. Now sideload rom using command ```adb sideload <rom_filename>.zip```
4. Now reboot to system.

**Rom Update/Dirty flash:**
1. Update firmware if required
2. Reboot to recovery
3. Apply update > Apply from ADB
4. Open command prompt & sideload rom using command ```adb sideload <rom_filename>.zip```
5. Reboot

**Update recovery:**
- Update recovery package if facing issue to adb sideload
- Download from [**HERE**](https://sourceforge.net/projects/projectmatrixx/files/Android-15/lemonadep/Utility/) and extract recovery package then execute __recovery.bat__ or __recovery.sh__ as per your computer OS 

**Note:** Gapps included so no need to flash/sideload GApps
