# 🛡️ Networking & Security

A lab is only as good as its security. Don't be the person who gets their network encrypted by ransomware.

## 🚦 Routers & Firewalls
Move away from ISP routers for advanced VLAN and VPN support.

*   **[OPNsense](https://opnsense.org/):** Hardened, open-source, and has a beautiful modern UI. Highly recommended over pfSense for most newer labs.
*   **[pfSense CE](https://www.pfsense.org/):** The classic. Rock solid, massive community support.
*   **[Ubiquiti UniFi](https://ui.com/):** For those who want the "Apple of Networking." Beautiful hardware and management, but proprietary.

## 🏠 Secure Remote Access (VPNs)
Stop opening ports (except for 443/80 if needed).

*   **[Tailscale](https://tailscale.com/):** Magic Zero-Config VPN. Works on everything. Based on WireGuard.
*   **[WireGuard](https://www.wireguard.com/):** The fastest, simplest VPN protocol. Use it directly or via OPNsense.
*   **[Cloudflare Tunnels](https://www.cloudflare.com/products/tunnel/):** Expose your services securely without opening a single port in your firewall.

## 🧹 DNS & Ad-Blocking
*   **[Pi-hole](https://pi-hole.net/):** The OG. Network-wide ad blocking.
*   **[AdGuard Home](https://adguard.com/en/adguard-home/overview.html):** Often preferred in 2026 for its built-in DNS-over-HTTPS (DoH) and cleaner UI.
*   **[Unbound](https://nlnetlabs.nl/projects/unbound/about/):** Run your own recursive DNS server for ultimate privacy.

## 🔐 Authentication & Zero Trust
*   **[Authelia](https://www.authelia.com/) / [Authentik](https://goauthentik.io/):** Add 2FA/SSO to every app in your lab.
*   **[CrowdSec](https://www.crowdsec.net/):** Modern, community-driven firewall that blocks IPs based on collective intelligence. Think "Waze for Security."
*   **[Vaultwarden](https://github.com/dani-garcia/vaultwarden):** Lightweight, self-hosted Bitwarden server for all your passwords.

---
[⬅️ Back to Home](../README.md)
