# Networking & Security

Documenting infrastructure choices for securing a local network and managing internal/external traffic.

## Routing & Firewall Platforms

Transitioning from consumer routers to dedicated firewall platforms allows for advanced traffic management and VLAN segregation.

- **[OPNsense](https://opnsense.org/)** - A hardened, open-source firewall based on FreeBSD. It provides a modern interface and extensive plugin support.
- **[pfSense CE](https://www.pfsense.org/)** - A widely established open-source firewall with a long history of stability and large-scale community documentation.
- **[Ubiquiti UniFi](https://ui.com/)** - An integrated networking suite providing simplified management through a central controller.

## Secure Remote Access

We prioritize methods that avoid exposing multiple open ports to the internet.

- **[Tailscale](https://tailscale.com/)** - A mesh VPN based on WireGuard. It simplifies secure connectivity between devices without complex firewall configurations.
- **[WireGuard](https://www.wireguard.com/)** - A high-performance, modern VPN protocol implemented as a lightweight alternative to IPsec or OpenVPN.
- **[Cloudflare Tunnels](https://www.cloudflare.com/products/tunnel/)** - Provides a method to expose internal services through the Cloudflare network without modifying local firewall rules.

## DNS Management

- **[AdGuard Home](https://adguard.com/en/adguard-home/overview.html)** - A network-wide DNS server that includes filtering for ads and tracking, with native support for encrypted DNS protocols.
- **[Pi-hole](https://pi-hole.net/)** - A DNS-based blocking tool designed to sinkhole tracking and advertising domains at the network level.
- **[Unbound](https://nlnetlabs.nl/projects/unbound/about/)** - A validating, recursive DNS resolver that enhances privacy by querying root name servers directly.

## Identity & Access Control

- **[Authentik](https://goauthentik.io/) / [Authelia](https://www.authelia.com/)** - Open-source identity providers that add multi-factor authentication (MFA) and Single Sign-On (SSO) to local applications.
- **[CrowdSec](https://www.crowdsec.net/)** - A security engine that analysis logs to detect and block malicious traffic based on community-sourced threat intelligence.
- **[Vaultwarden](https://github.com/dani-garcia/vaultwarden)** - A lightweight, self-hosted implementation of the Bitwarden API for password management.

---

[Back to Index](../README.md)
