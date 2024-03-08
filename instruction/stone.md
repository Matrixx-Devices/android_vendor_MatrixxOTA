**Before start flashing.....**
- At first make sure your bootloader is unlocked and you have downloaded the latest platform tools and drivers. You can check this link for simple installation!
- Always have backup of your internal storage
- For vanilla variant, if u need gapps, [**Nikgapps Core is Recommended**](https://sourceforge.net/projects/nikgapps/files/Releases/NikGapps-U/)

----

💠 FLASHING CUSTOM RECOVERY >>



1. Download TWRP image or roms boot image (if the dev recommend to use roms recovery), extension is .img file from #twp-latest

2. Now boot your device into fastboot mode (turn off the device first then press and hold at the same time power button+volume down)

3. Now open cmd in you computer and connect your device which is in fastboot mode

4. First check if your device is connected successfully or not by giving command fastboot devices and hit enter (if your device is recognized then you're good to go)

5. Now again give the command fastboot flash boot <drag and drop twrp.img or roms boot.img file here which you downloaded>

6. after flashing the boot image, give command fastboot reboot recovery 



◽ FLASHING ROM ONWARDS >

7. Now your device will boot into recovery and format data from there

8. If you cant format data and want to do a clean flash then simply flash rom and format data later, you can flash rom from your sd card or by adb sideload..



🔸 SD CARD/OTG method: 

1. Select rom file from the storage

2. Flash it from recovery

3. Reboot to recovery (it will boot into your roms recovery) and format data from there (if you couldn't earlier)

3. Reboot to system



🔸 Sideload method:

1. Copy your rom file in c drive

2. Go to advanced>adb sideload in twrp

3. Give the command in cmd adb sideload <drag and drop the rom zip file> and hit enter

4. Wait to finish the installation

5. Reboot to recovery (it will boot into your roms recovery) and format data from there (if you couldn't earlier)

6. Reboot to system



▫️ IF YOU WANT TO FLASH GAPPS >



1. Download your favorite gapps (or recommended by dev) by #gapps

2. After flashing the rom reboot into recovery again and then flash gapps file just like the rom (from OTG or by sideload)



▫️ IF YOU WANT TO KEEP TWRP >


1. After flashing the rom don't reboot to recovery

2. Go to advanced from twrp home

3. Select the option called install recovery ramdisk

4. Now go back and reboot to recovery and format data now (if you wanna do a clean flash)

5. Otherwise just reboot into the system

We don't recommend keeping TWRP, we're not responsible if anything happens
