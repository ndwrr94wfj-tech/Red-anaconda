# 🐍 Red Anaconda — OSINT Intelligence Suite

> Made by **azerkash** | For educational & research purposes only

![Version](https://img.shields.io/badge/version-3.2.0-red)
![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-Web%20%7C%20Mac%20%7C%20Windows-darkred)

---

## 🔍 What is Red Anaconda?

Red Anaconda is an open-source OSINT (Open Source Intelligence) tool that aggregates **publicly available information** from various sources. It is designed for **educational purposes**, security researchers, and professionals who need to gather intelligence from open sources legally.

---

## ⚡ Features

| Module | Description |
|--------|-------------|
| 👤 **Full Name OSINT** | Generates social media links, email patterns, Google Dorks, people search links |
| 🌐 **IP Lookup** | Real-time geolocation, ISP, ASN, country details, threat intel links |
| 🔍 **Domain / WHOIS** | Live DNS records (A, MX, NS, TXT, CNAME), SSL subdomains via crt.sh |
| 📞 **Phone** | Country detection, carrier lookup links, spam check |
| 🎭 **Username** | Checks 55+ platforms (GitHub, Twitter, Instagram, Reddit, TikTok...) |
| ✉ **Email** | Breach check links (HIBP, DeHashed), domain analysis |
| ⚡ **Google Dorks** | 20 auto-generated dork queries for any target |

---

## 🚀 Installation

### Option 1 — Run locally (Mac / Windows / Linux)
```bash
# 1. Clone the repo
git clone https://github.com/azerkash/red-anaconda.git

# 2. Open the file in your browser
open index.html        # Mac
start index.html       # Windows
xdg-open index.html    # Linux
```
No server needed. No dependencies. Just open the HTML file.

### Option 2 — GitHub Pages (online)
1. Fork this repo
2. Go to **Settings → Pages**
3. Select **Branch: main** → Save
4. Your site is live at `https://your-username.github.io/red-anaconda`

---

## 📁 Files

```
red-anaconda/
├── index.html     ← Main tool (everything in one file)
└── README.md      ← This file
```

---

## ⚠️ Legal Disclaimer

This tool is intended **strictly for educational and research purposes**.

- Only queries **publicly available** data sources
- Does **not** store, collect, or transmit any data
- All searches are performed **client-side** in your browser
- Always obtain **proper legal authorization** before investigating any individual
- The author is **not responsible** for any misuse

---

## 🛠️ Tech Stack

- Pure HTML / CSS / JavaScript (no frameworks, no dependencies)
- Public APIs: IP geolocation, Google DNS over HTTPS, crt.sh certificates
- Standalone single-file — works offline for most features

---

## 📜 License

MIT License — free to use, modify, and distribute with attribution.

---

*Red Anaconda — made by azerkash*
