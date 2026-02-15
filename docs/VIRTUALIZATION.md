# 📀 Virtualization & Operating Systems

The software layer that turns your hardware into a flexible powerhouse.

## 🏗️ Type 1 Hypervisors (Bare Metal)
The most common way to run a homelab.

*   **[Proxmox VE (9.x)](https://www.proxmox.com/)**
    *   **The Go-To:** Based on Debian, uses KVM for VMs and LXC for containers. 
    *   **Pro Tip:** Use the "Proxmox Post Install" scripts from [tteck](https://tteck.github.io/Proxmox/) to automate your setup.
*   **[XCP-ng](https://xcp-ng.org/)**
    *   The open-source alternative to Citrix Hypervisor. Excellent for large clusters.
*   **[ESXi / vSphere](https://www.vmware.com/)**
    *   Still powerful, but Licensing changes in 2024/2025 have pushed many away towards Proxmox or Hyper-V.

## 📦 Hyper-Converged / NAS OS
Systems that combine storage and virtualization.

*   **[TrueNAS SCALE](https://www.truenas.com/truenas-scale/)**
    *   Built on Linux. Uses ZFS for storage and KVM for VMs. Transitioning to integrated Docker/Apps in recent versions.
*   **[Unraid](https://unraid.net/)**
    *   Famous for its unique "mixed drive" parity system. Best-in-class UI for Docker management.
*   **[CasaOS](https://casaos.io/) / [Umbrel](https://umbrel.com/)**
    *   "Home Server OS" layers that sit on top of Debian/Ubuntu. Perfect for beginners who want a "One-Click App Store" experience.

## 🐧 Preferred Linux Distros
If you prefer running on bare metal Linux:
*   **Debian:** The rock-solid foundation for most labs.
*   **Ubuntu Server:** Great for hardware support and newer kernels.
*   **Alpine Linux:** Ultra-lightweight, perfect for dedicated Docker hosts.

---
[⬅️ Back to Home](../README.md)
