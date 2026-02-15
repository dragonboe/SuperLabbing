# Sourcing & Procurement Guide

This guide covers practical methods for finding hardware and building a homelab on a budget. It focuses on used enterprise gear and cost-effective modern alternatives.

## Sourcing Strategies

### Enterprise Hardware
- **[Lab Gopher](https://www.labgopher.com/)** - Best for tracking eBay listings of Dell PowerEdge and HP ProLiant servers. It provides a "Goodness" rating based on specs per dollar.
- **[ServerMonkey](https://www.servermonkey.com/)** - A reliable source for refurbished enterprise gear with limited warranties.

### Government & University Auctions
Institutions often cycle out hardware every 3-5 years. These are excellent sources for racks, switches, and large drive arrays.
- **[GovDeals](https://www.govdeals.com/)** - Search for "Computers" or "Networking Gear" in your local area.
- **[Public Surplus](https://www.publicsurplus.com/)** - Similar to GovDeals; often has bulk lots of office PCs.

### Local Marketplaces
When searching on Facebook Marketplace or Craigslist, use specific model names rather than generic terms.
- **Keywords:** `OptiPlex Micro`, `ProDesk Tiny`, `EliteDesk`, `NUC`, `R730`.
- **Tip:** Many office PCs (Mini/Tiny/Micro) are sold for very low prices and make highly efficient Proxmox nodes.

---

## Hardware Classes

### Low-Power & Thin Clients
Small nodes for single-purpose services (Home Assistant, Pi-hole).
- **HP T620 / T630:** Passive cooling, silent, and very low power consumption.
- **Wyse 5070:** Highly recommended for its low idle power and decent performance.

### Modern Mini PCs
The current sweet spot for most homelabs due to QuickSync and low idle power.
- **Intel N100 / N305:** Capable of handling multiple 4K transcodes and dozens of Docker containers.
- **Ryzen 7xxx / 8xxx SFF:** Better for multi-threaded workloads and high-performance VMs.

### Enterprise Rack Servers
Necessary for high core counts, large RAM requirements (ECC), and many PCIe lanes.
- **Dell R730 / R730xd:** Widely available, supports DDR4, and has excellent internal storage options.
- **HP DL380 Gen9:** Reliable alternative to the Dell R-series.

---

## Technical Accessories

- **Power Monitoring:** [Kill-A-Watt](http://www.p3international.com/products/p4400.html) is standard for measuring idle power of your lab.
- **VLAN Support:** A managed switch like the [TP-Link TL-SG108E](https://www.tp-link.com/us/business-networking/unmanaged-pro-switch/tl-sg108e/) is essential for network segregation.
- **Battery Backup:** A UPS (Uninterruptible Power Supply) is critical for preventing filesystem corruption during power events.

---

[Back to Index](../README.md)
