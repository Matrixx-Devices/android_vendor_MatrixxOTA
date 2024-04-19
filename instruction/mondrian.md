## Before Starting Flashing

- Backup all your data to an external source.
- A **clean flash** is mandatory if coming from another ROM or a previous unofficial build.
- Keep in mind that a clean flash is always recommended when coming from another ROM.

## Clean Flash

1. Reboot to fastboot mode.
2. Flash the required images:
    - `fastboot flash vendor_boot vendor_boot.img`
    - `fastboot flash boot boot.img`
    - `fastboot flash recovery recovery.img`
3. Reboot to recovery mode: `fastboot reboot recovery`.
4. Format data.
5. Connect your phone to the PC.
6. Apply update via ADB:
    - Run the command: `adb sideload <rom_filename>.zip`.
7. Confirm the update and click "Yes."
8. Reboot to the system.

## ROM Update / Dirty Flash

1. Reboot to recovery.
2. Go to `Apply update > Apply from ADB`.
3. In the command prompt, sideload the ROM using the command: `adb sideload <rom_filename>.zip`.
4. Reboot to the system.
