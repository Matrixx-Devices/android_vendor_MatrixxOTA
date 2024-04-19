## Before Starting Flashing

- Make sure your bootloader is unlocked and you have downloaded the latest platform tools and drivers. You can check [this link](#) for a simple installation guide.
- Always back up your internal storage.
- For vanilla variant ROMs, if you need GApps, [**NikGapps Core**](https://sourceforge.net/projects/nikgapps/files/Releases/NikGapps-U/) is recommended.

---

## Flashing Custom Recovery

1. Download TWRP image or the ROM's boot image (if the developer recommends using the ROM's recovery) in `.img` format from the latest source.

2. Boot your device into fastboot mode (power off your device, then hold power button and volume down simultaneously).

3. Connect your device to your computer in fastboot mode and open a command prompt.

4. Check if your device is connected successfully by running the command `fastboot devices`. If your device is recognized, proceed to the next step.

5. Run the command `fastboot flash boot <drag and drop the TWRP or ROM boot image file here>`. 

6. After flashing the boot image, run the command `fastboot reboot recovery`.

---

## Flashing ROM Onwards

7. Your device will boot into recovery. Format data from there.

8. If you can't format data and want to do a clean flash, simply flash the ROM and format data later. You can flash the ROM from your SD card or using ADB sideload.

### Flashing from SD Card/OTG

1. Select the ROM file from storage.
2. Flash it from recovery.
3. Reboot to recovery and format data (if you didn't earlier).
4. Reboot to the system.

### Sideloading

1. Copy your ROM file to your computer's C drive.
2. In TWRP, go to `Advanced > ADB sideload`.
3. In the command prompt, run the command `adb sideload <drag and drop the ROM zip file>`.
4. Wait for the installation to finish.
5. Reboot to recovery and format data (if you didn't earlier).
6. Reboot to the system.

---

## Flashing GApps

1. Download your favorite GApps (or the developer-recommended one) from a trusted source.
2. After flashing the ROM, reboot into recovery again and flash the GApps file like the ROM (from OTG or by sideload).

---

## Keeping TWRP

1. After flashing the ROM, do not reboot to recovery.
2. In TWRP, go to `Advanced` and select `Install recovery ramdisk`.
3. Now go back, reboot to recovery, and format data (if you want a clean flash).
4. Otherwise, just reboot into the system.

**Note:** We do not recommend keeping TWRP. We are not responsible if anything happens.
