====================
     11-30-2025
====================

   * frameworks/base
23dc23ad064c FixUp! UDFPS animation
bde7ec5b6468 Update UdfpsAnimation constructor to accept KeyguardStateController
9b72c2dcb2ba biometrics: Fix udfps races
822aa61b379c Revert "Revert "Biometrics: Hook up support for halHandlesDisplayTouches prop""

   * packages/apps/Settings
ee3995a959f OnePlus13: Device Settings

====================
     11-29-2025
====================

   * hardware/oplus
465f765 Add toggle for ltpo features

====================
     11-28-2025
====================

====================
     11-27-2025
====================

   * device/oneplus/dodge
88725d6 dodge:Initial Project Matrixx Bring up

   * device/oneplus/sm8750-common
e2c8b39 sm8750-common: Add Device Maintainer

   * hardware/oplus
302bcaa sepolicy: qti: Allow system server to detect oem charging
710895a sepolicy: adress fingerprint denials
acb8ef3 sepolicy: qti: Allow system_server to r/w oplus_chg nodes
e0f4234 sepolicy: qti: Allow binder calls for sensor hal to system_server
b641982 sepolicy: Fix bluetooth denial on user builds
e25e756 sepolicy: Fix hal_bootctl_default denial
c108b37 sepolicy: Address DeviceSettings and fast charging denials
4acd614 hardware: hidl: inscreen: Set thread to high CFS priority
e35d5b9 sepolicy: Address various denials
d567547 sepolicy: Label hal_charger service
c00f50e overlay: qssi: Update QSSI RROs from CPH2573_11_A.76
534c885 sepolicy: Label oplus bluetooth prop
5528e0f sepolicy: Address nfc denial
afaf2b2 sepolicy: Allow vendor_hal_perf_default to access surfaceflinger
5809ba7 oplus-fwk: Add OsenseResClient and OplusUIFirstManager stub implementation
1a41a02 [TEMP] sensors: aidl: Glorified one-shotting
0547c45 aidl: sensors: Return early if nothing is displayed over the light sensor
65b9256 aidl: sensors: Import AlsCorrection from sm8150-common
ca8e18a Import ALS capture service from sm8150-common
9549a03 overlay/sensors: Configure Doze brightness sensor
225a950 overlay: qssi: Define quick_pickup sensor string
e743859 overlay: qssi: Enable config_dozePulsePickup
aef9acd sepolicy: qti: Label sensors AIDL multihal
881c393 aidl: sensors: Standardize qti.sensor.amd to glance sensor
8b35c27 aidl: sensors: Invert value for pickup gesture event
8324141 aidl: sensors: Change standard tilt_detector to pickup_gesture
d9ba057 aidl: sensors: Avoid target name conflicts
cb02520 aidl: sensors: Change default applicable license to Android-Apache-2.0
91ea7a5 aidl: sensors: Import 2.X sensors hal proxy
35150a7 aidl: sensors: Revert^2 "SensorHAL: add moisture detection"
f0768b8 aidl: sensors: Import aidl sensors MultiHal
0e325a7 aidl: qti_vibrator: effect: import richtap effects
be5174e oplus-fwk: Add missing classes for oplus camera
06d2e14 oplus-fwk: Update for compatibility with android-15 IMS stack
654fd15 aidl: vibrator: Minimize code for ledVibratorDevice
9a1f70d doze: Use new method to listen for preference changes

   * lineage/hudson
b3b5d56 sake: Promote to 23.0

   * lineage/wiki
42682e47 wiki: Allow A16 FW for dodge and erhai
ea98db60 wiki: Promote sake to 23.0

   * vendor/MatrixxOTA
3948cd9 Matrixx: Update new IDs and push OTA [BOT]
8912179 Merge pull request #432 from mayuresh2543/16.0
5dbfe3e stone: initial 12.1.0 release

====================
     11-26-2025
====================

   * build/soong
2034bed24 config: allow keytool to path tool list

   * device/oneplus/dodge
4915b7b dodge: overlay: Enable multiple vibration intensity levels
341bb67 dodge: Set market name for device
27f8f78 dodge: overlay: Adjust brightness debounce values
912f038 dodge: overlay: Move in alert slider configs
2d7602d dodge: Set proper screen density
f2006b2 dodge: Enable UDFPS animations
f2eb345 dodge: overlay: Update Brightness configs
cb8f9f0 dodge: Increase start statusbar padding
2a53b39 dodge: Switch to FIFO vibration effects

   * device/oneplus/sm8750-common
