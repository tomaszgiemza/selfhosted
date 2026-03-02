---
layout: default
title: Wallos
parent: Finanse
nav_order: 4
description: "Prosta aplikacja do śledzenia subskrypcji. Monitoruj wydatki na Spotify, Netflix, hosting i inne usługi."
permalink: /finanse/cashcash/
---

# 💰 Wallos

{: .highlight }
Prosta aplikacja do śledzenia subskrypcji. Monitoruj wydatki na Spotify, Netflix, hosting i inne usługi.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-3.0 |
| **Typ hostingu** | VPS/Docker/PHP |
| **Język** | PHP |
| **Wymagania RAM** | 128 MB |
| **Dysk** | 512 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/ellite/Wallos)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 128 MB |
| Dysk | 512 MB |
| Typ | VPS/Docker/PHP |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  cashcash:
    image: ellite/wallos:latest
    container_name: cashcash
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

Prosta aplikacja do śledzenia subskrypcji. Monitoruj wydatki na Spotify, Netflix, hosting i inne usługi.

**✅ Plusy:** Prosty, śledzenie subskrypcji, przypomnienia, lekki

**❌ Minusy:** Tylko subskrypcje, brak pełnego budżetowania
