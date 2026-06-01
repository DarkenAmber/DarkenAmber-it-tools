# DarkenAmber IT Tools

**26 free, open-source IT & security tools in a single HTML file. No backend. No registration. Works offline.**

🌐 **Live Demo:** https://darkenamber.github.io/DarkenAmber-it-tools

---

## 🎯 Features

✅ **Single HTML file** — no dependencies, no build tools  
✅ **3 themes** — Dark, Light, Retro 8-bit  
✅ **localStorage** — saves all your inputs automatically  
✅ **Zero data collection** — nothing ever leaves your browser  
✅ **Copy buttons** — click to copy any result  
✅ **Works offline** — no internet required after first load  

---

## 🧰 Tools (26)

### 🌐 **Networking**
- **IP Calculator** — CIDR, subnet mask, binary, network details
- **Subnet Visualizer** — IP ranges, subnetting guide
- **MAC Lookup** — Vendor identification, multiple formats

### 💻 **Developer**
- **JSON Formatter** — Format, minify, validate, explore structure
- **Base64 Encoder/Decoder** — Text & file encoding
- **Hash Generator** — MD5, SHA1, SHA256, SHA512
- **Regex Tester** — Live matching with flags & patterns
- **JWT Validator** — Parse header, payload, check expiry, sub/iss/aud/kid claims
- **Timestamp Converter** — Unix ↔ readable dates, timezone-aware
- **UUID Generator** — v4 IDs, bulk up to 1000

### 📁 **File & Format**
- **QR Generator** — Text, URL, WiFi, vCard, Email, SMS · PNG & SVG export · custom colors
- **CSV to JSON** — Delimiter options, header detection
- **HEX Viewer** — Text ↔ hexadecimal conversion
- **Text Diff** — Side-by-side comparison, color highlights

### 🔤 **Text Tools**
- **Case Converter** — UPPERCASE, lowercase, camelCase, snake_case, kebab-case
- **Word Counter** — Words, characters, lines, paragraphs, reading time

### 🎨 **Design**
- **Color Converter** — HEX ↔ RGB ↔ HSL with palettes

### ⚖️ **Converters**
- **Unit Converter** — Storage, temperature, length, weight, time, speed

### 🛡️ **Security**
- **Password Generator** — Cryptographically secure · entropy meter · bulk generation
- **AES Encrypt/Decrypt** — AES-GCM 256-bit · PBKDF2 key derivation · browser-native
- **File Hash Calculator** — SHA-256, SHA-512, SHA-1 · drag & drop · hash verification
- **URL Encoder/Decoder** — encodeURIComponent & encodeURI modes · live stats
- **SSL Certificate Decoder** — PEM/X.509 parsing · validity · SANs · fingerprints
- **PBKDF2 Key Derivation** — Configurable iterations, hash, key length · OWASP presets
- **Email Masker** — 4 mask levels · alias generation · provider detection
- **Entropy Calculator** — Shannon entropy · frequency chart · randomness assessment
- **RSA Key Generator** — 1024/2048/4096-bit · OAEP & PSS · PEM export
- **Security & Privacy** — Zero data collection guarantee

---

## 🚀 Quick Start

**Option 1: Use Online**
```
https://darkenamber.github.io/DarkenAmber-it-tools
```

**Option 2: Download & Run Locally**
```bash
git clone https://github.com/DarkenAmber/DarkenAmber-it-tools.git
cd DarkenAmber-it-tools
open index.html
```

---

## 🔒 Security & Privacy

All cryptographic operations use the **Web Crypto API** — the browser's native, audited implementation:

| What | How |
|------|-----|
| AES Encryption | AES-GCM 256-bit |
| Key Derivation | PBKDF2 / SHA-256 / 100k+ iterations |
| RSA Keys | Generated locally, never transmitted |
| File Hashing | SHA-256/512/1 via SubtleCrypto |
| Password Generation | `crypto.getRandomValues()` |

**Verify yourself:** Open DevTools → Network tab → use any tool → you'll see **zero external requests** (except QR library on first use).

---

## 🎨 Themes

| Theme | Background | Accent |
|-------|-----------|--------|
| **Dark** (default) | `#0F0A05` | Amber |
| **Light** | `#B8B4AC` | Warm brown |
| **Retro** | Purple gradient + scanlines | Orange · Press Start 2P font |

---

## 💾 Data Storage

- All inputs saved to **localStorage** automatically
- **No server requests** — zero telemetry, zero tracking
- No cookies, no analytics, no ads
- **Clear All** button removes everything (theme choice kept)

---

## 🛠️ Tech Stack

- **HTML5 + CSS3 + Vanilla JavaScript**
- **Zero npm dependencies**, no build tools
- **~6000 lines**, **~277 KB** (single file)
- External: `qrcodejs` loaded on demand (QR Generator only)

---

## 📜 License

MIT License — free to fork, modify, redistribute.

---

## 🌟 Support

- ⭐ Star on GitHub
- 🐛 Report bugs via GitHub Issues
- 💡 Suggest features

---

## 🚀 Roadmap

- [ ] More languages (RU, AZ, ES...)
- [ ] Keyboard shortcuts
- [ ] Export results (PDF, CSV)
- [ ] Dark mode scheduling

---

Made with ❤️ by **DarkenAmber**

Part of the **DarkenAmber Ecosystem**:
- 🌐 [Web Tools](https://darkenamber.github.io/DarkenAmber-it-tools) (Free)
- 📱 Mobile Apps (iOS/Android)
- 🏠 Smart Home Projects
