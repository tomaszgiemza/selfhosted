---
layout: default
title: Matomo
parent: Analityka webowa
nav_order: 2
description: "Najbardziej rozbudowana alternatywa dla Google Analytics. E-commerce, lejki, mapy cieplne i setki funkcji."
permalink: /analityka/matomo/
---

# 📈 Matomo

{: .highlight }
Najbardziej rozbudowana alternatywa dla Google Analytics. E-commerce, lejki, mapy cieplne i setki funkcji.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-3.0 |
| **Typ hostingu** | VPS/Docker/PHP |
| **Język** | PHP |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/matomo-org/matomo)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 512 MB |
| Dysk | 2 GB |
| Typ | VPS/Docker/PHP |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  matomo:
    image: matomo:latest
    container_name: matomo
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

Najbardziej rozbudowana alternatywa dla Google Analytics. E-commerce, lejki, mapy cieplne i setki funkcji.

**✅ Plusy:** Bogaty w funkcje, e-commerce, heatmaps, GDPR, podobny do GA

**❌ Minusy:** Cięższy, starszy UI, wymaga MySQL
