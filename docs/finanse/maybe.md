---
layout: default
title: Maybe
parent: Finanse
nav_order: 3
description: "Nowoczesna aplikacja finansowa z śledzeniem inwestycji i net worth. Piękny, nowoczesny UI."
permalink: /finanse/maybe/
---

# 💰 Maybe

{: .highlight }
Nowoczesna aplikacja finansowa z śledzeniem inwestycji i net worth. Piękny, nowoczesny UI.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Ruby on Rails |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/maybe-finance/maybe)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 512 MB |
| Dysk | 2 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  maybe:
    image: ghcr.io/maybe-finance/maybe:latest
    container_name: maybe
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

Nowoczesna aplikacja finansowa z śledzeniem inwestycji i net worth. Piękny, nowoczesny UI.

**✅ Plusy:** Nowoczesny UI, inwestycje, net worth, aktywny rozwój

**❌ Minusy:** Młody projekt, mniej funkcji niż Firefly III