8f54e63 Revert "sm8750-common: define media settings to sun variant"
ab7b400 sm8750-common: Remove obsolete SurfaceFlinger properties
ea49ef1 sm8750-common: define media settings to sun variant
0cde1e0 Adapt  for Lineage SDK
4c03edd Refresh Rate Change-Id: Ifc1454eee3df760675432c41b03342b1b413bc1d
22f2304 Merge Utils into FileUtils
72aa7c7 device-settings: GameBar rewrite with static layouts
01f9af9 DeviceSettings: refactor and feature additions
2a371d4 Fix Up! add missing preference
53505eb DeviceSettings: add PulseOne PWM
f4ed445 Drop Lineage Health
c6d4bca Init: set permissions for OnePulse PWM
596a2e3 DeviceSettings: lunch it from Settings
7a5c2c9 DeviceSettings: rework bypass charging
8e21d18 fix up
dd58d58 Device Settings: Oneplus13
567d859 temp2
f7218ff DeviceSettings: disable all features except alert sliker
e1c69b9 sm8750: Device Settings move alert slider toast to left side
2e4541e sm8750-common: Ship ConsumerIR App
f29337d sm8750-common: DeviceSettings: Switch to material expressive design layout
09421fa sm8750-common: Move required alert slider configs to SystemUI
edf50db sm8750-common: overlay: Set fixed refresh rate on keyguard
cc32b78 sm8750-common: Set marketname for proper device info
aeceb5b sm8750-common: Allow gcam/snapcam to skip HFR checks
551b1f8 sm8750-common: Allow camera to skip high frame rate checks
0036193 sm8750-common: overlay: Add system ui restart option
10fa181 sm8750-common: Disable frame rate override feature
17962e2 sm8750-common: DeviceSettings: Migrate to Android.bp
a8a26a1 sm8750-common: DeviceSettings: Migrate to SwitchPreferenceCompat
72381f0 sm8750-common: DeviceSettings: Fix up for A14 QPR2
b4b83bf sm8750-common: DeviceSettings: Define used libraries
e2e3113 sm8750-common: DeviceSettings: Add game mode and edge touch switches
a7f3d77 sm8750-common: DeviceSettings: Add russian translations
8499c9d sm8750-common: DeviceSettings: Add node for USB fast charge
ffd393d sm8750-common: Add DeviceSettings
7954cf2 sm8750-common: Enable blur effect
03b826d sm8750-common: overlay: Update pinner list
798d811 sm8750-common: overlay: Turn on screen on unplug
631ba0e sm8750-common: overlay: Add temp divider value for cpu info overlay
376a736 sm8750-common: overlay: Add fps info path
659606d sm8750-common: overlay: Switch to crdroid doze
d5722bd sm8750-common: Nuke OnePlus doze
46edb5b sm8750-common: overlay: Decouple auto-suspend and interactive state from display
4e784b9 sm8750-common: overlay: Configure VOOC charging display on lockscreen
53ff59c sm8750-common: overlay: Fix lockscreen charging info
7fcc6c2 sm8750-common: overlay: Use appropriate charging thresholds
54a298f sm8750-common: Switch to oplus sensors AIDL
6b59703 sm8750-common: overlay: Enable VOOC charging support

   * kernel/oneplus/sm8750
