**Before start flashing.....**
- Backup all your data to any external source. 
- If you are coming from oos/cos you need to use super flasher and oos/cos on both slots.
- Get images for here (https://sourceforge.net/projects/projectmatrixx/files/Android-15/giulia/images/)

**Clean Flash:**
1. Download The boot,init_boot,vendor_boot and recovery.img (super_empty for ace 5 users)
2. Connect To Pc
3. Reboot To Fastboot  (  Press  Both Power_button_key + Vol_down_key)
4. fastboot flash boot boot.img
5. fastboot flash vendor_boot vendor_boot.img
6. fastboot flash init_boot init_boot.img
7. fastboot flash recovery recovery.img
8. fastboot reboot recovery
9. Select Wipe Data/factory Reset & Confirm
10. Select 'apply Update' From Adb
11. adb sideload  ```Matrixx***.zip```
12. Select Wipe Data/factory Reset & Confirm
13. After Installation Complete, Reboot System

**Rom Update/Dirty flash:**
1. Reboot to recovery
2. Apply update > Apply from ADB
3. Open command prompt & sideload rom using command ```adb sideload Matrixx***.zip```
4. Reboot
