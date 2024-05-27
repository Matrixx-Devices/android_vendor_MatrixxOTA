**Before start flashing.....**

- Always have backup of your internal storage
- Use recovery meant for Android 14. Check the note [**#twrp_a14**](https://t.me/matrixxalioth)
- To retain recovery after rom flash, don't forget to tick the option "Automatically Reflash TWRP after flashing a rom" in recovery. Else recovery will be replaced by aosp recovery from rom
- Get ready to provide logs/crash url and steps to reproduce the bug along with bug reports

----

## Gapps variant

**Clean flash:**
- Flash the rom 
- Flash current recovery
- Reboot to recovery 
- Format Data
- Flash the firmware
- Reboot to System

**Dirty flash:**
- Download the ROM
- Boot into recovery
- Wipe Dalvik/ArtCache
- Flash the ROM
- Reboot To System

