## Before Starting Flashing

- Backup all your data to an external source.
- A **clean flash** is mandatory if coming from another ROM or a previous unofficial build.
- Keep in mind that a clean flash is always recommended when coming from another ROM.
- Always remember that firmware is not included in the rom, so always update to the recommended firmware else bugs will appear.

## Clean Flash

1. Reboot to fastboot mode.
2. Download Required firmware which is OOS 14.0.0.604(EX01) for Oneplus 9R from [here](https://github.com/Wishmasterflo/Firmware_flasher)
3. Follow the instructions on the link and then proceed to do the below steps
4. Flash Matrixx boot image via`fastboot flash boot boot.img`
5. Flash Matrixx dtbo image via`fastboot flash dtbo dtbo.img`
6. Flash Matrixx vbmeta image via`fastboot flash vbmeta vbmeta.img`
7. Flash Matrixx recovery image via`fastboot flash recovery recovery.img`
8. Reboot to recovery mode: `fastboot reboot recovery`.
9. Format data.
10. Connect your phone to the PC.
11. Apply update via ADB via `adb sideload <rom_filename>.zip`.
12. Confirm the update and click "Yes" to reboot to recovery.
13. Reboot to the system.

## ROM Update / Dirty Flash

1. Reboot to recovery.
2. Go to `Apply update > Apply from ADB`.
3. In the command prompt, sideload the ROM using the command: `adb sideload <rom_filename>.zip`.
4. Confirm the update and click "Yes" to reboot to recovery.
5. Reboot to the system.
