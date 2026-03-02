---
layout: default
title: Psono
parent: Menedżery haseł
nav_order: 5
description: "Bezpieczny menedżer haseł dla firm z obsługą LDAP, SSO i dwuetapową weryfikacją. Klient webowy i rozszerzenie przeglądarki."
permalink: /menedzery-hasel/psono/
---

# 🔐 Psono

{: .highlight }
Bezpieczny menedżer haseł dla firm z obsługą LDAP, SSO i dwuetapową weryfikacją. Klient webowy i rozszerzenie przeglądarki.

## O narzędziu

| | |
|---|---|
| **Licencja** | Apache-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Python |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/psono/psono-server)

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
  psono:
    image: psono/psono-ce-server:latest
    container_name: psono
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
**Moja ocena: 7/10**

Bezpieczny menedżer haseł dla firm z obsługą LDAP, SSO i dwuetapową weryfikacją. Klient webowy i rozszerzenie przeglądarki.

**✅ Plusy:** LDAP, SSO, 2FA, REST API, firmowe funkcje

**❌ Minusy:** Bardziej złożona konfiguracja
