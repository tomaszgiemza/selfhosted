---
layout: default
title: Directus
parent: CMS
nav_order: 4
description: "Data platform i headless CMS. Interfejs do zarządzania dowolną bazą danych SQL z API REST i GraphQL."
permalink: /cms/directus/
---

# 📝 Directus

{: .highlight }
Data platform i headless CMS. Interfejs do zarządzania dowolną bazą danych SQL z API REST i GraphQL.

## O narzędziu

| | |
|---|---|
| **Licencja** | BSL 1.1 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/directus/directus)

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
  directus:
    image: directus/directus:latest
    container_name: directus
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

Data platform i headless CMS. Interfejs do zarządzania dowolną bazą danych SQL z API REST i GraphQL.

**✅ Plusy:** Dowolna baza SQL, piękny UI, REST+GraphQL, elastyczny

**❌ Minusy:** BSL licencja (nie w pełni OSS)
