---
layout: default
title: wg-easy
parent: VPN
nav_order: 2
description: "WireGuard z pięknym panelem webowym. Zarządzaj klientami VPN przez przeglądarkę. Najłatwiejszy sposób na WireGuard."
permalink: /vpn/wg-easy/
---

# 🔒 wg-easy

{: .highlight }
WireGuard z pięknym panelem webowym. Zarządzaj klientami VPN przez przeglądarkę. Najłatwiejszy sposób na WireGuard.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js |
| **Wymagania RAM** | 128 MB |
| **Dysk** | 256 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/wg-easy/wg-easy)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 128 MB |
| Dysk | 256 MB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  wg-easy:
    image: ghcr.io/wg-easy/wg-easy:latest
    container_name: wg-easy
    restart: unless-stopped
    ports:
      - "8080:80"
    volumes:
      - ./data:/data
```

```bash
docker compose up -d
```

## 💬 Opinia

{: .note }
**Moja ocena: 9/10**

WireGuard z pięknym panelem webowym. Zarządzaj klientami VPN przez przeglądarkę. Najłatwiejszy sposób na WireGuard.

**✅ Plusy:** Prosty panel, QR kody dla klientów, statystyki, bardzo łatwy

**❌ Minusy:** Tylko WireGuard, brak zaawansowanych opcji
