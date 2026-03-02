---
layout: default
title: Airsonic-Advanced
parent: Media
nav_order: 5
description: "Fork Airsonic z licznymi usprawnieniami. Serwer muzyczny z obsługą Subsonic API i strumieniowaniem."
permalink: /media/airsonic/
---

# 🎬 Airsonic-Advanced

{: .highlight }
Fork Airsonic z licznymi usprawnieniami. Serwer muzyczny z obsługą Subsonic API i strumieniowaniem.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Java |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 1 GB + muzyka |

## 🔗 Linki

- [Strona / GitHub](https://github.com/airsonic-advanced/airsonic-advanced)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 512 MB |
| Dysk | 1 GB + muzyka |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  airsonic:
    image: airsonicadvanced/airsonic-advanced:latest
    container_name: airsonic
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

Fork Airsonic z licznymi usprawnieniami. Serwer muzyczny z obsługą Subsonic API i strumieniowaniem.

**✅ Plusy:** Subsonic API, aktywny fork, wiele klientów

**❌ Minusy:** Java (większe zużycie RAM), mniej aktywny od Navidrome
