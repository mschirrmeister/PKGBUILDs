# linux-aarch-msc-rc

This package is latest [mainline kernel](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git) release from Linus Torvalds.

## Notes

With the upgrade to kernel `6.19+`, basic support for the **NanoPi R76S** is present in the mainline kernel and the patches for basic support are no longer needed.

With the upgrade to kernel `6.18+`, **bcachefs** is no longer part of the mainline kernel and needs to be build as a DKMS module.

With the upgrade to kernel `6.16+`, basic support for the **Rock 5B+** is present in the mainline kernel and the patches are no longer needed.

With the upgrade to kernel `6.14+`, basic support for the **Orange Pi 5 Max** is present in the mainline kernel and the patches are no longer needed.

## Kernel features

Kernel is based on [7Ji](https://github.com/7Ji-PKGBUILDs/linux-aarch64-7ji). The following additional kernel features are enabled.

- ~~Bcachefs (Awesome advanced new filesystem for Linux)~~
- netkit (High performance networking for Kubernetes)

## Patches

- ~~Orange Pi 5 Plus~~
- ~~Orange Pi 5 Max~~
- ~~Rock 5B+~~
- Orange Pi 4 LTS
- FriendlyElec NanoPi R76S
    - microSD card fixes
- Amlogic and Rockchip patches related to reboot issues
