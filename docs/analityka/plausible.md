---
layout: default
title: Plausible
parent: Analityka webowa
nav_order: 3
description: "Elegancka, lekka analityka bez ciasteczek. Skrypt 1KB, bez samplowania danych, GDPR."
permalink: /analityka/plausible/
---

# 📈 Plausible

{: .highlight }
Elegancka, lekka analityka bez ciasteczek. Skrypt 1KB, bez samplowania danych, GDPR.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Elixir |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/plausible/analytics)

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
  plausible:
    image: plausible/analytics:latest
    container_name: plausible
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

Elegancka, lekka analityka bez ciasteczek. Skrypt 1KB, bez samplowania danych, GDPR.

**✅ Plusy:** Lekki skrypt, bez ciasteczek, piękny UI, bez samplowania

**❌ Minusy:** Mniej funkcji niż Matomo, wymaga Clickhouse
