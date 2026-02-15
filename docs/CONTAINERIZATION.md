# 🐳 Containerization

Containers are the heartbeat of the modern homelab. They allow you to run hundreds of services with minimal overhead and zero dependency conflicts.

## 🛠️ The Engines
*   **[Docker](https://www.docker.com/):** The industry standard. Simple, powerful, and has the largest ecosystem.
*   **[Podman](https://podman.io/):** The "Rootless" alternative. Great for security-conscious labs.
*   **[LXC (Linux Containers)](https://linuxcontainers.org/):** Used extensively in Proxmox. Lower overhead than Docker but requires more manual configuration.

## 🕹️ Management GUIs
If you don't want to live in the CLI:

*   **[Portainer](https://www.portainer.io/):** The absolute best visual manager for Docker. Full control over stacks, networks, and images.
*   **[Dockge](https://dockge.kuma.pet/):** A newer, simpler manager focused specifically on `docker-compose.yaml` files. Created by the developer of Uptime Kuma.
*   **[Yacht](https://yacht.sh/):** A lightweight templated manager for easy app deployment.

## ☸️ The "Next Level": Kubernetes
When one node isn't enough.

*   **[K3s](https://k3s.io/):** Lightweight Kubernetes by Rancher. Perfect for Raspberry Pis or small N100 clusters.
*   **[KIND (Kubernetes in Docker)](https://kind.sigs.k8s.io/):** Great for testing K8s manifests without a full cluster.
*   **[Talos OS](https://www.talos.dev/):** A security-focused, immutable Linux distro built specifically for Kubernetes.

## 🤖 Homelab AI in 2026
Running local AI is now standard:
*   **[Ollama](https://ollama.com/):** The easiest way to run LLMs (Llama 3, Mistral) in a container.
*   **[LocalAI](https://localai.io/):** An OpenAI-compatible API for local LLMs, image generation, and more.

---
[⬅️ Back to Home](../README.md)
