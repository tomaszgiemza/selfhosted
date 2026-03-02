---
layout: default
title: Strapi
parent: CMS
nav_order: 3
description: "Headless CMS z REST i GraphQL API. Idealny do projektów JAMstack i aplikacji mobilnych."
permalink: /cms/strapi/
---

# 📝 Strapi

{: .highlight }
Headless CMS z REST i GraphQL API. Idealny do projektów JAMstack i aplikacji mobilnych.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js |
| **Wymagania RAM** | 1 GB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/strapi/strapi)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 1 GB |
| Dysk | 2 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  strapi:
    image: strapi/strapi:latest
    container_name: strapi
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

Headless CMS z REST i GraphQL API. Idealny do projektów JAMstack i aplikacji mobilnych.

**✅ Plusy:** Headless, REST+GraphQL, panel admin, elastyczny

**❌ Minusy:** Wymaga frontendu, bardziej dla deweloperów
