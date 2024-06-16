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