7bfd38e99ba3 PM / freezer: Reduce freeze timeout to 1 second for Android
48356601dd30 fs: Dont allow paths with lineage to be listed
14af71b913ea mbcache: Speed up cache entry creation
fa0ee3508e11 arm64/mm: Optimize loop to reduce redundant operations of contpte_ptep_get
b8cd1a9302c9 ANDROID: gki_defconfig: Enable Clang ThinLTO support
b2cfdc10dc76 ANDROID: gki_defconfig: Enable AUTOFDO_CLANG for AutoFDO optimizations
40d3318027bb lib/lz4: Remove redundant MIN/MAX macros to fix compilation error
a8c3e4b453b1 lib: update lz4 to v1.10.0
3940db0227f6 lib/decompress_unlz4: Add NEON-optimized LZ4 decompression for ARM64
5b56bcffe7d9 arm64: debug: disable self-hosted debug by default
2f44e74d65e0 lib: Disable debug_locks
57bca1d19a64 Makefile: Enable -mcpu=oryon-1
8e629abb2981 f2fs: Demote GC thread to idle scheduler class
8aefed7dee58 f2fs: set ioprio of GC kthread to idle
3bea4ae01af5 f2fs/gc: Reduce GC thread urgent sleep time to 50ms
10453eb55fbd f2fs: Use copy_page for full page copy
b72a88275bd4 f2fs: reduce timeout for uncongestion
e597037bc656 f2fs: Enable ATGC and GC_MERGE by default
2f4067ad08f2 lz4: Use ARM64 NEON-optimized decompression where available
7d5017bc68a8 kernelsu: replace renameat hook with fsnotify
7a9c2cabfe1e kernelsu: Fix kernel panics caused by thread info flag corruption
f7142b44384a kernelsu: Use SUS_SU by default
4a0e4563f17f kernelsu: Fix SUS_SU feature
434d242f25c9 devpts: KernelSU: Fix: Failed to execute pm in terminal
4141ab3ac4fe drivers: Add missing KernelSU hooks
33cb02d40860 kernelsu: implement v2_signature size/hash override from userspace through kernel module parameter
58196799eee8 kernelsu: Allow compatible manager apks
9b9ce4594e6d kernelsu: Remove duplicate function to fix compilation
2fc7c7313160 kernelsu: Enable susfs for ksu
223b8150eb8e kernelsu: Add susfs in gki android15-6.6
d61386224406 drivers: Set proper version for KernelSU-Next
667aeb498d6d drivers: Import KernelSU Next v1.1.1
33a133ffba71 drivers: Add KSU config path
919b77a5c394 thermal: qcom: tsens: Fix function prototype mismatch

   * kernel/oneplus/sm8750-modules
b096249139 display: Enforce ulps suspend
1d13e7a7a3 display: Enforce ulps by default

   * lineage/hudson
8496bac Time is money

   * lineage/wiki
e880e36e wiki: Update alioth maintainer list
e7987ee6 wiki: devices: Add LG V60 ThinQ (timelm)

   * vendor/MatrixxOTA
a9998d8 Matrixx: Update new IDs and push OTA [BOT]
0002b22 marble: initial 12.1.0 release
96f6254 zorn: Fix vanilla path
ffcb18d Matrixx: Update new IDs and push OTA [BOT]
36222f2 Merge pull request #431 from Lowxorx/16.0
0228062 zorn: Matrixx 12.1.0 release

   * vendor/oneplus/sm8750-common
d5a5859 add ConsumerIRApp

====================
     11-25-2025
====================

   * device/oneplus/sm8750-common
556cb91 sm8750-common: Update from OOS 11.F.80
3c35ec8 sm8750-common: Remove `oplus_bsp_tp_ft3419u` from modules list
c8af67e sm8750-common: Enable the start of the Vendor VM HAL
6f69079 sm8750-common: Update from OOS 11.F.74

   * hardware/oplus
824602c oplus-fwk: Stub NetworklessManager

   * hardware/qcom-caf/sm8450/audio/pal
0ab95e9be Revert "ResourceManager: fix activeStreams check"

   * lineage/hudson
4eb5ef0 Regenerate device dependency mappings

   * lineage/mirror
2074512 Updated to 25-Nov-2025 11:01 UTC

   * vendor/MatrixxOTA
989252f Matrixx: Update new IDs and push OTA [BOT]
e0cd611 Bot: Typo
47c9a37 Alioth: Matrixx 12.1.0 release

   * vendor/addons
b8c66592 update BCR to latest 1.86

   * vendor/lineage
91f17e0f Revert "vendor: Build Custom Themed iconpack for pixel launcher"
c1e7a3dd Move APNs data to vendor/apn
ca253987 crdroid: Update blur support
ecde2cf4 Matrixx A16 Protium release
e64fad4a config: add PERF_ANIM_OVERRIDE flag
0b09e17f envsetup: skip abi checks for now
ddd8d264 config: Build LMO systemui clock plugin
fa0dce91 overlay: Drop now playing customization
3921c4a7 Bump Security patch string to 2025-11-01
0f6e95ed vendor: Build Custom Themed iconpack for pixel launcher
a7d71eff Build QuickSwitch conditionally
4c112305 vendor: Build launcher for QuickSwitch
f94dfdeb vendor: Use and support Pixel charger animation
c0d7a2f4 drop crdroid offline charging animation * inorder to bring pixel charging manimation
929bf122 createjson: update createjson.sh
0e01b6a0 Build Avatar picker required for vanilla
9d795a55 vendor: also append time in version
1a17b9f6 vendor: Adapt json for matrixx
26ab52a0 vendor: Drop Settings Build status based on device status Will bring Back once device and maintainers list are sorted
186645ee vendor: bringin codenames
18f62a9a config: Remove useless addon.d file
0a2c0ff8 Config: Don't build updater as of now * We haven't set it up yet; it will be done after the QPR2 release.
396ea9c7 vendor: drop maintainers prop as we are moving to overlay based
5dac9275 vendor: Treat SystemUI clocks as privileged
72ff8624 vendor: Fix app icon font on PixelLauncher
928e7cb5 vendor: Enable R8 code shrinking for system_server and SystemUI
fd6f2032 vendor: Import BT Slice intent resources from SettingsGoogle
bef0d779 vendor: Add google dialer call recording feature
820b7417 tasks: add fastboot target
407e667d vendor: Conditionally build Gapps
ea1f9cd8 vendor: Initial Matrixx conversion

