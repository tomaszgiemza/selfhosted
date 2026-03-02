---
layout: default
title: Uptime Kuma
parent: Monitorowanie
nav_order: 1
description: "Piękne narzędzie do monitorowania dostępności usług. Obsługuje HTTP, TCP, DNS, Docker i wiele innych. Alerty przez Telegram, email, Slack."
permalink: /monitorowanie/uptime-kuma/
---

# 📊 Uptime Kuma

{: .highlight }
Piękne narzędzie do monitorowania dostępności usług. Obsługuje HTTP, TCP, DNS, Docker i wiele innych. Alerty przez Telegram, email, Slack.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/louislam/uptime-kuma)

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
  uptime-kuma:
    image: louislam/uptime-kuma:latest
    container_name: uptime-kuma
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
**Moja ocena: 10/10**

Piękne narzędzie do monitorowania dostępności usług. Obsługuje HTTP, TCP, DNS, Docker i wiele innych. Alerty przez Telegram, email, Slack.

**✅ Plusy:** Świetny UI, wiele protokołów, alerty, strona statusowa, łatwa instalacja

**❌ Minusy:** Brak zaawansowanych metryk (tylko uptime)
