<div align="center">

# 🌐 Proxy-Sorter

*Sort and manage proxy configurations by country — zero-config*

[![Stars](https://img.shields.io/github/stars/Surfboardv2ray/Proxy-sorter?style=for-the-badge&color=f5c542&logo=github)](https://github.com/Surfboardv2ray/Proxy-sorter/stargazers)
[![License](https://img.shields.io/badge/License-MIT-green?logo=open-source-initiative)](https://opensource.org/licenses/MIT)
[![Last Commit](https://img.shields.io/github/last-commit/Surfboardv2ray/Proxy-sorter?logo=github)](https://github.com/Surfboardv2ray/Proxy-sorter/commits/main)

</div>

## 🎯 What is this?

A **proxy configuration sorter and aggregator** that pulls proxy sources, filters by country/location, and outputs ready-to-use config files in multiple formats (Base64, Hiddify, etc.).

## ✨ Features

- 🌍 **Country filtering** — US-only, IR-only, or all countries
- 📦 **Multiple output formats** — Base64, Hiddify, WS+TLS, QUIC (Hysteria+Hy2+TUIC)
- 🔄 **Auto-updated** — GitHub Actions refreshes proxies on a schedule
- ⚡ **One-click subscribe** — Copy the subscription link directly into your client

## 📋 Subscription Links

### 🧧 All Countries

| Format | Link |
|--------|------|
| Base64 | `https://raw.githubusercontent.com/Surfboardv2ray/Proxy-sorter/main/submerge/converted.txt` |
| Hiddify | `https://raw.githubusercontent.com/Surfboardv2ray/Proxy-sorter/main/output/converted.txt` |

### 🧧 US Only

| Format | Link |
|--------|------|
| Base64 | `https://raw.githubusercontent.com/Surfboardv2ray/Proxy-sorter/main/submerge/US.txt` |
| Hiddify | `https://raw.githubusercontent.com/Surfboardv2ray/Proxy-sorter/main/output/US.txt` |

### 🧧 IR (Iran) Only

| Format | Link |
|--------|------|
| Base64 | `https://raw.githubusercontent.com/Surfboardv2ray/Proxy-sorter/main/submerge/IR.txt` |
| Hiddify | `https://raw.githubusercontent.com/Surfboardv2ray/Proxy-sorter/main/output/IR.txt` |

## 🔧 Advanced Options

### Light Sub (100 Random Proxies)
| Format | Link |
|--------|------|
| Base64 | `https://raw.githubusercontent.com/Surfboardv2ray/Proxy-sorter/main/selector/random64` |
| Hiddify | `https://raw.githubusercontent.com/Surfboardv2ray/Proxy-sorter/main/selector/random` |

### Sole WS+TLS Configs
| Format | Link |
|--------|------|
| Base64 | `https://raw.githubusercontent.com/Surfboardv2ray/Proxy-sorter/main/ws_tls/proxies/wstls_base64` |
| Hiddify | `https://raw.githubusercontent.com/Surfboardv2ray/Proxy-sorter/main/ws_tls/proxies/wstls` |

### QUIC Protocol (Hysteria + Hy2 + TUIC)
| Format | Link |
|--------|------|
| Base64 | `https://raw.githubusercontent.com/Surfboardv2ray/Proxy-sorter/main/custom/udp.txt` |

## 📖 Usage Guide

1. **Copy** a subscription link from the table above
2. **Open** your proxy client (V2Ray, Clash, Surffboard, etc.)
3. **Paste** the link in the subscription field
4. **Done!** Your client will auto-configure

## 🏗 Architecture

```
TGParse Sources → Proxy Scraper → Country Filter → Config Generator → Output Files
                                                              ↓
                                                  Base64 / Hiddify / WS+TLS / QUIC
```

## ⚠️ Disclaimer

> This project is for **learning purposes** only. Any issues arising from proxy usage are the sole responsibility of the user.

## ⭐ Star History

[![Star History](https://api.star-history.com/svg?repos=Surfboardv2ray/Proxy-sorter&type=Date)](https://star-history.com/#Surfboardv2ray/Proxy-sorter&Date)

---

README optimized with [Gingiris README Generator](https://gingiris.github.io/github-readme-generator/)
