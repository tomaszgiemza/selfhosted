---
layout: default
title: Headscale
parent: VPN
nav_order: 3
description: "Self-hosted implementacja kontrolera Tailscale. Sieć mesh VPN bez centralnego serwera Tailscale."
permalink: /vpn/headscale/
---

# 🔒 Headscale

{: .highlight }
Self-hosted implementacja kontrolera Tailscale. Sieć mesh VPN bez centralnego serwera Tailscale.

## O narzędziu

| | |
|---|---|
| **Licencja** | BSD-3-Clause |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 128 MB |
| **Dysk** | 512 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/juanfont/headscale)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 128 MB |
| Dysk | 512 MB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  headscale:
    image: headscale/headscale:latest
    container_name: headscale
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

Self-hosted implementacja kontrolera Tailscale. Sieć mesh VPN bez centralnego serwera Tailscale.

**✅ Plusy:** Tailscale bez chmury, mesh VPN, łatwe połączenia między urządzeniami

**❌ Minusy:** Wymaga klienta Tailscale, złożona konfiguracja
