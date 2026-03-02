---
layout: default
title: Firefly III
parent: Finanse
nav_order: 2
description: "Dojrzała aplikacja do zarządzania finansami osobistymi. Budżety, kategorie, raporty i import CSV."
permalink: /finanse/firefly-iii/
---

# 💰 Firefly III

{: .highlight }
Dojrzała aplikacja do zarządzania finansami osobistymi. Budżety, kategorie, raporty i import CSV.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker/PHP |
| **Język** | PHP/Laravel |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/firefly-iii/firefly-iii)

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
  firefly-iii:
    image: fireflyiii/core:latest
    container_name: firefly-iii
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

Dojrzała aplikacja do zarządzania finansami osobistymi. Budżety, kategorie, raporty i import CSV.

**✅ Plusy:** Dojrzały projekt, budżety, raporty, import, API, wielowalutowy

**❌ Minusy:** Starszy UI, złożona konfiguracja
