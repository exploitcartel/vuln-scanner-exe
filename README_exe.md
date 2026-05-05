<div align="center">

```
██╗   ██╗██╗   ██╗██╗     ███╗   ██╗    ███████╗ ██████╗ █████╗ ███╗   ██╗███╗   ██╗███████╗██████╗
██║   ██║██║   ██║██║     ████╗  ██║    ██╔════╝██╔════╝██╔══██╗████╗  ██║████╗  ██║██╔════╝██╔══██╗
██║   ██║██║   ██║██║     ██╔██╗ ██║    ███████╗██║     ███████║██╔██╗ ██║██╔██╗ ██║█████╗  ██████╔╝
╚██╗ ██╔╝██║   ██║██║     ██║╚██╗██║    ╚════██║██║     ██╔══██║██║╚██╗██║██║╚██╗██║██╔══╝  ██╔══██╗
 ╚████╔╝ ╚██████╔╝███████╗██║ ╚████║    ███████║╚██████╗██║  ██║██║ ╚████║██║ ╚████║███████╗██║  ██║
  ╚═══╝   ╚═════╝ ╚══════╝╚═╝  ╚═══╝    ╚══════╝ ╚═════╝╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝
```

# 🛡️ Vulnerability Scanner Pro — Executable Release

**© Edison Plaku — EXPLOITCARTEL**

[![Release](https://img.shields.io/badge/Release-v3.0-red?style=for-the-badge&logo=github)](/)
[![Platform](https://img.shields.io/badge/Platform-Windows%2064bit-0078D6?style=for-the-badge&logo=windows)](/)
[![NoInstall](https://img.shields.io/badge/Installation-Not%20Required-22c55e?style=for-the-badge&logo=checkmarx)](/)
[![PyQt6](https://img.shields.io/badge/GUI-PyQt6-41CD52?style=for-the-badge&logo=qt)](/)

<br>

> **Download. Double-click. Scan.**
> No Python. No pip. No setup.

<br>

---

</div>

## ⚡ Quick Start

```
1. Download VulnScannerPro-v3.exe
2. Double-click
3. Enter target → Click SKANO
4. Report opens automatically in browser
```

**That's it.** No installation required.

---

## 📦 Download

| File | Size | Platform |
|------|------|----------|
| `VulnScannerPro-v3.exe` | ~50MB | Windows 10/11 x64 |

> ⬇️ **[Download Latest Release](../../releases/latest)**

---

## 🚀 What It Does

```
You provide:  http://target.com/
              │
              ├── 🕷️  Crawls all pages & forms
              ├── 🌐  DNS, subdomains, technology detection
              ├── 🖥️  Port scan + OS fingerprinting
              ├── 💉  XSS, Path Traversal, SSRF, Shellshock
              ├── 🔐  SSL/TLS + Heartbleed check
              ├── 🔑  Brute Force — Web / SSH / FTP
              └── 📊  Professional HTML + PDF report (auto-opens)
```

---

## 🗄️ Optional Features

These features require additional tools — **the exe works fine without them**.

| Feature | Install Command | What it adds |
|---------|----------------|--------------|
| **Full SQLi Map** | `pip install sqlmap` | Auto DB enumeration via SQLMap |
| **PDF WeasyPrint** | `pip install weasyprint` | Light theme PDF export |
| **PDF Playwright** | `pip install playwright` + `playwright install chromium` | Dark theme PDF export |
| **Live Map Tab** | `pip install PyQt6-WebEngine` | Interactive network map in GUI |

---

## ✨ Features (Built-in)

### 🔍 Reconnaissance
- Web Crawler — pages, forms, emails
- DNS Recon — SPF, DMARC, DKIM, WHOIS
- Subdomain Enumeration
- OS Fingerprinting — TTL-based
- CVE Lookup — automatic
- VirusTotal API integration
- HaveIBeenPwned integration

### 💉 Injection Testing
- SQL Injection — error, time-based, boolean-blind
- XSS Detection — reflected
- Path Traversal / LFI
- SSRF Probe
- HTTP Methods — PUT/DELETE/TRACE
- Shellshock CVE-2014-6271
- JWT Token Analysis

### 🖥️ Network
- Port Scanner — 25+ ports, multi-threaded
- Service Detection + Banner Grabbing
- Unauthenticated service checks (Redis, MongoDB, Elasticsearch)

### 🔐 SSL/TLS
- Certificate validity + expiry
- Heartbleed CVE-2014-0160
- TLS version detection

### 🔑 Brute Force
- Web login forms
- SSH (paramiko)
- FTP
- Custom wordlist support

### 📊 Professional Reports
- **Auto-opens** after every scan
- **HTML** — dark theme, interactive D3.js maps
- **PDF WeasyPrint** — light theme, print-ready *(optional)*
- **PDF Playwright** — dark theme screenshot *(optional)*
- Sitemap — hybrid tree + network mini-map
- Network Map — force-directed, drag/zoom/click
- SQLi Map — full DB structure section

---

## 🖼️ Interface

```
┌─────────────────────────────────────────────────────┐
│  🛡️  VULNERABILITY SCANNER PRO  v3.0                │
│  © Edison Plaku  |  Web+Network+SQLi+Crawler+...    │
├──────────┬──────────┬──────────┬───────────────────┤
│ 🔍 Scanner│ 🔌 Plugins│ 🗺️ Map   │ ⚙️ Settings       │
├──────────┴──────────┴──────────┴───────────────────┤
│ Target: [________________________] [▶ SKANO]        │
│ ████████████████████░░░░░░░░░░░░░  67%             │
│                                                     │
│  CRITICAL:2  HIGH:8  MEDIUM:5  LOW:3  INFO:32      │
│                                                     │
│ [Severity] [Category] [Title]           [Time]     │
│ CRITICAL   SQLi       SQL Injection...  10:42:15   │
│ HIGH       Network    Port 22 OPEN      10:42:20   │
│ ...                                                 │
└─────────────────────────────────────────────────────┘
```

---

## ⚙️ API Keys (Optional)

Configure in **Settings** tab:

| API | Cost | What it adds |
|-----|------|--------------|
| VirusTotal | Free | IP/domain reputation vs 70+ AV engines |
| HaveIBeenPwned | $3.50/mo | Domain breach history |

---

## ⚠️ Legal Disclaimer

```
EDUCATIONAL USE ONLY

✓ Only scan systems you OWN
✓ Only scan with EXPLICIT WRITTEN PERMISSION  
✗ Unauthorized scanning is ILLEGAL
✗ Author assumes NO LIABILITY for misuse
```

---

## 🔗 Source Code

> Source code is available in the private repository.
> This repo contains **executable releases only**.

---

<div align="center">

**© Edison Plaku 2026 — EXPLOITCARTEL**

*Security Research & Education*

[![GitHub](https://img.shields.io/badge/GitHub-exploitcartel-181717?style=for-the-badge&logo=github)](https://github.com/exploitcartel)

<br>

*Vulnerability Scanner Pro v3.0 — Educational Use Only*

</div>
