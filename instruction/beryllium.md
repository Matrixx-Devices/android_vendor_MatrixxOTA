**DYNAMIC PARTITIONS ROM-:**

- Recovery-: Orangefox or TWRP Dynamic Partition supported recovery.
- Links-: [**OFOX**](https://www.pling.com/p/2117593/), [**TWRP**](https://www.pling.com/p/1346294/#files-panel)

**IMPORTANT TO NOTE:**

- Do not try to switch to any other kernel
- Do not use SYSTEM_EXT recoveries to flash this

**You must clean flash in following cases-:**

- You are coming from any other ROM or MIUI
- You are coming from previous Android Version
- You are coming from Non Retrofit Dynamic ROM

----

# GAPPS Varient

**Clean Flash (coming from a different ROM)**

- Clean flash involves formatting data which means you will be loosing data stored in the internal storage of your device, data in SD Card should not be affected. I will not be responsible for any loss of data.

- Download ROM, recovery to your computer
- Reboot the device to fastboot mode
- Flash recovery image by running ```fastboot flash recovery <path/to/recovery.img>``` in terminal
- Reboot to recovery mode
- Wipe dalvik cache,cache,data partitions
- On your phone ```(which is in recovery mode)```, Select ADB Sideload option, Flash the ROM through ADB sideload by running ```adb sideload <path/to/rom.zip>``` in terminal
- Reboot to recovery again
- Format data
- Reboot

**Dirty Flash or Update**

- There will be no loss of data if everything goes well. Keep backups incase of any mishap. I will not be responsible for any loss of data.

- Download ROM file to your device
- Reboot the device to recovery
- Flash rom.zip
- Wipe dalvik cache and cache partitions
- Reboot

