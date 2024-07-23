# 23-JUL-2024:
- Switched to Miui camera (vili hyperos)
- Use AOSP default Codec2/OMX rank
- Build android.hardware.graphics.common-V4-ndk
- Move input surface to CCodec
- Remove media_codecs_google_c2
- 8Gb dalvik heap size config

# 13-JUL-2024:
- Synced with latest source v10.6.1

# 10-Jul-2024
- Kernel Void 5.4.278 Thanks to Omar
- Dropped some apps eleven,mapps,seedvault
- Dropped KernelSU support. Use APatch or Magisk instead
- Update ViPER4Android FX 6.5
- Update BCR 1.65
- Use AOSP default Codec2/OMX ranks
- lmkd: kill heaviest task instead of any eligible task
- Disable VSync for CPU-rendered apps
- Other Fixes under the hood.

# 14-Jun-2024
- Synced to latest Matrixx source
- Other Fixes under the hood.

# 04-Jun-2024
- Fix Safetynet again

# 03-Jun-2024
- Sync with latest source to fix few source side errors
- Dropped livedisplay leftovers
- Downgraded netmgrd to LAHAINA-19300 (should fix VoWifi)
- Updated CarrierConfig from Nothing phone (2) and LA.QSSI.14.0.r1-12000-qssi.0
- Disabled unsupported perf resources
- Improved surfaceflinger offsets
- Kernel Initial Void release Thanks to Omar

# 26-MAY-2024
- Updated vili specific blobs to V816.0.2.0.UKDMIXM (credits to TheStrechh)
- Updated included firmware to V816.0.2.0.UKDMIXM
- Updated common blobs from Haydn V816.0.2.0.UKKMIXM
- Dropped QTI thermal HAL service
- Dropped livedisplay leftovers and switched to simple RGB adjustments (can be found in display color settings)
- Updated KSU to the latest version
- Kernel Rebased to latest LineageOS kernel
- Kernel Upstreamed to 5.4.276
- Sign build for safetynet

# 17-MAY-2024
- Update Basic call recorder
- Update Ksu to the latest version
- Add prebuilt protobuf full 3.9.1
- Other Fixes under the hood

# 13-MAY-2024
- Better RAM management
- dex2oat64 on sm8350
- Enable support for IEEE80211AX
- Disable Skia tracing by default
- Other Fixes under the hood

# 28-APR-2024
- VILI Vendor blobs updated to VILI EEA V816.0.1.0.UKDEUXM
- COMMON Vendor blobs updated to Haydn V816.0.1.0.UKKCNXM (HyperOS)
- Update Ksu to the latest version
- Adjust Color Modes from stock
- Other Fixes under the hood

# 17-APR-2024
- Synced to latest Matrixx source
- Other minor Fixes

# 13-APR-2024
- Hotfix build
- Fixed OTT apps like Netflix issue with Widevine L1 with LOS kernel
- Synced to latest Matrixx source
- Other Fixes under the hood.

# 09-APR-2024
- Initial QPR2 Build.
- Switch to Dolby Manager.
- Update Ksu to the latest version.
- Enable config avoidGfxAccel.
- Update adreno blobs from AOSPA/CLO.
- Other Fixes under the hood.

# Changelog 16 mar 2024:
- Initial A14 update.
