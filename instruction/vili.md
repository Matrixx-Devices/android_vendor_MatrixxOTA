**Before starting flashing:**

- Backup all your data to any external source. 
- Gapps included so no need to flash/sideload GApps.

**Clean Flash:**

- Use Twrp.
- Format Data.
- Wipe metadata, data, dalvik and cache.
- Flash the ROM from SD Card or OTG.
- Format data and Reboot to system.
- If you want to sideload from ADB, plug your phone into PC.
- Run `adb sideload ROM.zip` and follow step 4 .

**ROM Update/Dirty flash:**

- Reboot to recovery.
- Flash the downloaded ROM from internal storage.
- If you want to go with PC, then open command prompt & sideload ROM using command `adb sideload <rom_filename>.zip`.
- Reboot to system.
