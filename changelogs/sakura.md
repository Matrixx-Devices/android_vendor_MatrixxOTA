# Changelog 24 Aug 2024:
- Synced with latest v10.7.2 source
- ro_overlays: Move CarrierConfig to RRO
- Specify caymanslm source at the top
- Remove media_codecs_google_c2*
- Droped libts libs
- Brought back bcr and viper4android
- Move input surface to CCodec
- Import prebuilt wpa_supplicant
- Added performance point tag for msm8953
- Redisgned QS brightness progress bar
- And some optimisation here and there
- Disabled Wallpaper zoom animation once and for all

# Changelog 14 July 2024:
- Synced with latest v10.6.1 source
- Moved to Fbev1
- Remove software omx codec references
- Use AOSP default Codec2/OMX ranks
- Set higher priority to c2 than OMX
- finetune performance xml
- Finetune mediacodec performance
- mark the target with slow cpu
- Drop Xiaomiparts once and for all
- QCamera2: Fix sensor to active array ROI conversion
- HAL3 Fix for memleak if for snapshot stream
- Fix sharpness issue in snapshot
- Fix snprintf string truncation error
- Further more changes
- Rom signed with sign keys

# Changelog 17 March 2024:
- Synced with latest v10.3.1 source
- Set zram size to 50% of system ram
- Linked vendor sp to platform
- Added wifi support for two bands 2.4Ghz ang 5Ghz
- Disabled Wallpaper zoom animation
- Added props to bluetooth to fix auto turnoff

# Changelog 14 Feb 2024:
- Synced with latest v10.3.0 source
- Added Bcr as prebuild
- Added OTA support for Vanilla version
- Fixed random reboot while hotspot turned on
- Renamed perf as kernel line
- cpufreq_schedutil: remove tracing
- init/main.c: add sync point between each level
- Misc changes and further more improvement hereandthere

# Changelog 18 Jan 2024:
- Synced with latest v10.2.0 source
- Fixed Viper4FX driver issue and readded
- Imported SmartPixel in dt
- Added OTA support for Gapps version
- Fixed incoming calls not popup
- Added some vendor.prop

# Changelog 31 Dec 2023:
- Synced with latest v10.1.2 source
- Fixed Fingerprint for goodix 
- Removed Viper4FX for now
- Improved system animation
- Fixed Dialer crashing
- Many more underhood changes

# Changelog 22 Dec 2023:
-Initial official release.
