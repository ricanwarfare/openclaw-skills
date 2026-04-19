# OpenClaw Skills Collection

Agent skills for OpenClaw — your personal AI assistant.

**Browse all skills:** https://clawhub.ai/ricanwarfare/

## Skills

| Skill | Description |
|-------|-------------|
| [docsliteparse](./skills/docsliteparse/) | Parse unstructured documents (PDF, DOCX, PPTX, XLSX, images) locally with LiteParse — text extraction, JSON output with bounding boxes, batch processing, and page screenshots. No cloud dependencies. |
| [fal-api](./skills/fal-api/) | Fal.Ai Media Generation — Generate images, videos, and audio via fal.ai API (FLUX, SDXL, Whisper, etc.) |
| [ha-skill](./skills/ha-skill/) | Control Home Assistant entities via REST API. Supports climate (thermostat), light, switch, and sensor queries. Control lights, climate, switches, and monitor sensors. |
| [monochrome](./skills/monochrome/) | Browse and search music from monochrome.tf (Tidal-based Hi-Fi streaming). Search artists, albums, tracks, and get streaming URLs. High-fidelity audio streaming and discovery. |
| [proxmox-complete](./skills/proxmox-complete/) | Comprehensive Proxmox VE management via REST API: power control, snapshots, backups, storage, and tasks. Bash + Python scripts included. |
| [qbittorrent-skill](./skills/qbittorrent-skill/) | Manage torrents with qBittorrent WebUI API. List, add, pause, resume, delete torrents. Monitor download progress, speed limits, and qBittorrent stats. |
| [slickdeals](./skills/slickdeals/) | Search Slickdeals.net for deals, coupons, and promo codes. Find discounts on electronics, games, and more. |
| [unifi-network](./skills/unifi-network/) | Query and monitor UniFi network via local gateway API (Cloud Gateway Ultra / UniFi OS). Devices, clients, health, DPI, alerts. Read-only and safe for monitoring. |

## Installation

Skills can be installed via ClawHub:

```bash
clawhub install fal-api
```

Or cloned directly into your OpenClaw workspace:

```bash
git clone https://github.com/ricanwarfare/openclaw-skills.git
cp -r openclaw-skills/skills/* ~/.openclaw/workspace/skills/
```

## License

MIT