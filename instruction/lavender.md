Instruction to flash newer ROMs with Retrofit Dynamic Partitions:

- Ignore recovery errors at the first installation, they're normal
- if you are on the latest firmware no need to flash it again
- If you are unsure about the firmware, just flash the latest "V12.5.3.0" Download (https://t.me/SnxLav/104852)

# Installation of Retrofit Dynamic Partitions ROMs:
1. Flash 4.19 Dynamic recovery - recommended Recovery
[Fastboot: fastboot flash recovery recovery.img]
2. Enter the newly flashed recovery
3. Untoggle "Unmount System/vendor before installing a ZIP".
4. Wipe system, vendor, cache & metadata partition
5. Flash the ROM (Ignore system mount error)
6. If Vanilla ROM (Reboot to recovery and then flash GApps)
7. Wipe data on Decrypted builds (Format data on Encrypted builds)
8. Reboot and Enjoy (Ignore no os installed warning)


# Update to new version 
Flash ROM Updates:
0. take backup of important data, AOSP is unpredictable 
1. Enter recovery
2. Flash the update and Gapps (if vanilla build)
3. Wipe dalvik, cache
4. Reboot and Enjoy

# Switch to another Retrofit Dynamic Partitions ROM:
1. Enter recovery
2. Flash the ROM and Gapps (if vanilla build)
3. Wipe data on Decrypted builds (Format data on Encrypted builds)
4. Reboot and Enjoy

# Go back to standard partition ROM:
1. Install Standard recovery
2. Enter the newly flashed recovery
3. Wipe system & vendor partition
4. Flash the ROM
5. Factory Reset (Format data is recommended)
6. Change data filesystem to EXT4
7. Reboot and Enjoy
