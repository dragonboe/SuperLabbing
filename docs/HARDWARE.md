# Hardware Guide

Modern homelabbing has shifted toward efficiency and "Performance per Watt." This document covers hardware choices for different workloads within a home environment.

## Mini-PC Platforms (Small Form Factor)

Mini PCs are now the most common choice for home labs due to their low noise and high density.

### Intel N100 / N305
- **Performance:** Efficient quad-core/octa-core chips that handle 24/7 background services easily.
- **Transcoding:** Features 12th/13th Gen QuickSync (AV1 support), making them excellent for media servers.
- **Recommended Models:** Beelink EQ12, Minisforum UN100, ASUS ExpertCenter.

### High-Performance Mini PCs (AMD Ryzen)
For labs running heavyweight VMs or many database instances.
- **Specs:** 8-core/16-thread Ryzen 7000/8000 series chips.
- **DDR5 Support:** Faster memory and higher capacity limits compared to budget N100 units.
- **Recommended Models:** Minisforum UM780 XTX, Beelink SER7.

## ARM Systems

ARM is an excellent choice for dedicated network appliances or edge devices.

- **Orange Pi 5 Plus:** Significant performance jump over previous SBC generations. Features M.2 NVMe slots and dual 2.5GbE ports.
- **Ampere Altra Systems:** For enterprise-grade ARM development with high core counts (32-128 cores).
- **Apple Silicon (M-series):** Used for high-efficiency, silent virtualization or macOS-specific workloads.

## Networking & Storage

### High-Speed Networking (10GbE)
10GbE is becoming a standard for the lab backbone.
- **Fiber (SFP+):** The most cost-effective way to achieve 10Gbps using used enterprise switches and DAC cables.
- **Copper (RJ45):** Easier for existing cat6 cabling but runs hotter and requires more power.

### Storage Architecture
- **NVMe:** Preferred for OS drives and high-speed data pools.
- **Enterprise SAS/SATA:** Still the standard for large-scale data hoarding in rack-mount servers or DAS (Direct Attached Storage) units.

---

[Back to Index](../README.md)
