---
layout: default
title: Roundcube
parent: Email
nav_order: 4
description: "Klasyczny webmail client. Używany z osobnym serwerem IMAP/SMTP (Postfix+Dovecot)."
permalink: /email/roundcube/
---

# 📧 Roundcube

{: .highlight }
Klasyczny webmail client. Używany z osobnym serwerem IMAP/SMTP (Postfix+Dovecot).

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-3.0 |
| **Typ hostingu** | VPS/PHP |
| **Język** | PHP |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/roundcube/roundcubemail)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 256 MB |
| Dysk | 1 GB |
| Typ | VPS/PHP |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  roundcube:
    image: roundcube/roundcubemail:latest
    container_name: roundcube
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

Klasyczny webmail client. Używany z osobnym serwerem IMAP/SMTP (Postfix+Dovecot).

**✅ Plusy:** Klasyczny, sprawdzony, wtyczki, działa na shared hostingu

**❌ Minusy:** Wymaga osobnego serwera SMTP/IMAP, starszy UI
