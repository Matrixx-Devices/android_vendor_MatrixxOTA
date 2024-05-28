# 28-May-2024
- Signed build to pass Play Integrity again
- Updated BCR App to latest 1.63

# 21-May-2024
- Fixed Auto Brightness issue
- Haptics improved
- Screen flickering at low brightness is addressed to some extent (very less flickers now)

# 14-May-2024
- Update hyperos cam from 1.0.5.0.UMRMIXM 
- Bring back Thermal Profiles
- Nuked Brightness Slider Curve Implementation (No more higher Brightness at lower slider positions)

# 18-April-2024
- Fixed widevine issue (Back to L1 now)
- Fixed BCR App crashing issue
- Auto Brightness works like one shot Brightness (The moment u unlock phone, brightness adapts to surrounding light) 
- Upstreamed Los kernel to 5.10.209 and is based on latest April tag ASB-2024-04-05
- Update blobs from V816.0.4.0.ULLMIXM
- Fixed twrp getting replaced with source recovery
- Added back OTA support
- Nuked Thermal profiles as they were causing performance drop (Strange but true)

# 11-April-2024
- Switched to Los based trees
- Switched to OSS kernel
- Updated BCR app to latest 1.62
- Ships with Parts Dolby, ViperFX 6.2 for sound
- Includes Per App Refresh rate, Low Power Refresh rate options

# 16-March-2024
- Fixed Heating issues
- Improvements to Moto Dolby
- Added back spatial audio
- Unfortunately widevine is L3 again

# 06-March-2024

- Fixed sms/otp not receiving issue
- Fixed Thermals
- Fixed ott apps crash and now Widevine is back to L1
- Improved Auto Brightness
- Set Brightness slider curve Implementation (Enjoy higher brightness at lower slider positions)
- Upstreamed Evenstar Non ksu kernel to 5.10.211
- Updated BCR to latest 1.61
- Ships with Moto Dolby and Dirac instead of parts Dolby and ViperFX 
- Added overlay for Turbo Power Charging
- Enable Advanced SF Phase Offsets (Improved app open/close animation and reduces janks) 
- Optimized Dex flags (faster boot)
- Removed Force triple frame buffers (Reduces app lags & improves UI performance)
- Nuked Per-app Refresh Rate for now (Buggy after update to Hyperos Blobs)
- Moved Fuse Passthrough prop to product.prop from system.prop as per latest android change
- Fixed Battery Drain due to statsd

# 16-Feb-2024

- Based on HyperOS firmware 
- Added 90Hz support
- Ships with Evenstar Kernel non-ksu variant
- Dropped support for 32 bit apps for now

# 09-Feb-2024

- Fixed Green tint at low brightness
- Added smooth display Toggle
- Fixed some Janks
- Tuned charging control parameters
- Silence some spammy logging (reduces idle cpu usage)
- Tune ambient display burn-in protection
- Updated Silvercore Kernel to latest 5.10.209
- Updated ViperFX app to latest 6.1
- In order to fix crashing ott apps, widevine compromised to L3 for now

# 24-Jan-2024

- Hotfix update for 10.2.1 release of 22.01.24
- Fixed Fingerprint issues that was randomly occuring with few users
- Dropped Smooth display for now
- Switch back to Silvercore Kernel based on 5.10.208 (Though melt was not behind the FP issue)

# 22-Jan-2024

- Fixed issue with night light
- Fixed issue with extra dark
- Fixed an issue where TWRP was getting replaced with matrixx recovery after OTA 
- Improved Adaptive brightness (still brightness varying with screen content in certain scenarios is to be addressed)
- Added back smooth display Toggle
- Switched to Melt kernel and Upstreamed to latest version 2.5.3

# 11-Jan-2024

- Fixed Auto Brightness issue
- Disable frame rate override feature
- Disable backpressure prop (helps fix lags and Janks )
- Updated BCR to latest 1.59
- Updated Silvercore Kernel to latest by Chaitanya

# 27-Dec-2023

- Updated Silvercore Kernel to latest 5.10.204 
- Added some tweaks to improve smoothness of the rom
- Fixed 'No Space' Error with Gapps Flashing (Now use any Nikgapps package of ur choice)

# 20-Dec-2023

- Added Dolby atoms, spatial audio 
- Removed Dirac and retained ViperFX 
- Added dolby vision
- Added Battery Health
- Added support for new Bluetooth Low Energy (BLE) devices
- Updated Perf blobs from Nothing Phone 2
- Switched to latest Silvercore Kernel 5.10.203 
- Updated BCR to latest 1.57
- Updated ViperFX driver to latest 0.6.1

# 10-Dec-2023

- Fixed an issue where default dialer was not being set in Gapps build
- Shipped Google Messaging app instead of AOSP Messaging (Fixes message not received in some cases)
- Uprev ViPER4Android FX to latest release 5.6.2

# 03-Dec-2023

- Fixed issue of incoming call displaying weird numbers for dual sim users (Replaced Google Dialer with aosp dialer app) 
- Replaced Google Messages with aosp messages app
- Switched to aospa kernel from melt kernel

# 01-Dec-2023

- Hotfix build, synced with latest source
- Updated pinner service in tune with pixel_fw merge in source

# 29-Nov-2023

- Added props to improve App closing/opening animations and touch response
- Switched to Melt kernel and updated to latest 2.3.6_1
- Updated Basic Call Recorder app to latest 1.56
- Added lineage Charging Control feature
- Enabled aosp surfaceflinger (Improved smoothness)
- Enabled apk fs-verity (root detection improvement)
- Silenced OpenGLRenderer log spam
- Cleaned up useless log spams
- Reduction of idle drain
- Battery backup improvements
- Improvements to scrolling and smoothness of rom

# 23-Nov-2023

- Shipped & Updated ViperFX to latest version 5.5
- Match vendor security patch with platform security patch
- Adjust status bar paddings

# 17-Nov-2023

- Enjoy strong vibrations as it was before, RIP subtle vibrations
- Uprev BCR to v1.55
- Add Dirac Sound
- Add support for Smart Pixels

# 12-Nov-2023

- Added support for Vanilla Build
- Added cloned apps support for Gmail
- Improved vibrations 
- Updated Silvercore Kernel to v5.10.200
- Miscellaneous fixes and improvements

# 08-Nov-2023

- Added Leica Camera
- Nuked the system apps AudioFX, Auxio and Matlog
- Fixed the issue of vendor security patch level displaying as unknown
- Added Google messaging to fix sms not receiving after device restart
- Ships with Google Dialer instead of Aosp dialer
- Added back Support for 32 bit apps
- Switched to Silver core kernel
