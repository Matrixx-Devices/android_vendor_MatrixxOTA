## Initial Flashing Instructions ##

- Backup all your data to an external source.
- A **clean flash** is mandatory if coming from another ROM or a previous unofficial build.
- Keep in mind that a clean flash is always recommended when coming from another ROM.

## Clean Flash

1. Reboot to fastboot mode.
2. Flash Matrixx boot image via`fastboot flash boot boot.img`
3. Flash Matrixx dtbo image via`fastboot flash dtbo dtbo.img`
4. Flash Matrixx vbmeta image via`fastboot flash vendor_boot vendor_boot.img`
5. Flash Matrixx recovery image via`fastboot flash recovery recovery.img`
6. Reboot to recovery mode: `fastboot reboot recovery`.
7. Format data.
9. Connect your phone to the PC.
10. Apply update via ADB via `adb sideload <rom_filename>.zip`.
11. Confirm the update and click "Yes" to reboot to recovery.
12. Reboot to the system.

## ROM Update / Dirty Flash

1. Reboot to recovery.
2. Go to `Apply update > Apply from ADB`.
3. In the command prompt, sideload the ROM using the command: `adb sideload <rom_filename>.zip`.
4. Confirm the update and click "Yes" to reboot to recovery.
5. Reboot to the system.
