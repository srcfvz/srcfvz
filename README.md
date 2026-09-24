# Hi, I'm Alex

**I build and run small production systems: Linux, networking, APIs and automation.**

Based in Bucharest, Romania. I come from board-level phone repair, where nothing comes with an error message, and from a 24/7 NOC where I monitored 14 client environments. Since then I've built things for clients and for myself, and kept them running in production. The part I enjoy most is working out why something broke.

## What I'm running now

### [Needles](https://needlescrm.eu)

A CRM for tattoo and piercing studios. I designed and built it, and I operate it. It's in public beta, live with a pilot studio since September 2026.

- **Multi-tenant:** a separate PostgreSQL schema for each studio; sensitive client data encrypted field by field (AES-256-GCM, per-tenant keys)
- **Integrations on the studio's own accounts:** WhatsApp Cloud API for client reminders, a Telegram bot for artists, two-way Google Calendar sync
- **Operations:** Hetzner, Docker, Coolify, Cloudflare, backups, and I'm the one who gets paged
- **Code:** private. There's a [live demo](https://needlescrm.eu/app/#/demo); the interface is in Romanian.

### A home lab, since 2019

Home Assistant and MQTT, Prometheus and Grafana, self-hosted services behind Cloudflare Tunnels and Access, Traefik ingress, and three small Kubernetes clusters I use to learn.

## Public repos

**[valheim-server](https://github.com/srcfvz/valheim-server)** · *decommissioned, kept as a reference*
A containerized game server on a Hetzner VPS: key-only SSH, firewall rules, preflight checks before every deploy, and an operations runbook. It also documents two firewall problems hit in production, including Docker-published ports bypassing firewalld.

**[wow-mcp](https://github.com/srcfvz/wow-mcp)** · *abandoned when I stopped playing*
An MCP server that let an AI assistant read my World of Warcraft inventory and auction prices from the game's SavedVariables files, used from Codex CLI. The server worked. The in-game chat bridge was started but never finished.

## Built elsewhere

Private repos or client work. Happy to walk through any of them.

- **Marketplace sync:** OLX to WooCommerce over OAuth 2.0, with a one-click sync button for non-technical staff
- **Courier shipments:** AWB generation on the FAN Courier API
- **Device price evaluator:** a WordPress plugin that prices phones by condition
- **AI valuation assistant:** WhatsApp messages routed by type in n8n, a local multimodal model for photos and voice notes, and gpt-oss-20b via Ollama for the estimate, all on one RTX 3090. Built and tested end to end.
- **IVR anti-bot gate:** a random two-digit code read by text-to-speech on every call, which ended a robocall attack on a client's call ads
- **Supplier ordering tool:** React + TypeScript on top of a Python PDF parser, turning a 600-product catalogue into orders
- **E-commerce store:** full MERN storefront and admin for a startup that didn't launch

## Toolbox

- **Linux & networking:** openSUSE Tumbleweed (daily), Ubuntu/Debian, Fedora · systemd, SELinux, firewalld · DNS, TCP/IP, TLS, SSH
- **Troubleshooting:** Wireshark, tcpdump, browser DevTools, Postman, cURL, Prometheus, Grafana
- **Infrastructure:** Docker, Coolify, Hetzner Cloud, Traefik, nginx, Cloudflare
- **Code & automation:** Python, bash, JavaScript/TypeScript, PostgreSQL, n8n
- **AI:** RAG, local inference with Ollama, MCP servers, agentic coding tools
- **Learning:** AWS (Cloud Practitioner), Kubernetes

## Contact

alex.mihnea21@gmail.com
