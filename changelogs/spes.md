# Changelog 4 October 2024:
- Fixed media codec bug 
- Disable dynamic refreshrate
- Tweak lmk props
- Build missing Display HAL blobs
- Drop livedisplay
- Specify vendor.usb.device
- Disable camera perflock
- Change default dexpreopt compiler filter to speed-profile
- Fix mialogocontrol patch when extract blobs.
- Cleanup fpc fingerprint wakeup labels.
- Address maxim ic suspend policies.
- Correct maximum microphone count
- Set correct channel mask for earpiece
- Remove wait_for_keymaster and all references
- Update hal_power_default to have sys_admin capability
- Allow surfaceflinger to access firmware
- Remove conditional for WfdCommon
- Many more Misc Improvement

# Changelog 15 May 2024:
- DT rebased over from crdroid
- Updated blobs from SPESNGlobal_V14.0.6.0.TGKMIXM_3bf72b1c44_13.0
- Update HALs audio/display/media from LA.UM.9.15.2.r1-09300-KAMO..RTA.QSSI14.0
- WiFi calling now working 
- Fixed sys.fp.miui.token spam
- Goodix FP now working 
- Fixed PowerHAL nodes
- Fixed imsrcsservice neverallow
- Updated and add more wakeup nodes
- Kernel version updated to 4.19.312
- Address content_capture_service denial
- Silence OpenGLRenderer log spam
- Switch to sw enc/dec for vp9 codec
- Disable OMX.qcom.video.encoder.avc
- Many more Misc Improvement

# Changelog 18 Feb 2024:
- Disabled alpha compositing in WM
- Address vendor.qti.data.factory Selinux denials
- Register more libs to cached max freq
- Remove obsoleted INI called gFixedRate
- Speed up animations

# Changelog 24 Jan 2024:
- Adjusted lux stability time needed for updating auto-brightness values
- Cleanup brightness lcd value
- Used QCOM implementation for audio effects
- Fixed low mic volume
- Start bootanimation on post-fs
  
# Changelog 15 Jan 2024:
- Moved to common Xiaomi fingerprint HIDL
- Fixed DT2W & AOD Issues
- Moved to Bengal HALs
- Updated kernel version to 4.19.304

# Changelog 27 Dec 2023:
- Initial official Release
- Fixed FP issues for goodixFP users
- Set correct audio channel mask
- Updated kernel version to 4.19.303
