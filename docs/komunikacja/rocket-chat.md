---
layout: default
title: Rocket.Chat
parent: Komunikacja
nav_order: 2
description: "Kompletna platforma komunikacji dla firm. Czat, wideokonferencje, udostępnianie plików i integracje."
permalink: /komunikacja/rocket-chat/
---

# 💬 Rocket.Chat

{: .highlight }
Kompletna platforma komunikacji dla firm. Czat, wideokonferencje, udostępnianie plików i integracje.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js |
| **Wymagania RAM** | 1 GB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/RocketChat/Rocket.Chat)

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
  rocket-chat:
    image: rocketchat/rocket.chat:latest
    container_name: rocket-chat
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

Kompletna platforma komunikacji dla firm. Czat, wideokonferencje, udostępnianie plików i integracje.

**✅ Plusy:** Bogaty w funkcje, wideo, integracje, aplikacje mobilne

**❌ Minusy:** Duże zużycie zasobów, wymaga MongoDB
