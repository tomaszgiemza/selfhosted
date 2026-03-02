---
layout: default
title: openHAB
parent: Home Automation
nav_order: 2
description: "Dojrzała platforma automatyzacji domu z setkami addons. Bardziej techniczna alternatywa dla Home Assistant."
permalink: /home-automation/openhab/
---

# 🏠 openHAB

{: .highlight }
Dojrzała platforma automatyzacji domu z setkami addons. Bardziej techniczna alternatywa dla Home Assistant.

## O narzędziu

| | |
|---|---|
| **Licencja** | EPL-2.0 |
| **Typ hostingu** | VPS/Docker/RPi |
| **Język** | Java |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/openhab/openhab-core)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 512 MB |
| Dysk | 2 GB |
| Typ | VPS/Docker/RPi |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  openhab:
    image: openhab/openhab:latest
    container_name: openhab
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
**Moja ocena: 7/10**

Dojrzała platforma automatyzacji domu z setkami addons. Bardziej techniczna alternatywa dla Home Assistant.

**✅ Plusy:** Dojrzały, addony, reguły, nie wymaga chmury

**❌ Minusy:** Java, stroma krzywa uczenia, mniej przyjazny UI
