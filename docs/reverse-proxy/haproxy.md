---
layout: default
title: HAProxy
parent: Reverse Proxy
nav_order: 4
description: "Wysokowydajny load balancer i proxy. Standard w środowiskach produkcyjnych wymagających wysokiej dostępności."
permalink: /reverse-proxy/haproxy/
---

# 🔀 HAProxy

{: .highlight }
Wysokowydajny load balancer i proxy. Standard w środowiskach produkcyjnych wymagających wysokiej dostępności.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | C |
| **Wymagania RAM** | 128 MB |
| **Dysk** | 256 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/haproxy/haproxy)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 128 MB |
| Dysk | 256 MB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  haproxy:
    image: haproxy:latest
    container_name: haproxy
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

Wysokowydajny load balancer i proxy. Standard w środowiskach produkcyjnych wymagających wysokiej dostępności.

**✅ Plusy:** Ekstremalnie wydajny, HA, load balancing, health checks

**❌ Minusy:** Złożona konfiguracja, brak GUI, głównie dla zaawansowanych
