---
layout: default
title: Pocket ID
parent: Zarządzanie dostępem (SSO)
nav_order: 4
description: "Prosty dostawca OIDC z obsługą Passkeys. Minimalistyczna alternatywa dla Authentik dla małych instalacji."
permalink: /zarzadzanie-haslem/pocket-id/
---

# 🔑 Pocket ID

{: .highlight }
Prosty dostawca OIDC z obsługą Passkeys. Minimalistyczna alternatywa dla Authentik dla małych instalacji.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 128 MB |
| **Dysk** | 256 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/pocket-id/pocket-id)

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
  pocket-id:
    image: ghcr.io/pocket-id/pocket-id:latest
    container_name: pocket-id
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

Prosty dostawca OIDC z obsługą Passkeys. Minimalistyczna alternatywa dla Authentik dla małych instalacji.

**✅ Plusy:** Bardzo lekki, Passkeys, prosty, nowoczesny

**❌ Minusy:** Mniej funkcji niż Authentik, młody projekt
