# 23-June-2025
- disable gl backpressure
- disable adsprpcd
- set camera override format from reserved via soong config
- Fix product mod device
- Fix VoWifi
- Fix 64mp cn cam issues
- Switched to OSS Dolby interface
- enabled UFFD GC
- Update CarrierConfig from haydn v816.0.12.0 UKKCNXM
- Disable global mode and CDMA choices
- Configure WIFI TCP buffers
- enable VoNR for JIO5G
- Switch to common AIDL IR service
- Allow VoLTE and VoWiFi by default
- import missing wpa_supplicant configs from stock
- allow rild read default_prop
- Fixed many sepolicy denials
- Apply dex2oat optimizations
- Update blobs from haydn v812.0.18.0.UKKEUXM
- Update HyperOS gallery and editor
- Update Ksun to v1.0.6
- Added support for Susfs
- Added Vanila support

# 19-May-2025
- Move Lineage Health HAL to select()
- Move libcameraservice extension lib to select()
- Decrease debug.hwui.target_cpu_time_percent
- Disable_gl_backpressure
- Disable adsprpcd
- Fix 64mp Camera issue
- Many more improvements kernel side

# 03-May-2025
- drop dt2w hint from powerhint
- drop Game mode tuning from powerhint
- update blobs from V816.0.12.0.UKKCNXM
- Optimize native executables for Cortex-A76 CPU
- Switch to dot product CPU variant
- Move citsensorservice to background cpuset
- Enable usage of dex2oat64
- drop input boost freq configuration
- kang display stack from LA.UM.9.14.r1-21000-LAHAINA.QSSI13.0
- update adreno drivers from AOSPA
- Enable debug.sf.hw
- update VENDOR_SECURITY_PATCH lvl
- Disable multiple kswapd threads
- Disable continuous transaction tracing on all build types
- Don't pin camera app in memory
- Allow all filesystems for USB-OTG
- Declare 6ghz wifi support
- Unset schedutil ratelimits
- Move Lineage PowerShare HAL to select()
- Move libperfmgr mode extension lib to select()

# 21-Mar-2025
- Move audio-app cpuset to 1-2
- Disable the property debug.sf.enable_gl_backpressure
- Disable WLAN Firmware loggings
- Disable SF composition prediction model
- Force device to treat 170M as sRGB in SF
- Configure schedutil up/down rate limit
- kernel: Merged latest CAF tags && upgrade to linux 5.4.289
- kernel: Implement SLMK && MLGRU
- Many more improvements

# 14-Mar-2025
- Initial Matrixx A15 release
