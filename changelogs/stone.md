#v18-July-2024
- Synced with latest source

# 30-May-2024
- Synced with latest source
- Fixed all battery drain issues
- Fixed smart pixel
- More underhood changes

# 26-May-2024
- Synced with latest source
- Signed build for cts
- Added support for 24 bit wired headphones
- Enabled vibrate on icon animation
- Added script for remove cache and package cache after dirty flash
- Extended audio offload buffer size
- Enabled all vibration intensity
- Use the new auto network selection page
- Fixed updater missing issue
- Increased swappiness
- Switched to LMKD
- Remove deprecated trust HAL,libtinyxml
- Add back refresh rate overlays
- Added props for better ram management
- Disabled display refresh rate override
- Silence battery logspam
- Tuned powerhint.xml for performance
- Many more underhood changes

# 14-May-2024
- Synced with latest source
- Rebased over new tree
- Added leica,viper,dolby
- Many more underhood changes

# 29-April-2024
- Synced with latest source
- Re-Added dirac
- Revert back to old adreno drivers
- Revert back to old cpu freq method

# 18-April-2024
- Synced with latest source
- rootdir: Fix the battery drain due to statsd
- Builded goodix lib from source
- Enabled battery cycle count
- Added media_codecs from stock holi config and build some codecs
- Many more changes & fixes

# 17-March-2024

- Synced with latest source
- Reduced app opening/closing animation lags and Jitters
- Reduced qs lag when pulling it down
- Enabled VoNR Calls support
- updated Vendor Security Patch Level
- Removed dirac
- Fixed systemui crashing sometimes
- Many more changes

# 04-March-2024

- Added Dirac aka mi sound enhencer
- v4a & dolby present in rom
- Set low memory mode
- Dropped pinnerservice
- Set zram to 25% and swapiness to 20
- Fixed screen recorder audio recording
- Disabled Hardware Composer VDS debug
- Disabled "mobile data always on"
- Compact cached app heaps in the background
- Update screenrecorder to 4.2 and set framerate to 120
- Add malloc_svelte and camera override for newer features and perf improvements
- Switched to 8Gb dalvik heap size config
- Many more changes

# 27-Feb-2024

- Synced with latest source
- Disabled vsync for CPU rendered Apps
- rootdir: Hide Magisk Better
- Force disabled iorapd
- Enabled ro.hwui.render_ahead and set it to 20 frames
- set ro.hwui.render_ahead=23
- Use speed tuning for performance critical applications
- Compile HWUI for performance
- Reduce screenshot delay to 0
- Use HintManager for HWUI
- Fix screen record lag
- Add props to improve battery backup
- Disable slow blur effect to avoid laggish blur effect
- Added few touch props
- props: For smoother scrolling and better
- Add smooth motion flag
- props: Better RAM Management
- Disable blur on app launch
- Speed profile services
- Clean up useless log spams
- Optimize everything on preopt
- Stop bootanimation service after boot
- Disable frame rate override feature
- Add props for better signal
- Tune Vsync Phase Offset
- don't latch unsignal buffers
- Set debug.sf.frame_rate_multiple_threshold to 60 by default
- Add a property to enable prefetching video
- Import SettingsResStone
- Enabled all available vibration intensity
- Added audio start audio rpc daemon early to improve perf
- Setup Dalvik heap configuration
- Added Viper4Android
- Many more changes

# 19-Feb-2024

- Initial official release.
- Added better touch props.
- Many improvements here and there.
