---
layout: default
title: Gogs
parent: Git / Hosting kodu
nav_order: 4
description: "Minimalistyczna platforma Git. Idealna na słaby sprzęt (Raspberry Pi). Poprzednik Gitea."
permalink: /git/gogs/
---

# 🐙 Gogs

{: .highlight }
Minimalistyczna platforma Git. Idealna na słaby sprzęt (Raspberry Pi). Poprzednik Gitea.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 128 MB |
| **Dysk** | 512 MB + repo |

## 🔗 Linki

- [Strona / GitHub](https://github.com/gogs/gogs)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 128 MB |
| Dysk | 512 MB + repo |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  gogs:
    image: gogs/gogs:latest
    container_name: gogs
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

Minimalistyczna platforma Git. Idealna na słaby sprzęt (Raspberry Pi). Poprzednik Gitea.

**✅ Plusy:** Ekstremalnie lekki, działa na RPi, prosty

**❌ Minusy:** Mniej aktywny rozwój niż Gitea/Forgejo
