---
layout: default
title: Zitadel
parent: Zarządzanie dostępem (SSO)
nav_order: 5
description: "Nowoczesna platforma tożsamości dla deweloperów. OpenID Connect, OAuth2, SAML z pięknym UI."
permalink: /zarzadzanie-haslem/zitadel/
---

# 🔑 Zitadel

{: .highlight }
Nowoczesna platforma tożsamości dla deweloperów. OpenID Connect, OAuth2, SAML z pięknym UI.

## O narzędziu

| | |
|---|---|
| **Licencja** | Apache-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/zitadel/zitadel)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 512 MB |
| Dysk | 2 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  zitadel:
    image: ghcr.io/zitadel/zitadel:latest
    container_name: zitadel
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

Nowoczesna platforma tożsamości dla deweloperów. OpenID Connect, OAuth2, SAML z pięknym UI.

**✅ Plusy:** Nowoczesny, dla deweloperów, wielodomenowy, aktywny

**❌ Minusy:** Złożona konfiguracja, wymaga CockroachDB lub PostgreSQL
