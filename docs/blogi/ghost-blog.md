---
layout: default
title: Ghost
parent: Platformy blogowe
nav_order: 1
description: "Nowoczesna platforma blogowa z wbudowanym newsletterem i subskrypcjami. Szybka, SEO-friendly."
permalink: /blogi/ghost-blog/
---

# ✍️ Ghost

{: .highlight }
Nowoczesna platforma blogowa z wbudowanym newsletterem i subskrypcjami. Szybka, SEO-friendly.

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
  ghost-blog:
    image: ghost:latest
    container_name: ghost-blog
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

Nowoczesna platforma blogowa z wbudowanym newsletterem i subskrypcjami. Szybka, SEO-friendly.

**✅ Plusy:** Newsletter, subskrypcje, szybki, SEO, Markdown, piękny edytor

**❌ Minusy:** Mniejszy ekosystem niż WordPress
