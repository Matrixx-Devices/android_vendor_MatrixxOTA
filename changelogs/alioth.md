# 03-Aug-2024
- Upstreamed to latest 10.6.2 Matrixx source
- Upstreamed n0kernel to latest kernel source
- Nuke Battery Friendly Pocket mode
- Add missing IMS lib
- Build liblz4
- Fix Camera failed to start camera preview
- Switch to Leica 4.9

# 14-June-2024
- Upstreamed to latest 10.5.2 Matrixx source
- Upstreamed n0kernel to latest kernel source
- Enable ported CLO memory optimization
- Set GPU idle timeout to 58 ms
- Misc changes  in powerhint
- Improve Boot time tuning
- Lower down rate limit for prime CPU 
- Fix PowerHAL nodes
- Switched to uclamp

# 27-May-2024
- Upstreamed to latest 10.5.2 Matrixx source
- Upstreamed n0kernel to latest kernel source

# 16-May-2024
- Upstreamed to latest 10.5.0 Matrixx source
- Introduce OnePlus Dolby daxui and dax service
- Disable pre-rendering feature
- Update blobs from OS1.0.2.0.TKHMIXM
- Downgrade n0kernel from personal fork

# 06-May-2024
- Upstreamed to latest 10.4.3 Matrixx source
- Upstreamed n0kernel to latest kernel source
- Revert back to Neutron 18 clang

# 17-Apr-2024
- Upstreamed to latest 10.4.2 Matrixx source
- Upstreamed n0kernel to latest kernel source
- Switch to Neutron 19 clang
- Improve statusbar padding
- Change Leica camera implementation
- Update Leica apk to Leica 5.0 beta 7.3
- Adapt sepolicies to qpr2
- Adapt xiaomi parts to qpr2
- Rework dolby completely

# 7-Mar-2024
- Upstreamed to latest 10.3.0 Matrixx source
- Upstreamed to latest n0kernel sources
- Improved statusbar padding and height
- Fallback to Leica 4.5
- Add overlay to support System UI restart

# 13-Feb-2024

- Fixed leica where photos wont get saved
- Fixed leica where portrait mode wasn't working
- Switch to Infinir kernel (Idk temporary or permanent lets see how it goes)

# 11-Feb-2024

- Upstreamed to latest 10.3.0 Matrixx source
- Upstreamed to latest n0kernel sources
- Import haptics props from Miui alioth global 13.0.8
- Import all vibrator effects
- Import hw impl for audiohalext (backend)
- Update apn config from aospa
- Matrixx updater fixup
- Update default dax for dolby
- Enable Dolby DS2 support
- Increase audio HAL buffer size to 240
- Add property to enable HWC for VDS
- Switch to Jemalloc for libc
- Enable building ssrec for Audio Externals
- Enable support of HW Accelarated effect
- Remove some camera daemon commands
- Update Leica cam to Univerasal 5.0
- Rework Thermal environment values
- Fix thermal profile to init stage
- Sync carrier config with component
- Fixed statusbar padding

# 22-Jan-2024

- Fixed an issue where Dolby profile would reset on reboot
- Added stereo widening option in Dolby

# 11-Jan-2024

- Upstreamed to latest n0kernel
- Link Dolby Atmos dependencies against v33 libstagefright_foundation
- Patch dolby lib64 libs
- Introduce battery-friendly-pocketmode
- Revert back from health AIDL services to 2.1

# 10-Dec-2023

- Introduce more Dolby Atmos effects.
- Remove play/pause hack while toggling Dolby.
- Implement Dolby profile-specific settings
- Add toggle for Dolby volume leveler
- Add custom icons to Dolby and Dirac
- Import SpatialAudio lib from Cheetah dump
- Add mixer path and configuration for spatial audio
- uprev audio hal to 7.1
- Fix 24bit audio playback
- Update blobs from global 14.0.8.0
- Switch back to N0 kernel
- Switch to Neutron clang 18
- Add missing uceservice hal entry 

# 29-Nov-2023
-Initial release.
