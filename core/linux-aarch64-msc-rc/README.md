# linux-aarch-msc-rc

This package is latest [mainline kernel](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git) release from Linus Torvalds.

## Notes

With the upgrade to kernel `6.14+`, basic support for the **Orange Pi 5 Max** is present in the mainline kernel and the patches are no longer needed.

**Rock 5B+** is not yet in mainline, hence manually patched in.

## Kernel features

Kernel is based on [7Ji](https://github.com/7Ji-PKGBUILDs/linux-aarch64-7ji). The following additional kernel features are enabled.

- Bcachefs (Awesome advanced new filesystem for Linux)
- netkit (High performance networking for Kubernetes)

## Patches

- Rock 5B+
