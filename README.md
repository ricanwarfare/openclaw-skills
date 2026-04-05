# OpenClaw Skills Collection

Agent skills for OpenClaw — your personal AI assistant.

**Browse all skills:** https://clawhub.ai/ricanwarfare/

## Skills

| Skill | Description |
|-------|-------------|
| [fal-api](./skills/fal-api/) | Fal.Ai Media Generation — Generate images, videos, and audio via fal.ai API (FLUX, SDXL, Whisper, etc.) |
| [liteparse](./skills/liteparse/) | Parse unstructured documents (PDF, DOCX, PPTX, XLSX, images) locally with LiteParse — fast, lightweight, no cloud dependencies. |
| [monochrome](./skills/monochrome/) | Browse and stream music from monochrome.tf (Tidal-based Hi-Fi streaming). Search artists, albums, tracks, and get streaming URLs. |
| [proxmox-complete](./skills/proxmox-complete/) | Comprehensive Proxmox VE management: power control, snapshots, backups, storage, tasks. Bash + Python scripts. |
| [qbittorrent](./skills/qbittorrent/) | Manage torrents with qBittorrent WebUI API. List, add, pause, resume, delete torrents. Monitor download progress and speed limits. |
| [slickdeals](./skills/slickdeals/) | Search Slickdeals.net for deals, coupons, and promo codes. Find discounts on electronics, games, and more. |
| [unifi-network](./skills/unifi-network/) | Query and monitor UniFi network via local gateway API. Devices, clients, health, DPI, alerts. Read-only and safe for monitoring. |

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