====================
     11-24-2025
====================

   * lineage/wiki
4b134c26 wiki: Update gauguin maintainer list

   * packages/apps/Settings
29ed5aac195 Use A15 search as deafult [Temp]
90b42150461 Settings: Drop duplicate AccessibilitySettings Preference and move about phone preference
14e2a24cf4f Settings: Fix Storage preference icon in expressive style
6af78e3ecdb Settings: Add custom preference for google account settings
34280ca2835 Settings: Fix Backup and restore preference for Dashboard

   * vendor/MatrixxOTA
4cf2d11 OTA: Typo

====================
     11-23-2025
====================

   * device/qcom/sepolicy-legacy-um
b28a32c4 legacy: Grant sys_module cap for correct wifi/wigig domains
a6b7ae68 legacy: Disallow system_server from loading kernel modules

   * device/qcom/sepolicy_vndr/legacy-um
ac205a3f1 legacy: Grant sys_module cap for correct wifi/wigig domains
f06f20f3a legacy: Disallow system_server from loading kernel modules

   * hardware/oplus
32308a2 KeyHandler: Modernize ButtonSettings
7aa2810 KeyHandler: Switch to SwitchPreferenceCompat
c936325 doze: Convert to SwitchPreferenceCompat

   * lineage/wiki
444f8d07 devices: dre: Promote to 23.0

   * vendor/MatrixxOTA
9b61709 Matrixx: Update new IDs and push OTA [BOT]
275767f Merge pull request #429 from EvilAnsh/16.0
9f86e02 salaa: Initial v12.1.0 release
b321d27 Matrixx: Update new IDs and push OTA [BOT]
e2a2930 Merge pull request #428 from NoCache-69/16.0
96eec30 oscaro: Initial Android16 release (23/11/25)

====================
     11-22-2025
====================

====================
     11-21-2025
====================

   * android
90b25b1  Track modules Connectivity and compat

   * device/oneplus/dodge
a3c98b8 dodge: Update from OOS 11.F.80
a702039 dodge: Update from OOS 11.F.74

   * device/oneplus/sm8750-common
1b8b99d sm8750-common: Move CNE and DPM to phone blobs list

   * device/qcom/sepolicy_vndr/sm8450
3cf5bcbc1 BOARD_SYSTEM_EXT_PREBUILT_DIR is obsolete. Use BOARD_SYSTEM_EXT_SEPOLICY_PREBUILT_DIRS

   * device/qcom/sepolicy_vndr/sm8650
2c8325953 BOARD_SYSTEM_EXT_PREBUILT_DIR is obsolete. Use BOARD_SYSTEM_EXT_SEPOLICY_PREBUILT_DIRS

   * device/qcom/sepolicy_vndr/sm8750
dd8ebd72c BOARD_SYSTEM_EXT_PREBUILT_DIR is obsolete. Use BOARD_SYSTEM_EXT_SEPOLICY_PREBUILT_DIRS

   * packages/apps/LMOFreeform
738b49f New translations (#15)

   * vendor/MatrixxOTA
25b1793 Matrixx: Update new IDs and push OTA [BOT]
31c56ac Merge pull request #427 from kibria5/16.0
fa5b979 peridot: Initial v12.1.0 release

   * vendor/oneplus/dodge
be23fe9 dodge: Update from OOS 11.F.80
9858fea dodge: Update from OOS 11.F.74

   * vendor/oneplus/sm8750-common
93748fa sm8750-common: Update from OOS 11.F.80
c9a6385 sm8750-common: Update from OOS 11.F.74
ac979e7 sm8750-common: Move CNE and DPM to phone blobs list

