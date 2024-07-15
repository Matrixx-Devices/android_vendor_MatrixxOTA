## 16-July-2024

- Disable Smart Pixels on UDFPS
- Fixed audio issue when screen is off
- Fixed camera not recording video after the device is on for a while
- Fixed touch issue
- Merge latest android-4.19-stable (4.19.317) into kernel
- Merge tag 'LA.UM.9.12.r1-18400-SMxx50.QSSI14.0' into `audio-kernel`, `display-drivers`, `fw-api`, `qcacld-3.0`, `qca-wifi-host-cmn`, `video-driver`
- All changes from Yuragi Kernel r2 included

## 15-June-2024

- Initial official build
- Enable more cpu governor and TCP congestion algorithm
- Fix log spam about cpu4 node path
- Imported `bbr2` and set as default TCP
- Imported `NTFS3` drivers
- Imported `ssg` scheduler from G998USQU5CVDB
- Included firmware
- Initial build with rebased tree
- Many optimization to kernel for better bb and smoother system
- Merge latest android-4.19-stable (4.19.315) into kernel
- Rebranded kernel to `yuragi`
- Switch to pixel `power-libperfmgr`
- Switch to common camera shim
- Update KernelSU to v1.0
- Update `mi_thermald` blobs from munch
- Update blobs and firmware from latest MIUI V13.0.9.0.SJVCNXM
- Use ARM64 v8 ASM to accelerate `lz4` decompression
