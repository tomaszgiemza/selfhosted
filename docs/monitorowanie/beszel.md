---
layout: default
title: Beszel
parent: Monitorowanie
nav_order: 5
description: "Lekki system monitorowania serwerów z pięknym UI. Monitoruje CPU, RAM, dysk i sieć wielu serwerów z jednego miejsca."
permalink: /monitorowanie/beszel/
---

# 📊 Beszel

{: .highlight }
Lekki system monitorowania serwerów z pięknym UI. Monitoruje CPU, RAM, dysk i sieć wielu serwerów z jednego miejsca.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 128 MB |
| **Dysk** | 512 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/henrygd/beszel)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 128 MB |
| Dysk | 512 MB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  beszel:
    image: henrygd/beszel:latest
    container_name: beszel
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

Lekki system monitorowania serwerów z pięknym UI. Monitoruje CPU, RAM, dysk i sieć wielu serwerów z jednego miejsca.

**✅ Plusy:** Bardzo lekki, piękny UI, multi-server, prosty setup

**❌ Minusy:** Młody projekt, mniej funkcji niż Grafana
