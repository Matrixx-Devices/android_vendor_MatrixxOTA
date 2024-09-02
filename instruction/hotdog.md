**Disclaimer:**
- We're not responsible for bricked devices, dead SD card or anything happens with your device.
- Flash on your own risk/knowledge.
- Take your data backup before proceed.

**Before start flashing.....**
- If comming from OxygenOS or from anyother ROM, Required clean flash
- Required OxygenOS 12 in both slot, If already then skip step 3 & 4 if not **must follow all steps**
- Gapps included so no need to flash/sideload GApps
- Download recovery from [**HERE**](https://sourceforge.net/projects/projectmatrixx/files/Android-14/hotdog/Recovery/)
- Download copy-partition zip [**HERE**](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/copy-partitions-20220613-signed.zip/download)


**Clean Flash:**
1. Reboot to bootloader & connect your phone to PC
2. flash recovery by using command
```
fastboot flash recovery recovery.img
```
3. Reboot to recovery > Apply update > Apply from ADB
4. Sideload copy-partition zip by using command 
```
adb sideload copy-partitions-20220613-signed.zip
```
5. After complete, Back to recovery home page & tap Factory reset > Format data/factory reset
6. Back to recovery home page & tap > Apply update > Apply from ADB
7. Now sideload rom using command
```
adb sideload <rom_filename>.zip
```
8. Now reboot to system.

**Rom Update/Dirty flash:**
1. Reboot to recovery
2. Apply update > Apply from ADB
3. Open command prompt & sideload rom using command
```
adb sideload <rom_filename>.zip
```
4. Reboot
