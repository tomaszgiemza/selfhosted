---
layout: default
title: WireGuard
parent: VPN
nav_order: 1
description: "Nowoczesny, ultra-szybki protokół VPN wbudowany w jądro Linuxa. Standard w domowych VPN."
permalink: /vpn/wireguard/
---

# 🔒 WireGuard

{: .highlight }
Nowoczesny, ultra-szybki protokół VPN wbudowany w jądro Linuxa. Standard w domowych VPN.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-2.0 |
| **Typ hostingu** | VPS/Linux |
| **Język** | C |
| **Wymagania RAM** | 64 MB |
| **Dysk** | 256 MB |

## 🔗 Linki

- [Strona / GitHub](https://www.wireguard.com)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 64 MB |
| Dysk | 256 MB |
| Typ | VPS/Linux |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  wireguard:
    image: linuxserver/wireguard:latest
    container_name: wireguard
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
**Moja ocena: 10/10**

Nowoczesny, ultra-szybki protokół VPN wbudowany w jądro Linuxa. Standard w domowych VPN.

**✅ Plusy:** Ekstremalnie szybki, wbudowany w kernel, prostota, bezpieczny

**❌ Minusy:** Wymaga ręcznej konfiguracji (warto użyć wg-easy)
