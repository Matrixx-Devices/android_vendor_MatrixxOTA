# Matrixx v-11.9.0 (A15) Zeta Changelog 
- October patch merged 
- Fixed Freeform all app page opening in fullscreen
- Fix memory leaks
- Fix fingerprint crash in private space

# Matrixx v-11.8.0 (A15) DELTΔ Changelog 
- Sep patch merged 
- Reduce the size of keyguard affordance 
- Switch to pixel 10 pro xl for mainline spoofing 
- Spoof playstore to mainline
- Update Keybox spoofing & add default keybox in source (now you will get strong out of box)
- Add an option to customize blur radius in Launcher

# Matrixx v-11.7.0-EOL(A15) Tangent Changelog 
- Fix unsupported qs tile icon crash
- Fix flickering issue in streaming video cases
- Backport back button fix from 16 QPR1 Beta 2.1
- Fix vpn disconnects during package state changes
- Fix dark mode schedule 
- Fix crash in YT playback and YT music playback
- Add Power off verify option
- Bring back QuickSwitch
- Fixed ringtone setup for secondary SIM slot
- Fixed colors issue on QS for battery styles
- Fixed QS color for circle battery styles 
- Do not skip search animation for app icons 
- Align icons vertically when labels are hidden
- Cancel ongoing animations before entering All Apps 
- Prevent wrapping of icons from icon packs 
- Quickspace: Various improvements
- Bring Back Opacity Customization in Launcher for Appdrawer and recent
- August Patch

# Matrixx v-11.6.0-Hotfix Trigon Changelog 
- Fix App crashing on 1st click 
- Fix random reboots when restarting device for some users 
- Allow Icon Packs to change battery overlay
- Added overlay path for battery in sam and victor icon pack
- Launcher: import popup view icon from nothingOS
- Launcher: update recent overview color in dark mode
- Explicitly disable storage management preference (broken and show empty space)
- Properly configure wallpaper for vanilla and Gapps builds
- QS Clocks: Update OOS clock style
- PPUtils:fixup spoofing logic
- Allow disabling hdr display boost & allow changing HDR brightness intensity

# Matrixx v-11.6.0 Trigon Changelog
- Fix Clock glimpse issue when unlocking device
- Fix custom clock overlapping on theme switch from light/dark
- Fix default clock color stays white in light mode
- Fix Clock size getting reset after system ui restart
- Add keybox method to pass strog (get your own keys )
- Fix lock/unlock app in launcher recent
- Fix crash in HideAppListSettings when fragment is not attached
- Legacy attestation spoofing changes
- Fixup code for pif and game json file loading (now we don't need to click twice on same option to work)
- Show a popup dialog upon usb connection
- Set scrolling friction to 0.006f
- Disable new carrier group mobile icons(fixes signal icon stays white in expanded qs)
- Added toggle to switch between new revamp qs by google

# Matrixx v-11.5.0 Radian Changelog
- Added hide IME option, 
- Ambient text and img customzations,
- Fix volume pannel hapic switch, 
- Fix comapct media player toggle, 
- Conditionally remove SAF restrictions, 
- Restart SystemUI on lockclock font select, 
- Improve cutout force full screen, 
- Remove extra padding in settings page v2 style,
- Added compact status bar progress chip  style
- Added Bypass charging support 
- Added option to spoof encryption status 
- Fixes and improvement
- Fix recent button color
- Fix clone app not appearing in app drawer
- Bring back lens in recent button
- Allow Settings or SUW to connect to insecure Enterprise networks

# Matrixx v-11.4.0 Polar Changelog
- Update source to A15 qpr2 
- Add option to switch to A14 settings style 
- Add option to switch settings search bar style to A14 
- Integrate Avatar inside A15 searchbar (ps try to copy scamsung ig) 
- Add power menu style 
- Add notification style 
- Make lock recent app option togglebale
- Allow changing font for lockscreen clock
- Added default game spoof prop for some games 
- Added option to enable/disbale show media progress and control media playback from statusbar chip

# Matrixx v-11.2.6 CARTESIAN Changelog
- Implement Ongoing ProgressBar Chip and make it togglable
- Introduce QuickSwitch
- Add Ambient Customizations
- Bring back Matrixx udfps icon
- Implement Remove IME space under keyboard feature
- Introduce AutoDimService
- drop HTS switch
- Add recent button for locking tasks to recents
- Drop Share Button and bringback lens button in recent 
- rework app scrim colors for launcher 
- Introduce PowerOffAlarmService
- Optimize launcher animations
- Guard BCR and G(Dialer, Message, Phone) with flag

# Matrixx v-11.2.5 CARTESIAN Changelog
- Tweak the About phone a little
- added option to show cpu - battery temp in ambient
- add some more location exemption
- disable some more usless services
- Fixed lockscreen clock and weather padding for non smartspace users
- Reducing tg scrolling lag
- Try to reduce qs jitter
- Fixed avatar picker crashing in vanilla build
- Conditionally Support cinematic wallpaper in matrixx Launcher
- Add include pixel overlays conditionally
- redesign charging ripple
- Set the entire screen recorder as default
- Fix haptic feedback switch for volume slider (prev not applying on volume change through UI)
- Make a Haptic on volume slider better
- Add ability to resize qs clock and satus bar clock
- Add a notch bar killer for the left notch device
- Fix keyguard user avatar margins
- Skip launcher overview scale animation on tablet (should fix 2/3 app size when switching app through recent)
- Make zram info in recent optional
- Update cyberpunk qs styles notification
- Update Matrixx Launcher themed icons to pixel like
- Improve contextual greeting messages a bit
- Removed some ugly qs styles
- Added flashlight intensity support (need device side support too)
- Remove ability to set opacity in the launcher recent and app drawer also set default opacity value to 100

**A big thanks to Crdroid**

# Matrixx v-11.2.0 LEMMA Changelog
- Added IOS-16 battery style
- Added an option for setting Greeting Messages
- Added Some qs header clocks styles 
- Added hide developer option 
- Added Hide app list
- Added statausbar lyrics option 
- Added idle manager
- Added General Sans font 
- Fixed color notification icon (Thanks to neobuddy)
- Fixed less boring headsup (Thanks to neobuddy)
- Fixed Qs dynamic color.
- A lots of under the hood optimization

**A big thanks to Crdroid**

# Matrixx v-11.1.0 AXIOM Changelog
- Initial android 15 release based on QPR1
- Minimal UI adoption
- Most of the A14 features added
