# Monitoring & Management

Tracking system performance, uptime, and service health is essential for a stable homelab environment.

## Metrics & Visualization

- **[Prometheus](https://prometheus.io/)** - A monitoring system and time-series database that collects metrics through a pull model.
- **[Grafana](https://grafana.com/)** - An analytics and visualization platform that integrates with Prometheus, InfluxDB, and other data sources to create detailed performance dashboards.
- **[InfluxDB](https://www.influxdata.com/)** - A purpose-built time-series database often used for storing metrics from IoT devices or smart home sensors.

## Uptime & Real-time Statistics

- **[Uptime Kuma](https://github.com/louislam/uptime-kuma)** - A monitor that tracks service availability through HTTP(s), Ping, and TCP checks, providing an status page and notification integrations.
- **[Netdata](https://www.netdata.cloud/)** - Provides high-resolution, real-time metrics for system-level monitoring directly on the host.
- **[Glances](https://nicolargo.github.io/glances/)** - A cross-platform system monitoring tool with a console-based interface.

## Centralized Dashboards

Unified interfaces for accessing self-hosted services and monitoring summary data.

- **[Homepage](https://gethomepage.dev/)** - A modern dashboard that integrates with various service APIs to display stats and status indicators.
- **[Dashy](https://dashy.to/)** - A highly configurable dashboard with support for complex layouts and multiple themes.
- **[Flame](https://github.com/pawelmalak/flame)** - A minimalist dashboard focused on speed and simplicity.

## Log Management

- **[Loki](https://grafana.com/oss/loki/)** - A horizontally scalable, multi-tenant log aggregation system inspired by Prometheus.
- **[Dozzle](https://dozzle.dev/)** - A simple web interface for viewing Docker container logs in real-time.

---

[Back to Index](../README.md)
