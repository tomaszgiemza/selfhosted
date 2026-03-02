---
layout: default
title: Piwigo
parent: Zdjęcia
nav_order: 4
description: "Dojrzała platforma galerii zdjęć z bogatym ekosystemem wtyczek. Działa na klasycznym hostingu PHP."
permalink: /zdjecia/piwigo/
---

# 📷 Piwigo

{: .highlight }
Dojrzała platforma galerii zdjęć z bogatym ekosystemem wtyczek. Działa na klasycznym hostingu PHP.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-2.0 |
| **Typ hostingu** | VPS/PHP |
| **Język** | PHP |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB + zdjęcia |

## 🔗 Linki

- [Strona / GitHub](https://github.com/Piwigo/Piwigo)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 256 MB |
| Dysk | 1 GB + zdjęcia |
| Typ | VPS/PHP |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  piwigo:
    image: linuxserver/piwigo:latest
    container_name: piwigo
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

Dojrzała platforma galerii zdjęć z bogatym ekosystemem wtyczek. Działa na klasycznym hostingu PHP.

**✅ Plusy:** Wtyczki, działa na shared hostingu, dojrzały projekt

**❌ Minusy:** Starszy design, brak AI
