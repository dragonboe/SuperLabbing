# 🛠️ Hardware Foundations (2026 Edition)

Building a homelab in 2026 is all about **Performance per Watt**. Gone are the days of needing a power-hungry rack of R710s just to run a few containers.

## 🚀 The "Mini PC" Revolution
Small Form Factor (SFF) and Mini PCs are the gold standard for modern labs.

*   **The King: Intel N100 / N305**
    *   **Why:** Ultra-low power (6W-15W TDP), AV1 decoding, and enough threads for 20+ Docker containers.
    *   **Best Models:** Beelink EQ12, Minisforum UN100, ASUS ExpertCenter.
*   **The Workhorse: Ryzen 7000/8000 Series Mini PCs**
    *   **Why:** High core counts (8C/16T) and incredible iGPU performance for Plex/Jellyfin transcoding.
    *   **Best Models:** Minisforum UM780 XTX, Beelink SER7.

## 🌍 The ARM Ascension
ARM is no longer just for Raspberry Pis.

*   **Orange Pi 5 Plus:** Features the RK3588, M.2 NVMe support, and dual 2.5GbE ports. Faster than a Pi 5 for server tasks.
*   **Ampere Altra:** If you want "Real" ARM servers with 32 to 128 cores.
*   **Apple Silicon (M2/M3/M4):** Great for Mac-specific builds or ultra-efficient silent nodes.

## 💾 Storage & Networking
*   **10GbE is the new 1GbE:** With SFP+ switches dropping below $100, 10GbE is now standard for internal backbones.
*   **NVMe Everywhere:** SATA is fading. Modern mini-servers often support 2x or 3x M.2 slots for high-speed ZFS pools.
*   **DAS vs NAS:** Many are moving away from massive power-hungry NAS units towards USB-C/Thunderbolt DAS (Direct Attached Storage) connected to efficient Mini PCs.

## 🛒 Where to Buy
1.  **[Lab Gopher](https://www.labgopher.com/):** Still the best place to find used enterprise gear on eBay.
2.  **[ServerMonkey](https://www.servermonkey.com/):** Refurbished enterprise servers with warranties.
3.  **AliExpress:** Great for "no-name" N100 / N305 router boxes with 4x-6x 2.5GbE ports.

---
[⬅️ Back to Home](../README.md)
