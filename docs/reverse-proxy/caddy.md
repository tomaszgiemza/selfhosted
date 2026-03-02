---
layout: default
title: Caddy
parent: Reverse Proxy
nav_order: 3
description: "Serwer webowy i reverse proxy z automatycznym HTTPS. Najprostszy setup SSL – zero konfiguracji certyfikatów."
permalink: /reverse-proxy/caddy/
---

# 🔀 Caddy

{: .highlight }
Serwer webowy i reverse proxy z automatycznym HTTPS. Najprostszy setup SSL – zero konfiguracji certyfikatów.

## O narzędziu

| | |
|---|---|
| **Licencja** | Apache-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 128 MB |
| **Dysk** | 256 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/caddyserver/caddy)

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
  caddy:
    image: caddy:latest
    container_name: caddy
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

Serwer webowy i reverse proxy z automatycznym HTTPS. Najprostszy setup SSL – zero konfiguracji certyfikatów.

**✅ Plusy:** Auto-HTTPS zero-config, prosty Caddyfile, lekki, HTTP/3

**❌ Minusy:** Mniej popularny niż nginx, mniej wtyczek
