---
layout: default
title: Umami
parent: Analityka webowa
nav_order: 1
description: "Prosta, lekka analityka webowa skupiona na prywatności. Piękny UI, brak ciasteczek, GDPR-friendly."
permalink: /analityka/umami/
---

# 📈 Umami

{: .highlight }
Prosta, lekka analityka webowa skupiona na prywatności. Piękny UI, brak ciasteczek, GDPR-friendly.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/umami-software/umami)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 256 MB |
| Dysk | 1 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  umami:
    image: ghcr.io/umami-software/umami:postgresql-latest
    container_name: umami
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

Prosta, lekka analityka webowa skupiona na prywatności. Piękny UI, brak ciasteczek, GDPR-friendly.

**✅ Plusy:** Piękny UI, bez ciasteczek, GDPR, lekki, wielostronicowy

**❌ Minusy:** Mniej funkcji niż Matomo, brak e-commerce tracking
