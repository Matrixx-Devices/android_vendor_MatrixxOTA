## Before Flashing

- Backup all your data to an external source.
- A **clean flash** is mandatory if coming from another ROM.
- **Recommended Recovery:** [Matrixx Recovery](https://sourceforge.net/projects/projectmatrixx/files/Android-15/stone/recovery/boot.img/download)

## Clean Flash

1. Reboot to fastboot mode.
2. Flash Matrixx recovery image via`fastboot flash boot boot.img`
3. Reboot to recovery mode: `fastboot reboot recovery`.
4. Format data.
5. Connect your phone to the PC.
6. Apply update via ADB with `adb sideload <rom_filename>.zip`.
6.1. Click "Yes" to reboot to recovery to flash additional packages eg. Gapps, Magisk.
6.2 Format data again
7. You can ignore 6.1 and 6.2 if you dont want to flash anything else and click "No".
8. Reboot to the system.

## ROM Update / Dirty Flash

1. Reboot to recovery.
2. Go to `Apply update > Apply from ADB`.
3. In the command prompt, sideload the ROM using the command: `adb sideload <rom_filename>.zip`.
3.1 Reboot to recovery again and sideload Gapps or Magisk if you had them installed.
4. Reboot to the system

