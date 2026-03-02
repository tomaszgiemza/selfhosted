---
layout: default
title: Authentik
parent: Zarządzanie dostępem (SSO)
nav_order: 1
description: "Nowoczesna platforma SSO i zarządzania tożsamością. Obsługuje OAuth2, SAML, LDAP i proxy autoryzacji."
permalink: /zarzadzanie-haslem/authentik/
---

# 🔑 Authentik

{: .highlight }
Nowoczesna platforma SSO i zarządzania tożsamością. Obsługuje OAuth2, SAML, LDAP i proxy autoryzacji.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Python/Go |
| **Wymagania RAM** | 1 GB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/goauthentik/authentik)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 1 GB |
| Dysk | 2 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  authentik:
    image: ghcr.io/goauthentik/server:latest
    container_name: authentik
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

Nowoczesna platforma SSO i zarządzania tożsamością. Obsługuje OAuth2, SAML, LDAP i proxy autoryzacji.

**✅ Plusy:** Nowoczesny UI, OAuth2, SAML, LDAP, proxy auth, aktywny rozwój

**❌ Minusy:** Złożona konfiguracja dla początkujących, duże zużycie zasobów
