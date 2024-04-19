**Before starting flashing:**

   - Backup all your data to any external source.
   - CLEAN FLASH is mandatory if coming from another from or a previous unofficial build. 
   - Keep in mind that a clean flash is always recommended when coming from another rom.

**Clean Flash:**

   1. Reboot to fastboot and flash the required images : fastboot flash vendor_boot vendor_boot.img && fastboot flash boot boot.img && fastboot flash recovery recovery.img
   2. Reboot to recovery : fastboot reboot recovery
   3. Format Data
   4. Plug your phone to pc and Apply update via ADB
   5. Run adb sideload <rom_filename>.zip
   6. Click yes
   7. Reboot to system

**ROM Update/Dirty flash:**

   1. Reboot to recovery
   2. Apply update > Apply from ADB
   3. Open command prompt & sideload rom using command adb sideload <rom_filename>.zip
   4. Reboot to system
