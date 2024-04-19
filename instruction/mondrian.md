Before start flashing.....

    Backup all your data to any external source.
    CLEAN FLASH is mandatory if coming from another from or a previous unofficial build. 
    Keep in mind that a clean flash is always recommended when coming from another rom.

Clean Flash:

    Reboot to fastboot and flash the required images : fastboot flash vendor_boot vendor_boot.img && fastboot flash boot boot.img && fastboot flash recovery recovery.img
    Reboot to recovery : fastboot reboot recovery
    Format Data
    Plug your phone to pc and Apply update via ADB
    Run adb sideload <rom_filename>.zip
    Click yes
    Reboot to system

Rom Update/Dirty flash:

    Reboot to recovery
    Apply update > Apply from ADB
    Open command prompt & sideload rom using command adb sideload <rom_filename>.zip
    Reboot to system
