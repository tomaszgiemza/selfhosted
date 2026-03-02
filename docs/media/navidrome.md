---
layout: default
title: Navidrome
parent: Media
nav_order: 3
description: "Lekki serwer muzyczny kompatybilny z protokołem Subsonic. Doskonały do streamowania własnej biblioteki muzycznej."
permalink: /media/navidrome/
---

# 🎬 Navidrome

{: .highlight }
Lekki serwer muzyczny kompatybilny z protokołem Subsonic. Doskonały do streamowania własnej biblioteki muzycznej.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB + muzyka |

## 🔗 Linki

- [Strona / GitHub](https://github.com/navidrome/navidrome)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 256 MB |
| Dysk | 1 GB + muzyka |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  navidrome:
    image: deluan/navidrome:latest
    container_name: navidrome
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

Lekki serwer muzyczny kompatybilny z protokołem Subsonic. Doskonały do streamowania własnej biblioteki muzycznej.

**✅ Plusy:** Bardzo lekki, kompatybilny z Subsonic, piękny UI, szybki

**❌ Minusy:** Tylko muzyka, brak wideo
