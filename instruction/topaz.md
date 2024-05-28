**Before start flashing.....**

1. Your bootloader must be unlocked
2. You have to be on OS1.0.5.0.UMGMIXM (for topaz) / OS1.0.7.0.UMTMIXM (for tapas) firmware
----

## Vanilla variant

**Clean flash:**
- If you are using Orange Fox
1. Reboot into the recovery
2. Wipe metadata, cache, do format data
3. Flash ROM with "Reflash OrangeFox" option enabled.

- Optional if you need gapps:
4. Reboot in recovery
5. Flash modified RO2RW (https://t.me/NPDTeam/1/16322)
6. Reboot into recovery
7. Flash NikGapps (prefer core variant).

- If you are using Matrixx Recovery:
1. Reboot into the recovery
2. Select "Apply Update" -> ADB
3. Connect to PC
4. Enter the command: adb sideload Matrixx.zip (change the name to the correct one).
5. Format data

- If you need gapps:
6. Simply flash through adb sideload NikGapps (prefer core variant).

**Dirty flash:**
- If you are using OrangeFox
1. Boot into recovery
2. Wipe dalvik, cache
3. Flash the ROM

- If you installed gapps before (OrangeFox)
4. Flash modified RO2RW (https://t.me/NPDTeam/1/16322)
5. Reboot into recovery
6. Flash NikGapps (Omni or Full is NOT RECOMMENDED).

- If you are using Matrixx Recovery
1. Reboot into the recovery
2. Select "Apply Update" -> ADB
3. Connect to PC
4. Enter the command: adb sideload Matrixx.zip (change the name to the correct one).

- If you installed gapps before (Matrixx Recovery):
5. Simply flash through adb sideload NikGapps (prefer core variant)
