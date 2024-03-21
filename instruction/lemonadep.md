**Before start flashing.....**
- Backup all your data to any external source. 
- Update your device to OOS 14 or update OOS14 firmware using Firmware flasher
- Download firmware and update to 14.0.0.212(EX01) using Firmware-Flasher [**HERE**](https://sourceforge.net/projects/projectmatrixx/files/Android-14/lemonadep/Utility/)
- Gapps included so no need to flash/sideload GApps

**Clean Flash:**
1. Extract Firmware-Flasher zip
2. Reboot to bootloader & connect your phone to PC
3. Double click on __Update-firmware.bat__
4. Reboot to recovery & Factory reset > Format data/factory reset
5. Back to recovery home page & tap > Apply update > Apply from ADB
5. Now sideload rom using command ```adb sideload <rom_filename>.zip```
7. Now reboot to system.

**Rom Update/Dirty flash:**
1. Update firmware if required
2. Reboot to recovery
3. Apply update > Apply from ADB
4. Open command prompt & sideload rom using command ```adb sideload <rom_filename>.zip```
5. Reboot
