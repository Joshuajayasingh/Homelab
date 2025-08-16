# My Personal Homelab & Infrastructure

![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## About This Project

This repository contains the configuration, automation scripts, and documentation for my personal homelab. This environment serves as my practical learning sandbox for mastering DevOps, Cloud Native principles, and Systems Engineering at an enterprise level. It's a continuously evolving project where I experiment with new technologies and apply the theoretical concepts I learn to solve real-world problems.

## Core Technologies

| Category | Technology | Description |
| :--- | :--- | :--- |
| **Orchestration** | Docker | For container management, scalability, and service resilience. |
| **Automation** | Ansible | *(Planned)* For configuration management and a full Infrastructure as Code (IaC) workflow. |
| **Networking** | Pi-hole | Provides network-wide ad-blocking and local DNS resolution for all services. |
| **Operating System** | Linux (Debian) | The stable, secure foundation for the entire infrastructure. |
| **Monitoring** | Prometheus & Grafana | *(Planned)* For a full observability and metrics stack. |

## Architecture & Services

The lab is built on a single-node server running a minimal Linux distribution. All services are containerized to ensure portability and isolation.

### Key Self-Hosted Services:

* **Pi-hole:** A network-level ad and tracker blocker that also serves as the local DNS server, allowing me to give memorable names to my internal services.
* **Immich:** A high-performance, self-hosted photo and video backup solution, serving as a private alternative to Google Photos.
* **Minecraft Server:** A containerized game server for a private community, managed and kept up-to-date via automated processes.
* **Portfolio Website:** My personal portfolio, served as a lightweight, containerized web application. *(still not open open to public because i dont want to pay 300rs/month to airtel to port forward, so for now i use tailscale to connect all my devices together and use my services)*

## Current Goals & Future Roadmap

This project is always in development. Here is a high-level overview of my current goals:

- [x] Containerize all core services using Docker.
- [ ] Complete the full migration of all services to a single-node Kubernetes (K3s) cluster.

