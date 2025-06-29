# 29-June-2025
- Update from NOS V3.0-250506-1805
- Nothing Camera support
- Optimize dalvik heap config for performance
- Update dolby libs
- Set fixed size to 3GB instead of 40% of RAM
- Improvements to performance and system stability

# 22-May-2025
- Switch back to prebuild audio blobs
- Fix low mic sound
- Disable speaker audio spatializer by default
- Configure max values for background and dex2oat groups
- Unset scheduler ratelimits
- Switch BtAudio to AIDL
- Tweak dolby dax config
- Switch to PowerShare AIDL
- Set zram size to 40%
- Checkout fstab from NOS 3.0

# 06-May-2025
- Pong: Use common PowerShare HAL
- Pong: Set volume steps to 15
- Pong: powerhint: Drop cpu interection changes
- Pong: powerhint: Tune down cpu launch duration value
- Pong: powerhint: Tune uclamp values for efficiency
- Pong: Remove some unused props
- Pong: Fix FPS tile
- Pong: switch to common QCOM AIDL bootctrl HAL

# 22-March-2025
- Fix dolby sepolicy
- Bring back stream postprocess
- Drop sdrHdrRatio from displayconfig
- Fix Lockscreen cpu info
- Fixup glyph torch dying immediately when turning on during glyph music visualisation

# 2-March-2025
- Switch to oss audio HAL
- Unset scheduler ratelimits
- Switch to kryo785
- Adjust LAUNCH duration to 1200ms for better balance
- Set swappiness value to 60
- Fix powershare sepolicy
- Implement torch light control
- Improvements to performance and system stability

# 12-February-2025
- Switch to Xiaomi Dolby libs 
- Switch to Meteoric kernel
- Configuration for dolby spatial audio
- Note: signing keys are changed, dirty flash should work fine, but recommended to take backup just incase
- Improvements to performance and system stability

# 2-February-2025
- Initial Matrixx A15 release
