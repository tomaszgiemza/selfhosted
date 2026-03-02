---
layout: default
title: Ghost
parent: CMS
nav_order: 2
description: "Nowoczesna platforma publikacyjna skupiona na prędkości i SEO. Idealna dla twórców treści i newsletterów."
permalink: /cms/ghost/
---

# 📝 Ghost

{: .highlight }
Nowoczesna platforma publikacyjna skupiona na prędkości i SEO. Idealna dla twórców treści i newsletterów.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/TryGhost/Ghost)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 512 MB |
| Dysk | 1 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  ghost:
    image: ghost:latest
    container_name: ghost
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

Nowoczesna platforma publikacyjna skupiona na prędkości i SEO. Idealna dla twórców treści i newsletterów.

**✅ Plusy:** Bardzo szybki, wbudowany newsletter, świetne SEO, piękny edytor

**❌ Minusy:** Mniej elastyczny niż WordPress, mniejszy ekosystem
