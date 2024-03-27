**Before starting flashing:**

- Backup all your data to any external source.
- Update your device to the latest firmware of your region.
- GApps are included, so there's no need to flash/sideload GApps.

**Clean Flash:**

1. Make sure you have Matrixx recovery installed (`fastboot flash vendor_boot vendor_boot.img && fastboot flash boot boot.img`).
2. Reboot to Matrixx recovery.
3. Plug your phone into the PC and select "Apply update via ADB."
4. Run `adb sideload <rom_filename>.zip`.
5. Select "yes" if prompted for signature failure.
6. Factory Reset / Format Data.
7. Reboot to system and Enjoy!

**ROM Update/Dirty flash:**

1. Reboot to recovery.
2. Apply update > Apply from ADB.
3. Open a command prompt and sideload the ROM using the command `adb sideload <rom_filename>.zip`.
4. Reboot to system.
