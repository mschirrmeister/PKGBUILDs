# linux-aarch64-msc-lts

This package is based on the [LTS kernel](https://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git) release, tuned for maximum stability and longevity on Rockchip and Amlogic platforms.

## Notes

**LTS Focus**: This package tracks the `6.18` LTS branch to ensure a stable foundation for production environments.

**Bcachefs**: As of kernel `6.18+`, bcachefs is no longer in-tree. Users requiring this filesystem should use the external DKMS module.

## High-Performance Networking

This kernel is optimized for modern container workloads and low-latency networking:

- **netkit**: High-performance networking for Kubernetes (Enabled).

## Surgical Patches & Backports

Even on an LTS base, this kernel includes critical backports from mainline (`6.19+`) to ensure hardware operates at peak performance:

- **RK3576 Stability Overhaul**: Backported Shawn Lin's driver and GRF fixes to resolve the 400kHz SDMMC retuning loops.
- **Platform Support**: Enhanced support for Orange Pi 4 LTS and NanoPi R76S.
- **Power Management**: Resolved reboot and shutdown issues for various Amlogic and Rockchip boards.

