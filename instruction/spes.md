## Before Starting Flashing

- Backup all your data to any external source.
- Always check if the build is GAPPS or Vanilla variant.
- If it is a Vanilla variant, flash only the recommended flashable GAPPS zip given in the notes right after flashing the ROM.

## Clean Flash

1. Use OrangeFox Official Recovery.
2. Format Data.
3. Wipe metadata, data, dalvik, and cache.
4. Flash the ROM from SD Card or OTG.
5. Flash Recovery as Ramdisk.
6. Format data and reboot to the system.
7. If you want to sideload from ADB, plug your phone into the PC:
    - Run `adb sideload ROM.zip` and follow step 4.

## ROM Update / Dirty Flash

1. Reboot to recovery.
2. Flash the downloaded ROM from internal storage.
3. If you prefer using a PC:
    - Open command prompt & sideload ROM using the command `adb sideload <rom_filename>.zip`.
4. Reboot.

## Note

- If you encounter any issues after a dirty flash, perform a clean flash before reporting.
