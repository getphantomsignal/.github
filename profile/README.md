# PHANTOM SIGNAL

```
 ██████╗ ██╗  ██╗ █████╗ ███╗  ██╗████████╗ ██████╗ ███╗  ███╗
 ██╔══██╗██║  ██║██╔══██╗████╗ ██║╚══██╔══╝██╔═══██╗████╗████║
 ██████╔╝███████║███████║██╔██╗██║   ██║   ██║   ██║██╔████╔██║
 ██╔═══╝ ██╔══██║██╔══██║██║╚████║   ██║   ██║   ██║██║╚██╔╝██║
 ██║     ██║  ██║██║  ██║██║ ╚███║   ██║   ╚██████╔╝██║ ╚═╝ ██║
 ╚═╝     ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚══╝   ╚═╝    ╚═════╝ ╚═╝     ╚═╝

 ███████╗██╗ ██████╗ ███╗  ██╗ █████╗ ██╗
 ██╔════╝██║██╔════╝ ████╗ ██║██╔══██╗██║
 ███████╗██║██║  ███╗██╔██╗██║███████║██║
 ╚════██║██║██║   ██║██║╚████║██╔══██║██║
 ███████║██║╚██████╔╝██║ ╚███║██║  ██║███████╗
 ╚══════╝╚═╝ ╚═════╝ ╚═╝  ╚══╝╚═╝  ╚═╝╚══════╝
```

> *"See everything. Leave no trace."*

Open-source OSINT intelligence framework for security researchers, penetration testers, and investigators. Combining web scraping, network reconnaissance, people intelligence, and threat analysis into a single platform.

---

## PhantomSignal — OSINT Intelligence Framework

[![PyPI](https://img.shields.io/pypi/v/phantomsignal?style=flat-square&color=b026ff&logo=pypi&logoColor=white)](https://pypi.org/project/phantomsignal/)
[![PyPI Downloads](https://img.shields.io/pypi/dm/phantomsignal?style=flat-square&color=00ff41&logo=pypi&logoColor=white)](https://pypi.org/project/phantomsignal/)
[![Stars](https://img.shields.io/github/stars/getphantomsignal/phantomsignal?style=flat-square&color=00ff41&logo=github)](https://github.com/getphantomsignal/phantomsignal/stargazers)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-00f3ff?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![License](https://img.shields.io/badge/license-MIT-00ff41?style=flat-square)](https://github.com/getphantomsignal/phantomsignal/blob/main/LICENSE)
[![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20macOS%20%7C%20Windows%20%7C%20Docker-b026ff?style=flat-square)](https://github.com/getphantomsignal/phantomsignal)

```bash
pip install phantomsignal
phantomsignal scan <target>     # rich panel output — ports, DNS, tech, geo, anomalies
phantomsignal web               # launch the Shadow Grid web UI
```

A modular, plugin-driven OSINT platform with 46+ intelligence API integrations, ghost mode scanning, cyberpunk web UI, and full CLI support.

**Capabilities:** `web recon` · `network intelligence` · `people profiling` · `threat analysis` · `ghost mode` · `export pipeline`

---

## What's New — v1.4.2

| | |
|---|---|
| 📡 **16 new intelligence APIs** | Social, identity, and threat intel now spans Twitch, Mastodon, Keybase, Gravatar, HackerNews, Tumblr, Flickr, Spotify, Steam, VK, Telegram, Discord, Facebook Graph, EmailRep, Intelligence X, and Abstract Phone — 46+ integrations total |
| 🔑 **Ghost Key invalid-key detection** | TEST button distinguishes a rejected key (HTTP 401/403) from a working-but-empty result — invalid keys show an amber `⚠ INVALID` badge instead of a false `✓ OK` |
| ⚡ **AlienVault OTX fix** | Section requests now run concurrently via `asyncio.gather` with an 8 s per-section cap, eliminating the consistent 30 s timeout on the `reputation` endpoint |
| 🔄 **WebSocket sync** | Server emits current scan progress to late-joining clients; polling fallback keeps results accurate on slow connections |
| 📦 **Export works out of the box** | Output defaults to `/tmp` — no config required after install. Override with `PHANTOMSIGNAL_EXPORT_DIR` or `--output` |
| 🛠️ **Clean async pipeline** | Module coroutines are created lazily, eliminating `RuntimeWarning: coroutine was never awaited` noise on every scan |

---

## Links

[phantomsignal.sh](https://phantomsignal.sh) · [GitHub](https://github.com/getphantomsignal/phantomsignal) · [PyPI](https://pypi.org/project/phantomsignal/) · [Changelog](https://github.com/getphantomsignal/phantomsignal/blob/main/CHANGELOG.md) · [Docs](https://github.com/getphantomsignal/phantomsignal/blob/main/docs/USAGE.md)

---

Security disclosures & research inquiries → `security@phantomsignal.sh`
