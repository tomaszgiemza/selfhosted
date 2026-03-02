---
layout: default
title: Pi-hole
parent: Ad Blocking
nav_order: 1
description: "Klasyczny sieciowy bloker reklam działający jako DNS sinkhole. Blokuje reklamy na wszystkich urządzeniach w sieci."
permalink: /ad-blocking/pi-hole/
---

# 🚫 Pi-hole

{: .highlight }
Klasyczny sieciowy bloker reklam działający jako DNS sinkhole. Blokuje reklamy na wszystkich urządzeniach w sieci.

## O narzędziu

| | |
|---|---|
| **Licencja** | EUPL-1.2 |
| **Typ hostingu** | VPS/Docker/RPi |
| **Język** | PHP/Python |
| **Wymagania RAM** | 128 MB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/pi-hole/pi-hole)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 128 MB |
| Dysk | 2 GB |
| Typ | VPS/Docker/RPi |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  pi-hole:
    image: pihole/pihole:latest
    container_name: pi-hole
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

Klasyczny sieciowy bloker reklam działający jako DNS sinkhole. Blokuje reklamy na wszystkich urządzeniach w sieci.

**✅ Plusy:** Klasyk, ogromna społeczność, listy blokowania, panel webowy, działa na RPi

**❌ Minusy:** Tylko DNS blocking, nie blokuje reklam YouTube
