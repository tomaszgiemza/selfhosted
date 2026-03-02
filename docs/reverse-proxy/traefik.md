---
layout: default
title: Traefik
parent: Reverse Proxy
nav_order: 2
description: "Nowoczesny reverse proxy z automatycznym wykrywaniem kontenerów Docker. Auto-SSL, middleware i dashboard."
permalink: /reverse-proxy/traefik/
---

# 🔀 Traefik

{: .highlight }
Nowoczesny reverse proxy z automatycznym wykrywaniem kontenerów Docker. Auto-SSL, middleware i dashboard.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 128 MB |
| **Dysk** | 256 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/traefik/traefik)

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
  traefik:
    image: traefik:latest
    container_name: traefik
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
**Moja ocena: 9/10**

Nowoczesny reverse proxy z automatycznym wykrywaniem kontenerów Docker. Auto-SSL, middleware i dashboard.

**✅ Plusy:** Auto-discovery Docker, auto-SSL, middleware, lekki, potężny

**❌ Minusy:** Złożona konfiguracja dla początkujących, YAML/TOML config
