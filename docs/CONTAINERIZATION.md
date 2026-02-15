# Containerization

Containerization allows for running modular services with minimal overhead and isolated dependencies. It is the primary method for deploying software in modern home labs.

## Container Engines

- **[Docker](https://www.docker.com/)** - The most common engine with extensive community support and documentation.
- **[Podman](https://podman.io/)** - A daemonless, rootless alternative to Docker, often preferred for security-focused environments.
- **[LXC (Linux Containers)](https://linuxcontainers.org/)** - Operating system-level virtualization used primarily on Proxmox for high-performance service isolation.

## Management Interfaces

Visual tools can simplify the deployment and monitoring of container stacks.

- **[Portainer](https://www.portainer.io/)** - Provides a comprehensive dashboard for managing Docker engines, stacks, and networks.
- **[Dockge](https://dockge.kuma.pet/)** - A minimalist manager focused on editing and managing `docker-compose.yaml` files.
- **[Yacht](https://yacht.sh/)** - A lightweight dashboard for templated application deployments.

## Kubernetes for Homelabs

For multi-node orchestration and high availability.

- **[K3s](https://k3s.io/)** - A lightweight Kubernetes distribution optimized for small-form-factor devices.
- **[KIND (Kubernetes in Docker)](https://kind.sigs.k8s.io/)** - Useful for testing multi-node Kubernetes configurations within a single Docker environment.
- **[Talos OS](https://www.talos.dev/)** - An immutable, security-focused Linux distribution designed specifically for running Kubernetes clusters.

## Local Machine Learning Workloads

Techniques for running large computational models within containers:
- **[Ollama](https://ollama.com/)** - Simplified local execution of large language models.
- **[LocalAI](https://localai.io/)** - A self-hosted API compatible with standard machine learning specifications.

---

[Back to Index](../README.md)
