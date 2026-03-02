---
layout: default
title: Ghostfolio
parent: Finanse
nav_order: 5
description: "Aplikacja do śledzenia portfela inwestycyjnego. Akcje, ETF, krypto, metale szlachetne – wszystko w jednym miejscu."
permalink: /finanse/lunchmoney/
---

# 💰 Ghostfolio

{: .highlight }
Aplikacja do śledzenia portfela inwestycyjnego. Akcje, ETF, krypto, metale szlachetne – wszystko w jednym miejscu.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js/Angular |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/ghostfolio/ghostfolio)

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
  lunchmoney:
    image: ghostfolio/ghostfolio:latest
    container_name: lunchmoney
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

Aplikacja do śledzenia portfela inwestycyjnego. Akcje, ETF, krypto, metale szlachetne – wszystko w jednym miejscu.

**✅ Plusy:** Portfel inwestycyjny, wiele klas aktywów, piękny UI, API

**❌ Minusy:** Tylko inwestycje, brak budżetowania
