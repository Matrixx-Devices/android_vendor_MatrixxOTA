### Installation Guide For Project Matrixx on Xiaomi Pad 6 - pipa
 
# Clean flash
• If you already have aosp recovery installed, u can skip the next step, or keep following
• Download boot and vendor_boot from recovery folder of rom download link
• Now connect tab to PC, boot to fastboot mode, open cmd, type fastboot flash boot boot.img & fastboot flash vendor_boot vendor_boot.img 
• Now reboot to matrixx aosp recovery
• Format all partition and data through recovery
• Then go to install & adb sideload
• Run adb sideload rom.zip
• Finally reboot to system!

# Dirty flash
• You should receive OTA when new build is released it will auto update everything
• If not, just sideload the new rom zip and reboot [dont wipe or format anything except cache]
