
[!!!] WARNING [!!!]

Don't use fastboot reboot recovery or else you device may brick.

[i] PRE-REQUISITES

* Read through the instructions at least once before actually following them, 
  so as to avoid any problems due to any missed steps!
* Make sure your computer has adb and fastboot. Setup instructions can be 
  found here.
* Download or extract vendor_boot.img 


[>] INSTALLATION INSTRUCTIONS

1. Power off the device, and boot it into bootloader mode: With the device 
   powered off, hold volume down + power.
   
2. Flash the image files to your device by typing: 
   fastboot flash vendor_boot --slot=all vendor_boot.img
   
3. Reboot to recovery mode by typing: fastboot reboot and quickly holding 
   volume up button.
   
4. Now select Factory Reset, then Format data / factory reset and continue 
   with the formatting process. This will delete all files stored in the 
   internal storage, as well as format your cache partition.
   
5. Return to the main menu.
   
6. Sideload the ROM .zip package by typing: 
   adb sideload /path/to/zip
   
7. Choose no after sideload(reboots into recovery).
   
8. Reboot by returning to main menu and hitting: "Reboot system now".

