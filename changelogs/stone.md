# Changelog 20 May 2026
- May Security Patch
- Fix playstore app installation
- Introduce per-app-upscale (Huge thanks to kami for impl)
- Kang graphic blobs from xperia 10 V
- Kang display blobs from fogos_g
- Cleanup props and sepolicy
- Tweak powerhint for performance
- Define missing zram swappiness and algo
- Merge latest kernel changes from LOS
- Use BBR and FQ
- Optimized for balanced performance and efficiency

# Changelog 10 April 2026
- Initial Android 16 QPR2 release
- April Security Patch
- Clean Flash Required
- Update blobs from OS2.0.9.0.UMQEUXM
- Fully rebased kernel and device tree
- Optimized for balanced performance and efficiency
- Synced with latest tree and source changes

# Changelog 27 November 2025
- Initial Android 16 release
- Clean flash needed
- November Security Patch
- Update blobs from OS2.0.5.0.UMQMIXM
- Revert back to recovery in boot
- Switch to minimal kernel
- Fix cpu governor being performance
- Disable unnecessary logging
- Various other changes
- Sync with latest sources

# Changelog 2 October 2025
- September Security Patch
- Switch to Global Blobs and update from OS2.0.4.0.UMQMIXM
- Fix SMS not getting sent in some cases unless you reboot
- Bring back Dirac from old tree (thanks kami for original implementation)
- Reduce boost duration to 1.5s
- Revert back to in tree task profiles
- Extend task profiles to add dex2oat and input latency optimizations
- Update Dolby to latest version and also fix rare dolby crash
- Update DFM on IChargingControl and IFastCharge
- Cleanup postboot script
- Sync with latest sources

# Changelog 26 August 2025
- August Security Patch
- Update blobs from OS2.0.4.0.UMQEUXM
- Enable UFFD GC
- Add Datura Firewall
- Properly define CPU architecture
- Increase vibration duration from 20ms to 25ms
- Drop QCOM WFD and switch to AOSP WFD to fix wifi display (cast)
- Replace writepid with task_profiles command for cgroup migration
- Define missing hals in compatibility manifest
- Remove libqti-perfd-client.so from public.libraries.txt
- Kernel: Enable CONFIG_WIREGUARD
- Kernel: Enable CONFIG_USERFAULTFD
- Kernel: Move 'struct sched_param' out of uapi, to work around glibc/musl breakage
- Sync with latest sources

# Changelog 14 July 2025:
- Rebase on new  kami tree
- Actually add Viper4Android
- Switch to lineage libperfmgr
- Sync with latest sources
- Read source changes for bug fixes

# Changelog 24 June 2025:
- June Security Patch
- Add Sony Dolby Atmos and Viper4Android
- Limit AOD to 60hz
- Switch to common AIDL IR Service
- Switch to newer darkmoon base thanks to kami(which also fixed ir and custom recovery)
- Update Blobs from OS2.0.3.0.UMQMIXM
- Revert back to SkiaGL to fix video playback issue in some apps
- Recuce log spams
- Optimize native executables for Cortex-A76 CPU
- Improve sound quality
- Sync with latest sources

# Changelog 1 June 2025:
- CLEAN FLASH NEEDED
- Initial QPR2 build
- May Security Patch
- Switch to newer kami/baunilla base
- Switch to source built oss kernel (Does NOT support custom recovery and must use provided boot.img)
- Update to HOS2 blobs
- Added updated parts thanks to kami
- Dropped Dolby

# Changelog 13 February 2025:
- Initial Official Build
