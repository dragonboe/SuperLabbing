# 📦 Homelab Materials & Buyer's Guide (2026)

Finding the right gear doesn't have to be expensive or complicated. This guide breaks down the easiest ways to source hardware and provides a tiered path from "free" to the "ultimate rig."

---

## 🔍 Easy Ways to Find Hardware

### 1. The Pro's Secret: [Lab Gopher](https://www.labgopher.com/)
This tool crawls eBay specifically for enterprise servers (Dell PowerEdge, HP ProLiant). It categorizes them by price-to-performance and "Goodness" rating. **The easiest way to find power for cheap.**

### 2. Government & University Auctions
Institutions offload massive amounts of server gear every 3-5 years.
*   **[GovDeals](https://www.govdeals.com/):** Look for "Computers" or "Servers." You can often find a whole rack for $100 if you're willing to pick it up locally.
*   **[Public Surplus](https://www.publicsurplus.com/):** Similar to GovDeals, great for bulk lots.

### 3. Local Marketplace (FB / Craigslist)
*   **Keyword Tip:** Don't just search "Server." Search for `OptiPlex`, `ProDesk`, `NUC`, or `Workstation`.
*   **Why:** Many people sell "office PCs" without realizing they make perfect low-power homelab nodes.

---

## 📈 Tiers: From Budget to "The Best Rig"

### 🟢 Tier 1: Ultra Budget ($0 - $75)
*Target: Learning and Lightweight Services (Pi-hole, Home Assistant)*
*   **The Gear:** Used Thin Clients (HP T620/T630) or your old cracked-screen laptop.
*   **Why:** Thin clients are silent, consume < 10W, and are built like tanks.
*   **Where to buy:** eBay search for "HP Thin Client" or "Wyse 5070."

### 🟡 Tier 2: The Entry Point ($150 - $250)
*Target: 24/7 Docker Stacks, Media Streaming (Plex 1080p)*
*   **The Gear:** **Intel N100 Mini PC**.
*   **Recommended:** Beelink S12 Pro or Minisforum UN100.
*   **Why:** The Intel N100 is the 2026 king of budget labs. It handles 4K transcoding with Quicksync and uses almost zero power.

### 🟠 Tier 3: The "Sweet Spot" ($400 - $700)
*Target: Full Virtualization (Proxmox), Multiple VMs, 4K Transcoding*
*   **The Gear:** **Ryzen 7/9 Mini PC** or **Used Enterprise Server**.
*   **Mini PC Path:** Minisforum UM780 XTX (Ryzen 7 7840HS).
*   **Enterprise Path:** Dell PowerEdge R730xd (Used).
*   **Why:** 8+ Cores and 32GB+ RAM. This is where you can run a serious lab without limitations.

### 🔴 Tier 4: The "Best Rig" (High-End) ($1,200+)
*Target: Massive Data Hoarding, Local AI (LLMs), High-Speed 10GbE Networking*
*   **The Hardware:**
    *   **CPU:** AMD EPYC 7002/7003 series (Used/New) or Ryzen 9 7950X.
    *   **RAM:** 128GB - 256GB ECC DDR5.
    *   **Networking:** Integrated 10GbE or SFP+ Fiber cards.
*   **Recommended Build:** Custom Mid-Tower with a Supermicro/Asrock Rack motherboard.
*   **The "Ready-to-Go" King:** **Beelink SER9 Max** or **Mac Studio (M4)** for specialized ARM dev.

---

## 🔌 Essential Materials (The "Ease of Use" Kit)

*   **[Kill-A-Watt Meter](http://www.p3international.com/products/p4400.html):** To see exactly how much your lab is costing you in electricity.
*   **Managed Switch:** [TP-Link TL-SG108PE](https://www.tp-link.com/us/business-networking/poe-switch/tl-sg108pe/) - Cheap, supports VLANs (essential for security).
*   **UPS (Battery Backup):** [APC Back-UPS](https://www.apc.com/us/en/product-range/61883-backups/) - Protects your data from power surges and outages.
*   **Label Maker:** Trust us, you’ll need it. [Brother P-Touch](https://www.brother-usa.com/p-touch) is the gold standard.

---
[⬅️ Back to Home](../README.md)
