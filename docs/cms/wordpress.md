---
layout: default
title: WordPress
parent: CMS
nav_order: 1
description: "Najpopularniejszy CMS na świecie. Napędza ponad 40% internetu. Ogromny ekosystem wtyczek i motywów."
permalink: /cms/wordpress/
---

# 📝 WordPress

{: .highlight }
Najpopularniejszy CMS na świecie. Napędza ponad 40% internetu. Ogromny ekosystem wtyczek i motywów.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-2.0 |
| **Typ hostingu** | VPS/Shared/Docker |
| **Język** | PHP |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/WordPress/WordPress)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 256 MB |
| Dysk | 1 GB |
| Typ | VPS/Shared/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  wordpress:
    image: wordpress:latest
    container_name: wordpress
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

Najpopularniejszy CMS na świecie. Napędza ponad 40% internetu. Ogromny ekosystem wtyczek i motywów.

**✅ Plusy:** Ogromna społeczność, tysiące wtyczek, SEO, e-commerce (WooCommerce)

**❌ Minusy:** Wymaga regularnych aktualizacji bezpieczeństwa, może być wolny bez cache
