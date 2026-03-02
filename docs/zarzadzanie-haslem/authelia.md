---
layout: default
title: Authelia
parent: Zarządzanie dostępem (SSO)
nav_order: 3
description: "Lekki serwer autoryzacji z 2FA dla reverse proxy. Idealny do zabezpieczenia aplikacji homelab za Nginx/Traefik."
permalink: /zarzadzanie-haslem/authelia/
---

# 🔑 Authelia

{: .highlight }
Lekki serwer autoryzacji z 2FA dla reverse proxy. Idealny do zabezpieczenia aplikacji homelab za Nginx/Traefik.

## O narzędziu

| | |
|---|---|
| **Licencja** | Apache-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 128 MB |
| **Dysk** | 512 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/authelia/authelia)

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
  authelia:
    image: authelia/authelia:latest
    container_name: authelia
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

Lekki serwer autoryzacji z 2FA dla reverse proxy. Idealny do zabezpieczenia aplikacji homelab za Nginx/Traefik.

**✅ Plusy:** Bardzo lekki, 2FA, integracja z nginx/traefik, prosty setup

**❌ Minusy:** Brak pełnego SSO (tylko auth proxy)
