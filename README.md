# CachyOS-Settings
This repository contains configuration files that tweak sysctl values, add udev rules to automatically set schedulers, and provide additional optimizations.

## udev rules
- ZRAM
- audio latency
- SATA, power management for HDD to prioritize max performance.
- IO schedulers, automatic selection schedulers depends on your HW - SATA SSD, NVME and HDD.

## sysctl
Tweaks focused to memory and network.

## modprobe
- - i915 load modules and firmware.

## systemd
- pci latency
- [IRQ balance](https://github.com/Irqbalance/irqbalance) - Irqbalance is a daemon to help balance the cpu load generated by interrupts across all of a systems cpus.
Dupa
