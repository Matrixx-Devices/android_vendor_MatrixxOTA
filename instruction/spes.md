## Before You Start:
- Always back up your important data
- Use the official [OrangeFox](https://orangefox.download/device/spes) Recovery
---

### Clean Flash:
- Ensure you have Fastboot drivers installed and [Platform Tools](https://developer.android.com/tools/releases/platform-tools) downloaded on your system
- Extract the Platform Tools folder and place it in your boot drive
- Download the Compatible recovery from the link above
- Enable USB Debugging on your device
- Check if the device connected properly or not by:
```
adb devices
```
- It'll show the device id/serial number
- Boot into fastboot eithar manually or using Platform Tools by running this:
```
adb reboot bootloader
```
- While in Fastboot Mode, flash the recovery by:
```
fastboot boot recovery.img
```
- or
```
fastboot boot path/to/recovery.img
```
- Press enter, Your device should now boot into recovery mode
- Click on install
- Go to path/to/Matrixx*.zip
- Select the rom file you downloaded
- Swipe to flash the rom
- *If vanilla:* Flash rom > Format data > Reboot to revovery > Flash Gapps > Reboot system
- Once flash(Gapps/Regular) done, format data and reboot system
- If it said couldn't format data then Home > Advance > Reboot to revovery > Format data > Reboot system
---

### Dirty Flash:
- Follow the same steps as Clean Flash, but do not format data
- Instead, just: Boot into recovery > Flash rom > Reboot
---

### Flash Kernel:
- Boot into recovery
- Flash/Sideload(adb) the kernel file
- Reboot system
- You can also flash magisk by using this same method
---

### Notes:
- Since there's no dedicated recovery partition, you must flash recovery every time after flashing the ROM
- After the dirty flash your root/kernel will be overwritten. So, take a backup of your favourite kernel
- If you face any bug or issues, politely report them with [logs](https://github.com/nathanchance/android-tools/blob/main/guides/proper_bug_reporting.txt) into the [device support group](https://t.me/TanvirBuildsSupport)
- When dirty/clean flashing via OrangeFox, do not reflash Ofox after flashing the ROM
---
