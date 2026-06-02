# DarkenAmber IT Tools

> **The IT toolkit that works without internet, servers, or trust.**

One HTML file. Open it. Use it. No npm. No cloud. No tracking. Ever.

```bash
open index.html
```

🌐 **[Live Demo](https://darkenamber.github.io/DarkenAmber-it-tools)** · ⭐ Star if useful · 🐛 [Report Bug](https://github.com/DarkenAmber/DarkenAmber-it-tools/issues)

---

## Why this exists

Every other tool either:
- Requires `npm install` + build pipeline
- Sends your data to a server
- Shows ads
- Needs an account

This doesn't. It's a single 440KB file that runs in any browser, on any machine, with no internet connection. Your passwords, keys, certificates, and configs never leave your device.

---

## What makes it different

Most toolkits have JSON formatters and Base64 encoders. This one also has:

| Tool | What it does |
|------|-------------|
| 📦 **Packet Analyzer** | Parse Ethernet/IP/TCP/UDP/ICMP/DNS from raw hex — no Wireshark needed |
| 🔀 **CIDR Aggregator** | Merge subnet lists into minimal CIDRs · export as Cisco ACL or iptables |
| ⚙️ **Config Diff** | Syntax-aware diff for Cisco IOS, Juniper, nginx, iptables configs |
| 🔗 **Cert Chain Builder** | Order & validate PEM certificate chains · detect expiry & breaks |
| 🛡️ **HTTP Headers Analyzer** | Grade A+–F · detect missing CSP/HSTS/X-Frame · actionable fixes |
| 🔒 **AES-GCM Encrypt** | Real AES-256-GCM via Web Crypto API · PBKDF2 key derivation |
| 🔐 **SSH Key Generator** | ECDSA P-256/P-384 · RSA 2048/4096 · OpenSSH authorized_keys format |
| 🌐 **SSL Cert Decoder** | Parse PEM · SANs · fingerprints · days remaining |

---

## All 36 tools

<details>
<summary>🛡️ Security (12)</summary>

- Password Generator — crypto.getRandomValues() · entropy meter · bulk
- AES Encrypt/Decrypt — AES-GCM 256-bit · PBKDF2 · offline
- RSA Key Generator — 1024/2048/4096-bit · OAEP & PSS · PEM
- SSH Key Generator — ECDSA P-256/P-384 · RSA · OpenSSH format
- File Hash Calculator — SHA-256/512/1 · drag & drop · verify
- SSL Certificate Decoder — PEM/X.509 · SANs · fingerprints
- HTTP Headers Analyzer — security grade · CSP/HSTS analysis
- PBKDF2 Key Derivation — iterations/hash/length · OWASP presets
- Email Masker — 4 mask levels · alias generator
- Entropy Calculator — Shannon entropy · frequency chart
- URL Encoder/Decoder — encodeURIComponent & encodeURI
- Security & Privacy — zero data collection guarantee

</details>

<details>
<summary>💻 Developer (9)</summary>

- JSON Formatter — format, minify, validate
- JWT Validator — header/payload · expiry · claims · algorithm info
- Hash Generator — MD5, SHA1, SHA256, SHA512
- UUID Generator — v4 · bulk up to 1000
- Base64 Encoder/Decoder — text & file
- Regex Tester — live matching · flags & patterns
- Timestamp Converter — Unix ↔ readable · timezone-aware
- Cron Builder — visual grid · human description · next 5 executions
- YAML/JSON/TOML Converter — bidirectional · Docker/Cargo examples

</details>

<details>
<summary>🌐 Networking (6)</summary>

- Packet Analyzer — Ethernet/IPv4/IPv6/TCP/UDP/ICMP/DNS/ARP
- CIDR Aggregator — merge subnets · Cisco ACL & iptables export
- Certificate Chain Builder — order & validate · expiry check
- IP Calculator — CIDR · subnet mask · binary
- Subnet Visualizer — IP ranges · subnetting guide
- MAC Lookup — vendor identification

</details>

<details>
<summary>📁 File & Text & Design (9)</summary>

- QR Generator — URL/WiFi/vCard/Email/SMS · PNG & SVG · custom colors
- Config Diff — Cisco/Juniper/nginx/iptables · syntax highlight · patch export
- Text Diff — side-by-side · color highlights
- CSV to JSON — delimiter options · header detection
- HEX Viewer — text ↔ hex
- Case Converter — camelCase · snake_case · kebab-case · and more
- Word Counter — words · chars · lines · reading time
- Color Converter — HEX ↔ RGB ↔ HSL
- Unit Converter — storage · temperature · length · weight · speed

</details>

---

## Quick start

```bash
# Option 1: Use online (no install)
open https://darkenamber.github.io/DarkenAmber-it-tools

# Option 2: Run locally
git clone https://github.com/DarkenAmber/DarkenAmber-it-tools.git
open index.html
```

That's it. No npm. No Python. No Docker.

---

## Security model

All crypto uses the browser's native **Web Crypto API** — the same engine used by your bank:

```
AES-GCM 256-bit      ← AES encryption
PBKDF2 / SHA-256     ← key derivation (100k+ iterations)
ECDSA / RSA-OAEP     ← RSA & SSH key generation
SubtleCrypto.digest  ← file hashing
getRandomValues()    ← password generation
```

**Zero external requests.** Verify: F12 → Network → use any tool → empty.  
The only exception: `qrcodejs` and `js-yaml` loaded once on first use.

---

## Tech

```
Single HTML file    ~440 KB
Lines of code       ~9800
Dependencies        0 (npm)
Build tools         0
External APIs       0
Frameworks          0
```

---

## Themes

**Dark** · **Light** · **Retro 8-bit** (Press Start 2P font, scanlines)

---

## License

MIT — fork it, modify it, ship it.

---

## Roadmap

- [ ] PCAP file viewer
- [ ] Keyboard shortcuts
- [ ] More languages (RU, AZ, ES)
- [ ] Export results (PDF, CSV)

---

## 🆓 Free. Forever.

No ads. No subscriptions. No "Pro" tier. No data selling.  
This tool is and will always be completely free and open source.

If it saved you time, consider supporting:

- ⭐ **Star on GitHub** — helps others find it
- 💬 **Share** — post in r/networking, r/netsec, r/devops, Hacker News
- ☕ **[Buy me a coffee](https://ko-fi.com/darkenamber)** — one-time support via Ko-fi
- 🎯 **[Support on Patreon](https://www.patreon.com/cw/DarkenAmber)** — $3/month membership

> Just an engineer from Baku 🇦🇿 building things as a hobby.  
> No pressure. The tools will always be free. 🙏

---

Made with ❤️ by **[DarkenAmber](https://github.com/DarkenAmber)**
