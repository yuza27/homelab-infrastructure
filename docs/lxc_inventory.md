# 📋 Proxmox VE (yuzuchan) LXC Inventory

Overview of all active lightweight LXC containers running on the `yuzuchan` Proxmox VE host, mapping each container ID to its dedicated network/application service.

| CT ID | Container Name | Service / Role | Description | Status |
| :---: | :--- | :--- | :--- | :---: |
| `100` | `Cloudflare` | Zero-Trust Ingress | Cloudflare Tunnel client daemon (`cloudflared`) | 🟢 Running |
| `101` | `adguard` | Network Security & Filtering | AdGuard Home DNS server (Ad-blocking, DoH, LAN Gateway) | 🟢 Running |
| `102` | `grafana` | Monitoring Visualization | Grafana Dashboard for system telemetry & logs | 🟢 Running |
| `105` | `homelable` | Topology Canvas Engine | Self-hosted web app (React Flow) to render interactive topology diagrams | 🟢 Running |
| `106` | `Docker` | Containerized App Host | Docker runtime environment hosting image compression tools | 🟢 Running |
| `107` | `bentopdf` | Self-Hosted Application | BentoPDF / PDF manipulation suite | 🟢 Running |
| `108` | `linkding` | Self-Hosted Application | Linkding bookmark & link tag manager | 🟢 Running |
| `109` | `prometheus-pve-exporter` | Telemetry Exporter | Prometheus exporter specifically for Proxmox VE host metrics | 🟢 Running |
| `110` | `technitiumdns` | Recursive & Local DNS | Technitium DNS server for internal local zones & upstream resolution | 🟢 Running |
| `111` | `nginxproxymanager` | Reverse Proxy & SSL | Nginx Proxy Manager for internal port mapping & Cloudflare SSL | 🟢 Running |
| `112` | `prometheus` | Time-Series Metrics | Prometheus server for metric collection & scraping | 🟢 Running |
| `113` | `loki` | Centralized Logging | Grafana Loki log aggregation engine | 🟢 Running |

> **Note:** CT `104` (N8N) is currently inactive/idle and omitted from primary production routing.
