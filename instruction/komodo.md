**Before start flashing.....**
- Always keep a recent backup of your internal storage

----

**Flashing Steps**

**Clean flash:**
- Download the ROM and all the recovery images
- Boot into bootloader mode
- Flash all the recovery images to their designated partitions with the official Google fastboot tool. For e.g.:
```
fastboot flash boot boot.img
fastboot flash vendor_kernel_boot vendor_kernel_boot.img
fastboot flash dtbo dtbo.img
fastboot flash init_boot init_boot.img
fastboot flash vendor_boot vendor_boot.img
```
- Boot into recovery
- Factory reset -> Format data -> Press Yes
- Apply update -> Apply update from ADB
- Sideload the ROM and wait for it to reach 47% progress. The command is as follows:
```
adb sideload Matrixx*.zip
```
- On screen, you should be prompted to press Yes or No. Just press Yes and wait for the phone to boot into recovery.
- Flash a compatible custom kernel or any kind of additions with the Apply update section as done before. (Optional)
- Once you're finished with recovery mode, reboot to system now.

**Dirty flash:**
- Download the ROM
- Boot into recovery
- Wipe Dalvik/Art Cache and cache
- Flash the ROM
- Reboot to system
