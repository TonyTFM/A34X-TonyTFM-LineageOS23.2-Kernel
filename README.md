# A34X-TonyTFM-LineageOS23.2-Kernel

A34X TonyTFM Kernel — LineageOS 23.2

Custom Linux kernel for the Samsung Galaxy A34 5G (SM-A346B / A34X), built for LineageOS 23.2.

The kernel is based on the Samsung/UN1CA A34X kernel sources and was built using the Android 15 / Linux 6.6 kernel build environment.

Device

- Device: Samsung Galaxy A34 5G
- Model: SM-A346B
- Codename: A34X / a34x
- SoC: MediaTek Dimensity 1080 (MT6877)
- RAM: 6 GB
- Target ROM: LineageOS 23.2
- Kernel branch: Linux 6.6
- Build system: KLEAF / Bazel
- Architecture: ARM64

Features

- Custom kernel built specifically for the Samsung Galaxy A34 5G
- Linux 6.6 kernel base
- LineageOS 23.2 compatibility
- AnyKernel3 flashable package
- Designed for use with custom Android ROMs
- Tested on a real SM-A346B device

Installation

Recovery / AnyKernel3

1. Boot into a custom recovery such as TWRP.
2. Make sure you have a backup of your current boot/kernel setup.
3. Flash:

A34X-TonyTFM-LineageOS23.2-Kernel.zip

4. Reboot to system.

Important

This kernel is intended for the Samsung Galaxy A34 5G SM-A346B / A34X.

Do not flash it on another device or model unless you know that the kernel and device configuration are compatible.

Source

Kernel source:

https://github.com/UN1CA/kernel_samsung_a34x

The build includes the A34X device configuration and the required Samsung/MediaTek kernel components.

Build

The kernel was built on Linux using the Android kernel KLEAF/Bazel build system.

The final kernel was packaged using AnyKernel3:

A34X-TonyTFM-LineageOS23.2-Kernel.zip

Status

Build: Successful
Flash: Successful
Boot: Successful
Device: Samsung Galaxy A34 5G SM-A346B
ROM: LineageOS 23.2

Disclaimer

Flash custom kernels at your own risk.

Always keep a working backup of your current boot/kernel images and a way to return to your previous setup.

The author is not responsible for data loss, bootloops, soft-bricks, or other damage caused by flashing or using this kernel.

Credits

- Samsung
- MediaTek
- Android Open Source Project
- LineageOS
- UN1CA
- AnyKernel3
- All contributors to the Linux kernel and Android kernel ecosystem

Author

TonyTFM

Custom kernel development for the Samsung Galaxy A34 5G.
