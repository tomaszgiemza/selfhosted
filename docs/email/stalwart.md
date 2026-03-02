---
layout: default
title: Stalwart Mail
parent: Email
nav_order: 5
description: "Nowoczesny serwer email napisany w Rust. SMTP, IMAP, JMAP w jednym procesie z minimalnym zużyciem zasobów."
permalink: /email/stalwart/
---

# 📧 Stalwart Mail

{: .highlight }
Nowoczesny serwer email napisany w Rust. SMTP, IMAP, JMAP w jednym procesie z minimalnym zużyciem zasobów.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Rust |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/stalwartlabs/mail-server)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 256 MB |
| Dysk | 2 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  stalwart:
    image: stalwartlabs/mail-server:latest
    container_name: stalwart
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

Nowoczesny serwer email napisany w Rust. SMTP, IMAP, JMAP w jednym procesie z minimalnym zużyciem zasobów.

**✅ Plusy:** Rust (bardzo wydajny), JMAP, wszystko w jednym, nowoczesny

**❌ Minusy:** Młodszy projekt, brak panelu webowego (webmail)
