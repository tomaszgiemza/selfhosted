---
layout: default
title: Plex
parent: Media
nav_order: 2
description: "Najpopularniejszy serwer mediów. Wymaga konta Plex, ale oferuje świetne aplikacje i funkcje społecznościowe."
permalink: /media/plex/
---

# 🎬 Plex

{: .highlight }
Najpopularniejszy serwer mediów. Wymaga konta Plex, ale oferuje świetne aplikacje i funkcje społecznościowe.

## O narzędziu

| | |
|---|---|
| **Licencja** | Proprietary |
| **Typ hostingu** | VPS/Docker |
| **Język** | C++ |
| **Wymagania RAM** | 2 GB |
| **Dysk** | 5 GB + media |

## 🔗 Linki

- [Strona / GitHub](https://www.plex.tv)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 2 GB |
| Dysk | 5 GB + media |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  plex:
    image: plexinc/pms-docker:latest
    container_name: plex
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

Najpopularniejszy serwer mediów. Wymaga konta Plex, ale oferuje świetne aplikacje i funkcje społecznościowe.

**✅ Plusy:** Świetne aplikacje, duża społeczność, synchronizacja offline

**❌ Minusy:** Wymaga konta, niektóre funkcje płatne, telemetria
