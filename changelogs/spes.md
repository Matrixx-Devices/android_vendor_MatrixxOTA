# 21-Mar-2025
- Add front-facing camera protection
- Add support for modernized doze double/single tap to wake
- Drop legacy double-tap-to-wake config
- Drop MIUI Camera
- Drop old Android Go configurations
- Enable fts_gesture_mode
- Enable Bluetooth HAL to read MAC address from NV
- Enable Touch Gestures
- Handle DT2W feature through Xiaomi Touch
- Implement double/single tap attributes
- Implement support for multiple touch sensor paths
- Remove camera-daemon boost configs
- Remove unneeded NFC package
- Many more misc. changes

# 02-Mar-2025
- Add WPA3 definition for SAE authentication
- Allow system_server to read fastcharge node
- Build QTI Thermal AIDL HAL
- Disable config_avoidGfxAccel overlay
- Enable force LTE_CA toggle overlay
- Fix video thumbnail bug
- Fix WPA3 Wi-Fi authentication
- Remove software C2 codec overrides
- Update reserved partition size
- Many more misc. changes

# 13-Feb-2025
- Synced with the latest source
- Switched to the Murali kernel
- Added support for displaying battery info in settings
- Fixed battery drain issues
- Reduced ZRAM to 50%
- Enabled deep buffer for media by default
- Enabled WPA3/SAE
- Enabled smart pixels
- Reduced wakeup events to 100ms
- Disabled wakeup source creation
- Updated to Wakelock Blocker driver v1.1.0
- Reduced wakelock hold time to 1000ms
- Reduced timeout for uncongestion
- Reduced GC thread urgent sleep time to 50ms
- Disabled I/O stats accounting by default
- Reduced NTP wakeups
- Optimized file overwrites
- Applied branch optimization in free slowpath
- Many more misc. changes

# 02-Feb-2025
- Initial A15 QPR1 Release
