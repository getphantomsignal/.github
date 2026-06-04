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

A modular, plugin-driven OSINT platform with 30+ intelligence API integrations, ghost mode scanning, cyberpunk web UI, and full CLI support.

**Capabilities:** `web recon` · `network intelligence` · `people profiling` · `threat analysis` · `ghost mode` · `export pipeline`

---

## What's New — v1.3.0

| | |
|---|---|
| 🖥️ **Rich CLI panels** | `phantomsignal scan <target>` renders module-specific panels — DNS records, port table with VERSION/BANNER/RISK, tech stack grade A–F, GeoIP/ASN, red anomaly callout |
| 🎯 **nmap integration** | Port scanner chains `nmap -sV -O` for full version detection and OS fingerprinting; falls back to pure-Python async prober automatically |
| 🌐 **Expanded port coverage** | 99 common ports by default (up from 56) — WinRM, Webmin, InfluxDB, Radmin, Kubernetes, Docker API, and more |
| 🌑 **Web UI parity** | Results page renders structured output per result type (port cards, DNS tables, security grade, TLS, geo flags) matching CLI panels |

---

## Links

[phantomsignal.sh](https://phantomsignal.sh) · [GitHub](https://github.com/getphantomsignal/phantomsignal) · [PyPI](https://pypi.org/project/phantomsignal/) · [Changelog](https://github.com/getphantomsignal/phantomsignal/blob/main/CHANGELOG.md) · [Docs](https://github.com/getphantomsignal/phantomsignal/blob/main/docs/USAGE.md)

---

Security disclosures & research inquiries → `security@phantomsignal.sh`
