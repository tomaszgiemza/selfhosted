---
layout: default
title: Ackee
parent: Analityka webowa
nav_order: 5
description: "Analityka skupiona na prywatności z minimalistycznym UI. Anonimizacja danych i GraphQL API."
permalink: /analityka/counter/
---

# 📈 Ackee

{: .highlight }
Analityka skupiona na prywatności z minimalistycznym UI. Anonimizacja danych i GraphQL API.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 512 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/electerious/Ackee)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 256 MB |
| Dysk | 512 MB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  counter:
    image: electerious/ackee:latest
    container_name: counter
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

Analityka skupiona na prywatności z minimalistycznym UI. Anonimizacja danych i GraphQL API.

**✅ Plusy:** Prywatność, GraphQL API, minimalistyczny

**❌ Minusy:** Podstawowe funkcje, wymaga MongoDB
