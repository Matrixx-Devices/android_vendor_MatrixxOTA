## Before Starting Flashing

- Backup all your data to an external source.
- A **clean flash** is mandatory if coming from another ROM or a previous unofficial build.
- Keep in mind that a clean flash is always recommended when coming from another ROM.

## Clean Flash

1. Reboot to fastboot mode.
2. Flash Matrixx recovery image via`fastboot flash recovery recovery.img`
3. Reboot to recovery mode: `fastboot reboot recovery`.
4. Format data.
5. Connect your phone to the PC.
6. Apply update via ADB via `adb sideload <rom_filename>.zip`.
7. Confirm the update and click "Yes" to reboot to recovery.
8. Optional : for KSU support :
    - Select 'Reboot to bootloader'
    - Download the "boot_ksu_patched_XXX.img" (where XXX is the current Matrixx version)
    - Flash it via `fastboot flash boot boot_ksu_patched_XXX.img`
9. Reboot to the system.

## ROM Update / Dirty Flash

1. Reboot to recovery.
2. Go to `Apply update > Apply from ADB`.
3. In the command prompt, sideload the ROM using the command: `adb sideload <rom_filename>.zip`.
4. Confirm the update and click "Yes" to reboot to recovery.
5. Optional : for KSU support :
    - Select 'Reboot to bootloader'
    - Download the "boot_ksu_patched_XXX.img" (where XXX is the current Matrixx version)
    - Flash it via `fastboot flash boot boot_ksu_patched_XXX.img`
6. Reboot to the system.
