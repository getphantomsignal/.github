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

[![PyPI](https://img.shields.io/pypi/v/phantomsignal?style=flat-square&color=ff7a45&logo=pypi&logoColor=white)](https://pypi.org/project/phantomsignal/)
[![PyPI Downloads](https://img.shields.io/pypi/dm/phantomsignal?style=flat-square&color=35d0ff&logo=pypi&logoColor=white)](https://pypi.org/project/phantomsignal/)
[![Stars](https://img.shields.io/github/stars/getphantomsignal/phantomsignal?style=flat-square&color=ff7a45&logo=github)](https://github.com/getphantomsignal/phantomsignal/stargazers)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-35d0ff?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![License](https://img.shields.io/badge/license-MIT-ff7a45?style=flat-square)](https://github.com/getphantomsignal/phantomsignal/blob/main/LICENSE)
[![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20macOS%20%7C%20Windows%20%7C%20Docker-a78bfa?style=flat-square)](https://github.com/getphantomsignal/phantomsignal)

```bash
pip install phantomsignal
phantomsignal scan <target>     # rich panel output — ports, DNS, tech, geo, anomalies
phantomsignal web               # launch the web console (Dark / Neon / Light)
```

A modular, plugin-driven OSINT platform with 46+ intelligence API integrations, covert low-and-slow scanning, a themeable web console, and full CLI support.

**Capabilities:** `web recon` · `network intelligence` · `people profiling` · `threat analysis` · `covert scan` · `export pipeline`

---

## What's New — v1.23.0

| | |
|---|---|
| 🎨 **Three switchable themes** | A theming system on semantic role tokens: **Dark** (deep-slate federal, default), **Neon** (deep-navy coral glow), and **Light** (clean, print-friendly). Segmented switch in the nav; persists and pre-paints. Every token validated to WCAG AA. |
| 📝 **Plain-language interface** | The web UI was rewritten from codenames to clear labels — Dashboard, New Scan, Scans, Profiler, Integrations — with Findings, Risk Score, and Data Sources throughout |
| 🔤 **Roboto + signal mark** | Roboto for UI text (tables/terminal/code stay monospace), a font-based `∿` signal glyph, and a PS-monogram favicon |
| 🖱️ **Clickable dashboard** | Stat cards are now links straight into the matching view |
| 🔄 **One-click re-scan** | Re-run any completed scan against the same target with its original profile, modules, and options |
| 📊 **Honest risk gradient** | The Risk Score meter runs a true green → amber → red ramp, so low reads green (safe) at a glance |

---

## Links

[phantomsignal.sh](https://phantomsignal.sh) · [GitHub](https://github.com/getphantomsignal/phantomsignal) · [PyPI](https://pypi.org/project/phantomsignal/) · [Changelog](https://github.com/getphantomsignal/phantomsignal/blob/main/CHANGELOG.md) · [Docs](https://github.com/getphantomsignal/phantomsignal/blob/main/docs/USAGE.md)

---

Security disclosures & research inquiries → `security@phantomsignal.sh`
