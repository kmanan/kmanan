### Manan

Founder, [Kryton Labs](https://krytonlabs.com). I ship products with AI agents. Read about my homelab, smart home, AI-journey here: [Tech Blog](https://beingmanan.com).

---

- [cyberprism.app](https://cyberprism.app) — Cybersecurity threat intel platform
- [spratt-skills](https://github.com/kmanan/spratt-skills) — Custom skills built for my family butler, Spratt, built on OpenClaw
- [cheap-openclaw](https://github.com/kmanan/cheap-openclaw) — several adjustments to OpenClaw to drastically reduce AI spend to run OpenClaw as my family butler
- [npm-mobile](https://github.com/kmanan/npm-mobile) ⭐ 75 — Nginx Proxy Manager dashboard
- [gethomepage](https://github.com/kmanan/gethomepage) ⭐ 17 — Homelab landing page for the homepage project
- [claude-setup](https://github.com/kmanan/claude-setup) — My Claude Code configuration to reduce interruptions

**Upstream Contributions**

- OpenClaw: [issue #77155](https://github.com/openclaw/openclaw/issues/77155) → [merged fix #77573](https://github.com/openclaw/openclaw/pull/77573) — `doctor --fix` wiping externalized plugins during v2026.5.2 migration
- Wanderlust - OpenClaw integration in printing-press-library: [merged PR #504](https://github.com/mvanhorn/printing-press-library/pull/504) — broadened `pp-wanderlust-goat` skill triggers so LLM routers invoke the CLI for city-wide place queries ("best coffee in Redmond"), not just "near me" anchored ones
- Instacart - OpenClaw integration in printing-press-library: [issue #501](https://github.com/mvanhorn/printing-press-library/issues/501) → [merged fix #539](https://github.com/mvanhorn/printing-press-library/pull/539) and [issue #546](https://github.com/mvanhorn/printing-press-library/issues/546) → [merged fix #563](https://github.com/mvanhorn/printing-press-library/pull/563) to fix location bugs that broke the plugin.
- Weather-goat OpenClaw integration in printing-press-library: [issue #502](https://github.com/mvanhorn/printing-press-library/issues/502) → [merged fix #541](https://github.com/mvanhorn/printing-press-library/pull/541) — `weather-goat-pp-cli geocoding` routing `/search` to `api.open-meteo.com` (404) instead of Open-Meteo's dedicated `geocoding-api.open-meteo.com` host
- feedparser ReDoS: [issue #562](https://github.com/kurtmckee/feedparser/issues/562) · [PoC](https://github.com/kmanan/feedparser-redos-poc) — CWE-1333 in `_sync_author_detail()`, CVE assignment in progress

