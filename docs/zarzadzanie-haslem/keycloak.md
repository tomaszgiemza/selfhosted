---
layout: default
title: Keycloak
parent: Zarządzanie dostępem (SSO)
nav_order: 2
description: "Enterprise-grade platforma SSO od Red Hat. Standard w środowiskach firmowych z obsługą OAuth2, SAML i OpenID."
permalink: /zarzadzanie-haslem/keycloak/
---

# 🔑 Keycloak

{: .highlight }
Enterprise-grade platforma SSO od Red Hat. Standard w środowiskach firmowych z obsługą OAuth2, SAML i OpenID.

## O narzędziu

| | |
|---|---|
| **Licencja** | Apache-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Java |
| **Wymagania RAM** | 2 GB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/keycloak/keycloak)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 2 GB |
| Dysk | 2 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  keycloak:
    image: quay.io/keycloak/keycloak:latest
    container_name: keycloak
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

Enterprise-grade platforma SSO od Red Hat. Standard w środowiskach firmowych z obsługą OAuth2, SAML i OpenID.

**✅ Plusy:** Enterprise-grade, bardzo rozbudowany, standard branżowy

**❌ Minusy:** Duże zużycie RAM (Java), złożona konfiguracja
