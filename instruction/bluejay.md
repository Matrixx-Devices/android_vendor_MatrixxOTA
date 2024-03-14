**Before start flashing…..**
- Backup all your data to any external source.

**Clean Flash:**
- Download ROM
- Download recovery images from [**HERE**](https://sourceforge.net/projects/wilmabumsson/files/Installation_Kit_Bluejay_PM_A14/)
- Boot device into bootloader.
- Flash recovery images

```
fastboot flash boot boot.img
fastboot flash dtbo dtbo.img
fastboot flash vendor_boot vendor_boot.img
```
- Choose recovery and press Power
- Format Data
- Sideload ROM ```adb sideload rom.zip```
- Reboot and enjoy ROM

**Rom Update/Dirty flash:**
- Reboot to recovery
- Apply update > Apply from ADB
- Open command prompt & sideload rom using command ```adb sideload <rom_filename>.zip```
- Reboot

**Note:**
- If getting any issue after dirty flash, Flash clean before reporting.
