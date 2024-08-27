# 27-August-2024
NOTE: Both panel are supported

* No changes

# 24-August-2024
NOTE: Both panel are supported

* Updated blobs to V816.0.6.0.UMSMIXM
* Shipped with firmware ( OS1.0.6.0.UMSMIXM )
* overlay: Speed up auto-brightness ramp up
* overlay: Disable alpha compositing in WM
* overlay: Globally enable LTE+ icon
* Switch to QTI Memtrack AIDL HAL
* Build missing libraries for Dolby Atmos
* audio: Disable ULL mode

# 18-August-2024

- Switched to Perf kernel 
- Updated camera & blobs to V816.0.8.0.UMSCNXM
- Updated yupik-post-boot script for memory optimization
- Updated kernelSU to v0.9.5 ( THE END )

# 12-August-2024
- Switched to TURBO kernel ( Both panel are supported now )
- Drop vm-bootsys from fstab ( This reduces the boot time )
- Build xiaomi-telephony-stub ( Unpatch & update ims libs to V816.0.7.0.UMSCNXM )
- Import missing camera blobs
- overlay: Disable pocket mode lock
- Enable force LTE_CA
- Re-implemented dolby
- Switched to AOSP dialer

# 28-July-2024
- Note: Dirty flash is fine over last build
- Note: This build is only compatible with Gtx panel
- Switched to Google dialer & Google Messages

# 23-July-2024
- Note: Dirty flash is fine over last build
- Shipped with OS1.0.7.0.UMSCNXM firmware
- updated blobs to V816.0.7.0.UMSCNXM
- props: Disable VSync for CPU-rendered apps
- props: Disable sf EGL image tracking
- props: Enable lmkd
- Introduce custom LiveDisplay HAL
- Add Notch Bar Killer overlay
- Codecs: Remove software omx codec references
- Codecs: Use AOSP default Codec2/OMX ranks
- Codecs: Move input surface to CCodec	
- Codecs: Remove media_codecs_google_c2*





# 14-July-2024
- No changes

# 10-July-2024
- Shipped with OS1.0.5.0.UMSMIXM firmware
- Switched to stock HyperOS camera V5.1.001110.5 ( This uses Google Photos as the default gallery. You need to install Google Photos to open pictures from the camera.)
- Updated blobs to OS1.0.5.0.UMSMIXM
- Updated radio properties from haydn V816.0.1.0.UKKCNXM
- Updated IMS blobs to haydn V816.0.1.0.UKKCNXM
- Fixed low mic issue on  whatsapp, telegram etc 
- overlay: Added P3 and sRGB color mode
- Switched to AOSP dialer and message again
- Build missing libraries for 14 QPR3

# 16-Jun-2024
- Updated blobs to OS1.0.4.0.UMSMIXM
- Shipped with OS1.0.4.0.UMSMIXM firmware 
- Updated adreno blobs to v744
- Build Aptx and ldacBT libs from source
- Switched to Google dialer

# 31-May-2024
- fixed systemui high cpu usage on idle
- kernel: fixed heating issue
- kernel: updated kernelSU to v0.9.4
- kernel: Added 90hz support

# 27-May-2024
- No changes

# 18-May-2024
- No changes

# 16-May-2024
- Switched to leica camera again.
- Introduced Xiaomi parts
- Dropped oneplus dolby support & added Dolby Atmos as part
- Disable alpha compositing in WM
- Added SpatialAudio support
- Imported powerhint.json from coral and adapted it for yupik

# 14-May-2024

NOTE: clean flash is required.
- updated KernelSU ( v0.9.3 )
- Dropped Leica camera and imported hyperOS stock miuicamera
- Re-implemented oneplus dolby 
- Optimize statusbar paddings
- Added HBM support

# 29-April-2024
- Import LDAC prebuilt from stock

# 17-April-2024
- Fixed ScreenCast issue.

# 10-April-2024
- Shipped with hyperos firmware ( OS1.0.3.0.UMSMIXM ) 
- Update blobs from OS1.0.2.0.UMSMIXM
- Fixed  lag issue in screen recording at 120hz
- Fixed call on voNR 
- Updated kernelSU ( v0.9.2 )
- props: Disable display refresh rate override
- props: Set frame rate multiple threshold to 60
- props: Enable config_avoidGfxAccel
- props: Reduce refresh rate timers
- props: Extend audio offload buffer size to 256kb

# 17-March-2024

- Synced with latest source
- Fixed audio distortion 
- Boost audio output
- Switch to SkiaGL Threaded (Fixed LMC/GCAM crash issue)
- Fixed systemui crashing
- Updated KernelSU
- Many miscellaneous changes

# Changelog 11 Feb 2024:
- Initial A14 update.
