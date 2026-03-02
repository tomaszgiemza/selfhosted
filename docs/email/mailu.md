---
layout: default
title: Mailu
parent: Email
nav_order: 2
description: "Prosta i kompletna platforma email w Dockerze. Mniejsze wymagania niż Mailcow, prostszy setup."
permalink: /email/mailu/
---

# 📧 Mailu

{: .highlight }
Prosta i kompletna platforma email w Dockerze. Mniejsze wymagania niż Mailcow, prostszy setup.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Python |
| **Wymagania RAM** | 1 GB |
| **Dysk** | 5 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/Mailu/Mailu)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 1 GB |
| Dysk | 5 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  mailu:
    image: mailu/mailu:latest
    container_name: mailu
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

Prosta i kompletna platforma email w Dockerze. Mniejsze wymagania niż Mailcow, prostszy setup.

**✅ Plusy:** Prostszy niż Mailcow, mniej zasobów, webmail wbudowany

**❌ Minusy:** Mniej funkcji niż Mailcow, mniejsza społeczność
