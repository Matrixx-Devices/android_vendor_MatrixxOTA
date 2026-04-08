# 7-April-2026
- Source: Synced with the latest source
- Device: Synced with Lineage changes
- Device: Readded Dolby with Lunaris Dolby
- Device: Synced parts with Material UI3
- Device/Kernel: Enabled Bypass Charging
- Device: 
# 27-November-2025
-Source: Synced with latest source
-Source: Build With November Security Patch
-Device: Drop Miuicam for now 
-Device: Add device side Improvment for less lag
-Device: Add per app maximum refresh rate
-Kernel: Switch to SLMK 
-Kernel: Switch to Kernel Space Battery Saver
-Kernel: Introduce SBalance IRQ balancer
-Kernel: Increase minimum bus frequency
-Kernel: Synced with latest lineage source 


# 14-October-2025
- Kernel: Revert "Enable Power CONFIG_BATT_VERIFY_BY_DS28E16 CONFIG_SMB1390_CHARGE_PUMP_PSY CONFIG_SMB1355_SLAVE_CHARGER CONFIG_QPNP_SMB5 And CONFIG_ONEWIRE_GPIO For faster Charging Speed"
- Source: Synced with latest source

# 27-August-2025
- Kernel: Move 'struct sched_param' out of uapi, to work around glibc/musl breakage
- Kernel: Enable Power CONFIG_BATT_VERIFY_BY_DS28E16 CONFIG_SMB1390_CHARGE_PUMP_PSY CONFIG_SMB1355_SLAVE_CHARGER CONFIG_QPNP_SMB5 And CONFIG_ONEWIRE_GPIO For faster Charging Speed
- Kernel: Improvements & misc changes in Kernel
- Kernel: upstream with LineageOS
- sm6150-common: Drop kernel target-level
- sm6150-common: Drop legacy ANT remnants
- sm6150-common: overlay: Remove deprecated config_mobile_tcp_buffers/networkAttributes
- sm6150-common: Silence Codec2 spammy logs
- sm6150-common: Reformat releasetools.py
- sm6150-common: manifest: Commonize target-level
- sm6150-common: sepolicy: Label bq2597x nodes for surya
- sm6150-common: sepolicy: allow init to bind mount SKU-specific bdwlan firmware
- sm6150-common: rootdir: Set permissions for FPC compatible_all node
- sm6150-common: Enable UFFD GC
- sm6150-common: Run sort-blobs-list.py --dir-first
- phoenix: manifest: Commonize target-level
- Device: Fixed up some sepolicy denials
- Source: Synced with latest source
- Source: Build August Security Patch

# 24-june-2025
- Merge with latest june source

# Changelog 01 JUNE 2025:
- Initial A15 build
- May patch
