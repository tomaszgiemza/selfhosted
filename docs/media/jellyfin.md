---
layout: default
title: Jellyfin
parent: Media
nav_order: 1
description: "W pełni darmowy i open-source serwer mediów. Alternatywa dla Plex bez konta, bez abonamentu i bez telemetrii."
permalink: /media/jellyfin/
---

# 🎬 Jellyfin

{: .highlight }
W pełni darmowy i open-source serwer mediów. Alternatywa dla Plex bez konta, bez abonamentu i bez telemetrii.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | C#/.NET |
| **Wymagania RAM** | 1 GB |
| **Dysk** | 5 GB + media |

## 🔗 Linki

- [Strona / GitHub](https://github.com/jellyfin/jellyfin)

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
  jellyfin:
    image: jellyfin/jellyfin:latest
    container_name: jellyfin
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

W pełni darmowy i open-source serwer mediów. Alternatywa dla Plex bez konta, bez abonamentu i bez telemetrii.

**✅ Plusy:** 100% darmowy, brak konta, hardware acceleration, aplikacje na TV

**❌ Minusy:** Transkodowanie 4K wymaga mocnego sprzętu, aplikacja iOS mniej dopracowana
