---
layout: default
title: Emby
parent: Media
nav_order: 4
description: "Serwer mediów z bogatymi funkcjami. Wersja podstawowa darmowa, premium płatne. Dobra alternatywa dla Plex."
permalink: /media/emby/
---

# 🎬 Emby

{: .highlight }
Serwer mediów z bogatymi funkcjami. Wersja podstawowa darmowa, premium płatne. Dobra alternatywa dla Plex.

## O narzędziu

| | |
|---|---|
| **Licencja** | Proprietary |
| **Typ hostingu** | VPS/Docker |
| **Język** | C# |
| **Wymagania RAM** | 1 GB |
| **Dysk** | 5 GB + media |

## 🔗 Linki

- [Strona / GitHub](https://emby.media)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 1 GB |
| Dysk | 5 GB + media |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  emby:
    image: emby/embyserver:latest
    container_name: emby
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

Serwer mediów z bogatymi funkcjami. Wersja podstawowa darmowa, premium płatne. Dobra alternatywa dla Plex.

**✅ Plusy:** Bogaty w funkcje, Live TV, DVR

**❌ Minusy:** Część funkcji płatna, mniejsza społeczność niż Jellyfin
