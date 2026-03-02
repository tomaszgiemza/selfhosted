---
layout: default
title: Pangolin
parent: Reverse Proxy
nav_order: 5
description: "Tunelowany reverse proxy z panelem webowym. Eksponuje lokalne serwery przez VPS bez otwierania portów."
permalink: /reverse-proxy/pangolin/
---

# 🔀 Pangolin

{: .highlight }
Tunelowany reverse proxy z panelem webowym. Eksponuje lokalne serwery przez VPS bez otwierania portów.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go/Next.js |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/fosrl/pangolin)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 256 MB |
| Dysk | 1 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  pangolin:
    image: fosrl/pangolin:latest
    container_name: pangolin
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

Tunelowany reverse proxy z panelem webowym. Eksponuje lokalne serwery przez VPS bez otwierania portów.

**✅ Plusy:** Tunelowanie, panel webowy, SSO, nowoczesny, bez otwierania portów

**❌ Minusy:** Młody projekt, mniejsza społeczność
