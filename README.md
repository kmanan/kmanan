# Hi, I'm Manan 👋

🏗️ **Founder, [Kryton Labs](https://krytonlabs.com)** · 🤖 **Shipping products with AI agents** · 🛡️ **Cybersecurity**

![OpenClaw](https://img.shields.io/badge/-OpenClaw-FF6B35?style=flat-square&logo=openai&logoColor=white)
![Claude Code](https://img.shields.io/badge/-Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Home Assistant](https://img.shields.io/badge/-Home_Assistant-41BDF5?style=flat-square&logo=home-assistant&logoColor=white)
![Self-hosted](https://img.shields.io/badge/-Self--hosted-0078D4?style=flat-square&logo=proxmox&logoColor=white)

> Homelab tinkerer running an iMessage-first autonomous butler ([Spratt](https://github.com/kmanan/spratt-skills)) on OpenClaw, building a cybersecurity product company on the side, and writing about all of it at **[beingmanan.com](https://beingmanan.com)**.

## Start Here

- 🤖 **[spratt-skills](https://github.com/kmanan/spratt-skills)** — Custom OpenClaw skills powering my family's autonomous butler
- 💸 **[cheap-openclaw](https://github.com/kmanan/cheap-openclaw)** — 14 production-tested techniques to cut OpenClaw agent costs by 10x
- 🛜 **[npm-mobile](https://github.com/kmanan/npm-mobile)** ⭐ 76 — Nginx Proxy Manager on your phone (Flutter, iOS + Android)

## Upstream Contributions

Real fixes shipped upstream — bug hunting, root-cause analysis, and PRs against the tools I rely on every day.

### OpenClaw

- 🔧 **[issue #82904](https://github.com/openclaw/openclaw/issues/82904) → [merged fix #82986](https://github.com/openclaw/openclaw/pull/82986)** — Managed Chrome CDP launch was throwing self-contradicting failures on cold-start: `isChromeReachable` (HTTP-only probe) and `diagnoseChromeCdp` (full WebSocket + `Browser.getVersion`) disagreed about readiness. Reported with a 5-incident history, root cause traced through the built JS, and a proposed fix that shipped on `main`.
- 🔧 **[issue #77155](https://github.com/openclaw/openclaw/issues/77155) → [merged fix #77573](https://github.com/openclaw/openclaw/pull/77573)** — `doctor --fix` was wiping externalized plugins during the v2026.5.2 migration.

### printing-press-library (CLI library for agents)

- 🌍 **[merged PR #504](https://github.com/mvanhorn/printing-press-library/pull/504)** — Broadened `pp-wanderlust-goat` skill triggers so LLM routers invoke the CLI for city-wide place queries ("best coffee in Redmond"), not just "near me"-anchored ones.
- 🛒 **[issue #501](https://github.com/mvanhorn/printing-press-library/issues/501) → [fix #539](https://github.com/mvanhorn/printing-press-library/pull/539)** and **[issue #546](https://github.com/mvanhorn/printing-press-library/issues/546) → [fix #563](https://github.com/mvanhorn/printing-press-library/pull/563)** — Location bugs that broke the Instacart plugin.
- ☁️ **[issue #502](https://github.com/mvanhorn/printing-press-library/issues/502) → [fix #541](https://github.com/mvanhorn/printing-press-library/pull/541)** — `weather-goat-pp-cli` geocoding was routing `/search` to `api.open-meteo.com` (404) instead of Open-Meteo's dedicated `geocoding-api.open-meteo.com` host.

### feedparser

- 🪲 **[issue #562](https://github.com/kurtmckee/feedparser/issues/562)** · **[PoC](https://github.com/kmanan/feedparser-redos-poc)** — CWE-1333 ReDoS in `_sync_author_detail()`. CVE assignment in progress.

## GitHub Projects

### OpenClaw & Agent Tooling

- 🤖 **[spratt-skills](https://github.com/kmanan/spratt-skills)** — Custom skills for Spratt, my OpenClaw-powered family butler
- 💸 **[cheap-openclaw](https://github.com/kmanan/cheap-openclaw)** — 14 production-tested techniques to cut OpenClaw spend by 10x
- 🛠️ **[claude-setup](https://github.com/kmanan/claude-setup)** — My Claude Code config for running 20+ projects with zero friction

### Apps

- 🛜 **[npm-mobile](https://github.com/kmanan/npm-mobile)** ⭐ 76 — Nginx Proxy Manager on your phone (Flutter, iOS + Android)
- 📱 **[cyberprismapp](https://github.com/kmanan/cyberprismapp)** — Mobile companion for CyberPrism (iOS + Android)
- 🥦 **[snack-spinner](https://github.com/kmanan/snack-spinner)** — Site for *Snack Spinner: Kids Food Game*, my toddler healthy-eating app

### Homelab & Smart Home

- 🏠 **[gethomepage](https://github.com/kmanan/gethomepage)** ⭐ 17 — Custom landing page for the homepage project
- 🛎️ **[HA-announcements](https://github.com/kmanan/HA-announcements)** — Welcome-home announcements via Home Assistant, Aqara, Siri, and iPhone
- 📊 **[proxmox-glances](https://github.com/kmanan/proxmox-glances)** — Installing Glances on Proxmox without breaking everything
- 🚀 **[nodejsdeploy](https://github.com/kmanan/nodejsdeploy)** — Tiny stop / deploy / start script for PM2 apps
- 🔌 **[WindowsNAR](https://github.com/kmanan/WindowsNAR)** ⭐ 4 — Network adapter reset app for Windows

### Security Research

- 🪲 **[feedparser-redos-poc](https://github.com/kmanan/feedparser-redos-poc)** — Reproducer for CWE-1333 ReDoS in feedparser ≤ 6.0.11 (CVE assignment in progress)

## Products at Kryton Labs

Not on GitHub — closed-source products I build and ship at [krytonlabs.com](https://krytonlabs.com).

- 🛡️ **[CyberPrism](https://cyberprism.app)** — Mobile-first cybersecurity threat-intel platform
- 🧩 **[ArtFall](https://artfall.app)** — iOS puzzle game where stacking pieces reveals classic artworks
- 🤝 **[Team Exercises](https://teamexercises.app)** — AI-driven web platform for team-building activities
- 📈 **[Child Growth Chart](https://krytonlabs.com/childgrowth)** — Web app tracking kids' growth against health standards
- 🍎 **[DarwinMQTT](https://krytonlabs.com/darwinmqtt)** — macOS ↔ Home Assistant bridge over MQTT, privacy-first
- 🖼️ **[OpenGraph Resizer](https://opengraph.krytonlabs.com)** — Free tool to optimize images for social-media sharing
- 📺 **[Tech Reviews Hub](https://gadgets.krytonlabs.com)** — Gadget reviews aggregated from YouTube creators

## GitHub Activity

![GitHub Contribution Graph](https://ghchart.rshah.org/kmanan)

## Connect

- 🌐 **Blog** — [beingmanan.com](https://beingmanan.com)
- 🏢 **Company** — [krytonlabs.com](https://krytonlabs.com)
- 🐦 **X / Twitter** — [@manan](https://x.com/manan)
- 💼 **LinkedIn** — [in/manankakkar](https://www.linkedin.com/in/manankakkar)
