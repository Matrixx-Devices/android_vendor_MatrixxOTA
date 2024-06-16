**Before start flashing.....**
- Backup all your internal storage
- GApps are included, so you don't need to flash them

**Clean flash**
1. Reboot to fastboot
2. ```fastboot flash dtbo dtbo.img```
3. ```fastboot flash vendor_boot vendor_boot.img```
4. ```fastboot flash boot boot.img``` 
5. Reboot to recovery
6. Select Factory reset and Format data/factory reset
7. Select Apply Update and Apply Update from ADB
8. Now connect your phone to PC and type ```adb sideload Matrixx.zip```
9. Reboot to system and enjoy :)

**Dirty flash** 
1. Reboot to recovery
2. Select Apply Update and Apply Update from ADB
3. Connect your phone to PC and flash rom with ```adb sideload Matrixx.zip```
4. Reboot to system and enjoy :)
