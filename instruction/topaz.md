**Before start flashing.....**

1. Your bootloader must be unlocked
2. You have to be on OS1.0.5.0.UMGMIXM (for topaz) / OS1.0.7.0.UMTMIXM (for tapas) firmware
3. You can download matrixx recovery on sourceforge: recovery folder
----
## Gapps variant

**Clean flash:**

**If you are using Orange Fox:**
1. Reboot into the recovery
2. Wipe metadata, cache, do format data
3. Flash ROM with "Reflash OrangeFox" option enabled.

**If you are using Matrixx Recovery:**
1. Reboot into the recovery
2. Select "Apply Update" -> ADB
3. Connect to PC
4. Enter the command: adb sideload Matrixx.zip (change the name to the correct one).
5. Format data

**Dirty flash:**

**If you are using Orange Fox:**
1. Boot into recovery
2. Wipe dalvik, cache
3. Flash the ROM

**If you are using Matrixx Recovery:**
1. Reboot into the recovery
2. Select "Apply Update" -> ADB
3. Connect to PC
4. Enter the command: adb sideload Matrixx.zip (change the name to the correct one).
