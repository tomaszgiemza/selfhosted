---
layout: default
title: Blocky
parent: Ad Blocking
nav_order: 3
description: "Szybki DNS proxy jako adblocker bez interfejsu graficznego. Konfiguracja przez YAML, idealne dla zaawansowanych."
permalink: /ad-blocking/blocky/
---

# 🚫 Blocky

{: .highlight }
Szybki DNS proxy jako adblocker bez interfejsu graficznego. Konfiguracja przez YAML, idealne dla zaawansowanych.

## O narzędziu

| | |
|---|---|
| **Licencja** | Apache-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 64 MB |
| **Dysk** | 256 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/0xERR0R/blocky)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 64 MB |
| Dysk | 256 MB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  blocky:
    image: spx01/blocky:latest
    container_name: blocky
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
**Moja ocena: 8/10**

Szybki DNS proxy jako adblocker bez interfejsu graficznego. Konfiguracja przez YAML, idealne dla zaawansowanych.

**✅ Plusy:** Ekstremalnie lekki, szybki, YAML config, DOH, DOT

**❌ Minusy:** Brak GUI, tylko dla zaawansowanych
