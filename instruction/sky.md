## Before Starting Flashing

- Backup all your data to an external source.
- A **clean flash** is mandatory if coming from another ROM or a previous unofficial build.
- Keep in mind that a clean flash is always recommended when coming from another ROM.
- **Recommended Recovery:** [OrangeFox](https://sourceforge.net/projects/projectmatrixx/files/Android-15/sky/recovery/recovery.img/download)
- **Recommended Firmware:** [OS2.0.5.0.VMWEUXM](https://xmfirmwareupdater.com/download/?file=fw_sky_eea_global_sky_eea_global-ota_full-OS2.0.5.0.VMWEUXM-user-15.0-0c811cb5a7.zip)

## Clean Flash

1. Reboot to fastboot mode.
2. Flash Matrixx recovery image via`fastboot flash recovery recovery.img`
3. Reboot to recovery mode: `fastboot reboot recovery`.
4. Format data.
5. Connect your phone to the PC.
6. Apply update via ADB via `adb sideload <rom_filename>.zip`.
7. Confirm the update and click "Yes" to reboot to recovery.
8. Reboot to the system.

## ROM Update / Dirty Flash

1. Reboot to recovery.
2. Go to `Apply update > Apply from ADB`.
3. In the command prompt, sideload the ROM using the command: `adb sideload <rom_filename>.zip`.
4. Confirm the update and click "Yes" to reboot to recovery.
5. Reboot to the system.
