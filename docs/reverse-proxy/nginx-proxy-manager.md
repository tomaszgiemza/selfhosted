---
layout: default
title: Nginx Proxy Manager
parent: Reverse Proxy
nav_order: 1
description: "Nginx z pięknym panelem webowym. Zarządzaj proxy, SSL (Let's Encrypt) i przekierowaniami przez GUI bez znajomości nginx."
permalink: /reverse-proxy/nginx-proxy-manager/
---

# 🔀 Nginx Proxy Manager

{: .highlight }
Nginx z pięknym panelem webowym. Zarządzaj proxy, SSL (Let's Encrypt) i przekierowaniami przez GUI bez znajomości nginx.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js/nginx |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/NginxProxyManager/nginx-proxy-manager)

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
  nginx-proxy-manager:
    image: jc21/nginx-proxy-manager:latest
    container_name: nginx-proxy-manager
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
**Moja ocena: 10/10**

Nginx z pięknym panelem webowym. Zarządzaj proxy, SSL (Let's Encrypt) i przekierowaniami przez GUI bez znajomości nginx.

**✅ Plusy:** GUI dla nginx, Let's Encrypt auto, łatwy, wildcard certs

**❌ Minusy:** Mniej elastyczny niż czysty nginx/Traefik
