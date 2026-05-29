# Flashing Instructions

Always have backup of your internal storage
- Use Ofox/Twrp recovery meant for Android 16[**OrangeFox**](https://orangefox.download/device/6654e14cd739290feafe4383).
- For vanilla variant, if u need gapps, [**Nikgapps is Recommended**](https://sourceforge.net/projects/nikgapps/files/Releases/Android-16/)
----

# First Time Installation (Clean Flash):

- Flash recovery
- Reboot to recovery
- Format data
- Install latest firmware for your region
- Reboot recovery
- Install Matrixx.zip
- Reboot recovery
- Install GApps (optional For Vanilla Variant)
- Format Data
- Reboot system

# ADB Sideload Command:
- adb sideload Matrixx.zip
- When asked to sideload GApps, choose "Yes" to reboot to recovery.
- Choose "No" if you don't want GApps and want to reboot directly to system.

If installing GApps For Vanilla Version:
adb sideload gapps.zip

- Reboot to system after installation.

# Update Installation

Via Recovery (Recommended):
- Boot to recovery
- Flash Matrixx.zip
- Reinstall GApps (For Vanilla Variant)
- Wipe cache and dalvik
- Reboot system

