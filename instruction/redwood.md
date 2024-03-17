**Before start flashing.....**
- Backup all your data to any external source. 
- Update your device to latest firmware of your region.
- Gapps included so no need to flash/sideload GApps.

**Clean Flash:**
1. Download The Boot , Dtbo  And Vendor_boot Images  
2. Connect To Pc
3. Reboot To Fastboot  (  Press  Both Power_button_key + Vol_down_key)
4. fastboot flash boot boot.img
5. fastboot flash vendor_boot  vendor_boot.img
6. fastboot flash dtbo dtbo.img 
7. fastboot reboot recovery
8. Select Wipe Data/factory Reset & Confirm
9. Select 'apply Update' From Adb
10. adb sideload  Matrixx***.zip
11. Select Wipe Data/factory Reset & Confirm
12. After Installation Complete, Reboot System

**Rom Update/Dirty flash:**
1. Reboot to recovery
2. Apply update > Apply from ADB
3. Open command prompt & sideload rom using command ```adb sideload Matrixx***.zip```
4. Reboot
