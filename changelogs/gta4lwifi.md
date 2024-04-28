---
title: Samsung Galaxy Tab A7 (gta4lwifi)
description: Brought to you by Aryan
---

<b>Changelog 29 APR 2024:</b>
- Switch to VULKAN UI renderer
- Stop pinning camera app in memory
- Disable debug.sf.enable_hwc_vds
- Enable backpressure propagation in SF
- Remove redunant vendor props
- Reverted gta4l assert
- Switch to Wifi aidl
- Switch to android.hardware.usb@1.3-service.dual_role_usb
- Updated libqti-perfd-client
- Imported powerhint.json from sunfish
- Imported powerhint.xml from Oneplus Kona
- Adapt powerhint for sm8250
- Set 1 second timeout for interaction boosts
- Modify kgsl idle timer to 58ms
- Fix cpu_dma_latency value
- Decrease launch boost to 3sec
- [PATCH] Remove hints for Adaptive Battery CPU
- Drop PM QoS boosting
- [PATCH] Remove sm8250-AC frequency
- Increase sustained performance and interaction freqs
- Remove Schedtune boost
- Increase little cluster interaction boost
- Disable kpti
- Update Wifi driver flags
- Allow vendor_hal_drm_widevine to set vendor.drm.keystatus prop
- Tweak some default configs
- Do not balance msm_drm and kgsl_3d0 IRQs
- Extend audio offload buffer size to 256kb
- Build libcodec2_hidl|vndk from source
- RIL edits for battery life.
- Do not dexpreopt prebuilt packages
- Enable full LLVM compilation on kernel
- Prefer 'cache' backing storage
- Tune zram performance (Switch to lz4 compression)
- Merged few latest clo kernel tags
- Upstream kernel v4.19.312
- KernelSU updated
- Many more underhood changes

<b>Changelog 21 MAR 2024:</b>
- Optimise DEX flags
- Optimise package manager dexopt properties
- Enable PRODUCT_FS_COMPRESION
- Switched back to legacy aidl DRM
- Add props to improve battery life
- Update zram configuration
- Added battery health stats
- overlay: disable useless gms components
- Upstream kernel v4.19.310
- Compiled kernel with proton clang

<b>Changelog 24 FEB 2024:</b>
- Optimised ART
- Added speed preopt for launcher/SettingsGoogle/SystemUIGoogle
- Compile system services using speed-profile
- Always use preopt extracted apks
- dex2oat stripp off some debug packages
- Fixed DRM
- Allow Updatable Apex
- Update notifications icon overlay for A14 
- Speed up animations
- Import SF props for smoothness
- Switch to SkiaGL and SkiaGL Threaded
- Overlay for ui tweaked smoothness
- Enable subtle tick vibration when revealing shelf
- Enable zygote critical window 
- init rm cache on early boot
- Disable skia tracing by default
- Compile HWUI for performance
- Use HintManager for HWUI
- Enable suspend to RAM
- Force device to treat 170M as sRGB in SF
- Prop to disable SF client composition cache
- Updated pinner files for SystemUIGoogle
- Don' pin launcher app in memory
- Disable Async MTE on system server
- Disable Vsync for CPU rendered Apps
- Some more misc changes 

----
Flashing instructions : [Get From Here](gta4lwifi_inst.md)

----
Download Link : [Official Download Link for gta4lwifi](https://sourceforge.net/projects/projectmatrixx/files/Android-14/gta4lwifi/)

----
