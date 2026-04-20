# 🕵🏻 Loupe

**100% offline, single-file security analyser for suspicious files.**
No server, no uploads, no tracking — just drop a file and inspect it.


[![Try Loupe](https://img.shields.io/badge/▶_Try_it-loupe.tools-cyan?style=for-the-badge)](https://loupe.tools/)
[![Download](https://img.shields.io/badge/⬇_Download-latest-brightgreen?style=for-the-badge)](https://github.com/Loupe-tools/Loupe/releases/latest/download/loupe.html)

---

### Why Loupe?

SOC analysts, incident responders, and security-conscious users need a way to safely inspect suspicious files — without uploading them to third-party services or spinning up a sandbox. Loupe runs entirely in your browser; **nothing ever leaves your machine**.

- 🔒 **Zero network access** — strict CSP blocks all external requests
- 📄 **Single HTML file** — no install, no dependencies, works on any OS
- 🧬 **Broad format coverage** — Office, PDF, email, archives, PE/ELF/Mach-O, macOS (DMG/PKG/plist/AppleScript), browser extensions (CRX/XPI), MSIX/ClickOnce, certificates (X.509/PGP), forensics (EVTX/SQLite), scripts, images, and more
- 🎯 **Built-in YARA engine** — in-browser rule matching with **500+ default rules** across 20+ categories; drop in your own `.yar` files to extend
- 🔎 **IOC extraction** — URLs, IPs, emails, hostnames, domains, file/UNC paths, hashes (MD5/SHA-1/SHA-256), GUIDs, cert fingerprints, MAC addresses. Defanged and SafeLinked indicators refanged automatically
- 🪆 **Encoded payload drill-down** — Base64 / hex / gzip / zlib layers decoded recursively with full lineage
- 🧩 **VBA / macro analysis** — extracts, decodes, and syntax-highlights embedded macros; flags auto-exec entry points
- 📤 **Exports** — one-click Markdown brief for tickets/LLMs, plus STIX 2.1, MISP event JSON, and IOC JSON/CSV
- 🎨 **Six themes** — Light, Dark, Midnight OLED, Solarized, Mocha, Latte

---

### Quick Links

| | |
|---|---|
| 🔗 **Try online** | [loupe.tools](https://loupe.tools/) |
| 📦 **Download** | [Latest release](https://github.com/Loupe-tools/Loupe/releases/latest/download/loupe.html) |
| 📖 **Source code** | [Loupe-tools/Loupe](https://github.com/Loupe-tools/Loupe) |
| 📋 **Features** | [FEATURES.md](https://github.com/Loupe-tools/Loupe/blob/main/FEATURES.md) |
| 🔒 **Security model** | [SECURITY.md](https://github.com/Loupe-tools/Loupe/blob/main/SECURITY.md) |
| 🤝 **Contributing** | [CONTRIBUTING.md](https://github.com/Loupe-tools/Loupe/blob/main/CONTRIBUTING.md) |
| 📜 **License** | [MPL-2.0](https://github.com/Loupe-tools/Loupe/blob/main/LICENSE) |

---

<sub>Loupe is open source under the Mozilla Public License 2.0. Contributions, YARA rules, and format support suggestions are always welcome.</sub>
