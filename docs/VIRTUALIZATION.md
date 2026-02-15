# Virtualization & Operating Systems

This guide covers the primary software platforms used to manage virtual machines and containers on local hardware.

## Type 1 Hypervisors (Bare Metal)

Bare metal hypervisors install directly on the hardware for maximum performance and efficiency.

- **[Proxmox VE](https://www.proxmox.com/)**
    - **Architecture:** Debian-based platform using KVM for full virtualization and LXC for system containers.
    - **Community Tools:** The "Proxmox Post Install" scripts by tteck are highly useful for initial configuration and automation.
- **[XCP-ng](https://xcp-ng.org/)**
    - A fully open-source virtualization platform based on the Xen project. It is a robust alternative for those requiring enterprise clustering features.
- **[ESXi / vSphere](https://www.vmware.com/)**
    - Historically the industry standard, though licensing changes have shifted many home users toward Proxmox.

## Hyper-Converged & NAS OS

These systems combine storage management with built-in virtualization capabilities.

- **[TrueNAS SCALE](https://www.truenas.com/truenas-scale/)**
    - Linux-based storage platform using ZFS. It provides KVM for virtualization and supports integrated containerized applications.
- **[Unraid](https://unraid.net/)**
    - Known for its flexible drive array management. It includes a user-friendly interface for managing Docker stacks and virtual machines.
- **[CasaOS](https://casaos.io/) / [Umbrel](https://umbrel.com/)**
    - Simplified management layers that install on top of standard Linux distributions. These are designed for ease of use and automated application deployment.

## Linux Distributions

For those preferring a standard Linux environment for bare-metal hosting:
- **Debian:** Often used as the base for stable, long-term server deployments.
- **Ubuntu Server:** Provides broader hardware support and frequent kernel updates.
- **Alpine Linux:** A security-oriented, ultra-lightweight distribution ideal for lean Docker hosts.

---

[Back to Index](../README.md)
