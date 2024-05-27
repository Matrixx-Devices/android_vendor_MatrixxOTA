**Before starting flashing:**

- Backup all your data to an external source.
- Update your device to the latest firmware of your region.
- Always check if the build is GAPPS or Vanilla variant.
- If it is Vanilla, then flash only the recommended flashable GAPPS zip provided in the notes after flashing the ROM.

**Clean Flash:**

- Use twrp recovery ([Download here](https://t.me/kamleshbuilds/313))
- Wipe metadata, data, dalvik, and cache.
- Flash the ROM from internal storage if available locally.
- Format data and reboot to system.
- If you want to sideload from ADB, plug your phone into the PC.
- Run `adb sideload ROM.zip` and follow step 4.

**ROM Update/Dirty flash:**

- Reboot to recovery.
- Flash the downloaded ROM from internal storage.
- If you want to use a PC, open the command prompt and sideload the ROM using the command `adb sideload <rom_filename>.zip`.
- Reboot.
