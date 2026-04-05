# OpenClaw Skills Collection

Agent skills for OpenClaw — your personal AI assistant.

## Skills

| Skill | Description |
|-------|-------------|
| [fal-api](./skills/fal-api/) | Fal.Ai Media Generation — Generate images, videos, and audio via fal.ai API (FLUX, SDXL, Whisper, etc.) |
| [liteparse](./skills/liteparse/) | Parse unstructured documents (PDF, DOCX, PPTX, XLSX, images) locally with LiteParse — fast, lightweight, no cloud dependencies. |
| [monochrome](./skills/monochrome/) | Browse and stream music from monochrome.tf (Tidal-based Hi-Fi streaming). Search artists, albums, tracks, and get streaming URLs. |
| [slickdeals](./skills/slickdeals/) | Search Slickdeals.net for deals, coupons, and promo codes. Find discounts on electronics, games, and more. |

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