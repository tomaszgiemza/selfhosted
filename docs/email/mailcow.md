---
layout: default
title: Mailcow
parent: Email
nav_order: 1
description: "Kompletny serwer email z panelem webowym. Zawiera Postfix, Dovecot, Rspamd, SOGo i zarządzanie przez GUI."
permalink: /email/mailcow/
---

# 📧 Mailcow

{: .highlight }
Kompletny serwer email z panelem webowym. Zawiera Postfix, Dovecot, Rspamd, SOGo i zarządzanie przez GUI.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | PHP/Go |
| **Wymagania RAM** | 3 GB |
| **Dysk** | 10 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/mailcow/mailcow-dockerized)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 3 GB |
| Dysk | 10 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  mailcow:
    image: mailcow/mailcow-dockerized
    container_name: mailcow
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

Kompletny serwer email z panelem webowym. Zawiera Postfix, Dovecot, Rspamd, SOGo i zarządzanie przez GUI.

**✅ Plusy:** Kompletny stack email, panel webowy, antispam, DKIM, aktualizacje auto

**❌ Minusy:** Duże wymagania RAM, wymaga VPS z dedykowanym IP
