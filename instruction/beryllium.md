* DYNAMIC PARTITIONS ROM-:

Recovery-: Orangefox/TWRP Dynamic Partition supported recovery.

Links-: https://www.pling.com/p/2117593/(OFOX)
https://www.pling.com/p/1346294/#files-panel(TWRP)



IMPORTANT TO NOTE:

* Do not try to switch to any other kernel

* Do not use SYSTEM_EXT recoveries to flash this



* You must clean flash in following cases-:

- You are coming from any other ROM or MIUI

- You are coming from previous Android Version

- You are coming from Non Retrofit Dynamic ROM



* Clean Flash (coming from a different ROM)

Clean flash involves formatting data which means you will be loosing data stored in the internal storage of your device, data in SD Card should not be affected. I will not be responsible for any loss of data.

1- Download ROM, recovery to your computer

2- Reboot the device to bootloader (Fastboot Mode)

3- Flash recovery image by running fastboot flash recovery <path/to/recovery.img> in terminal

3- Reboot to recovery mode

4- Wipe dalvik cache,cache,data partitions

5- On your phone [which is in recovery mode], Select ADB Sideload option

Flash the ROM through ADB sideload by running adb sideload <path/to/rom.zip> in terminal
6- Reboot to recovery again

7- Format data

8- Reboot



* Dirty Flash / Update

There will be no loss of data if everything goes well. Keep backups incase of any mishap. I will not be responsible for any loss of data.

1- Download ROM file to your device

2- Reboot the device to recovery

3- Wipe dalvik cache/cache partitions

4- Flash rom.zip

5- Reboot

