# 09-July-2025
 overlay: Update brightness restrictions for VRR.
- blobs: Update some blobs from LA.UM.9.15.2.r1-10600-KAMORTA.QSSI14.0
- blobs: Update power profiles from TKQ1.221114.001-V816.0.11.0.TGKMIXM-release-keys
- Reduced zRAM size to 60% (Previous was causing too much overhead).
- kernel: Synced the kernel's sources to the latest.

# 30-June-2025
- Revert "Enable zRAM Writeback".
- Increased zRAM Size.
- sepolicy: Address hal_graphics_composer_default denial. 
- sepolicy: Label remaining Wakeup nodes.
- kernel: Synced the Kernel's sources to the latest.

# 26-June-2025
- Fixed proximity sensor on not working.
- Dropped GameBar to modernize XiaomiParts.
- Debloated some apps that came included in the ROM.
- kernel: Synced the kernel's sources to the latest
- source: Fixed an issue where Dirty Flashing the ROM causes bootloop.

# 21-June-2025
- Enabled LTE_CA Workaround
- Reduced Screen Brightness
- Switched to AIDL ST NFC HAL
- overlay: Updated CarrierConfig from TKQ1.221114.001-V816.0.11.0.TGKMIXM-release-keys
- overlay: Synced brightness values with spesn TKQ1.221114.001-V816.0.11.0.TGKMIXM-release-keys
- sepolicy: Removed duplicate IR rules
- kernel: Updated the kernel sources to the latest (Credits to @angelomds42)
- Disable UFFD GC via OVERRIDE_ENABLE_UFFD_GC

# 04-June-2025
- props: Added touch improvement props
- props: Enabled Incremental on the device
- props: Enabled the pre-rendering feature
- system: Optimized SF durations
- system: Improved surfaceflinger
- audio: Removed direct flag for VOIP RX
- wifi: Enabled Optimized Power Management
- wifi: Smarter descicions on wether to use a 2 or 5Ghz AP
- Reduced boot time
- Disabled camera perflock
- Disabled Dynamic RR (refresh-rate)
- overlays: Disabled 5G toggle in QS
- overlays: Offloaded WM shell to another thread
- Enabled LTO Optimizations
- Disable default game FPS Limit in developer-options
- Many more misc. changes from DT

# 26-May-2025
- Fixed an issue where Camera on certain applications like TG, Brave (QR Code Scanner) or Face Unlock / Banking Apps doesn't work.
- Addressed some cameraserver denials
- Migrated Lineage Health to soong_config_set
- Many more misc. changes from DT

# 21-May-2025
- Initial Release from the New Maintainer (v11.5.0)
- GameBar & MIUI Camera is included
- Import functional OMX codecs from rhode
- Update configs with fogona
- Drop unused media_profiles
- Copy media_codecs_vendor to media_codecs
- Reduce aggressive TAUClampBoost at launch
- Many more Misc. changes from Device Tree

# 23-Mar-20225
- Add init.spes.rc
- Disable turbulence noise
- Fix log spam in logcat
- Introduce GameBar v2.0
- Move GameBar to system settings
- Add custom icon for GameBar on system settings
- Move NFC to global manifest
- Move to M3 switch for GameSpace 2.0
- Many more misc. changes

# 21-Mar-2025
- Add front-facing camera protection
- Add support for modernized doze double/single tap to wake
- Drop legacy double-tap-to-wake config
- Drop MIUI Camera
- Enable fts_gesture_mode
- Enable Bluetooth HAL to read MAC address from NV
- Enable Touch Gestures
- Handle DT2W feature through Xiaomi Touch
- Implement double/single tap attributes
- Implement support for multiple touch sensor paths
- Remove camera-daemon boost configs
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
