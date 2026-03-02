---
layout: default
title: Node-RED
parent: Automatyzacja
nav_order: 4
description: "Wizualne narzędzie do programowania przepływów danych. Popularne w automatyzacji IoT i Home Assistant."
permalink: /automatyzacja/node-red/
---

# ⚙️ Node-RED

{: .highlight }
Wizualne narzędzie do programowania przepływów danych. Popularne w automatyzacji IoT i Home Assistant.

## O narzędziu

| | |
|---|---|
| **Licencja** | Apache-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/node-red/node-red)

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
  node-red:
    image: nodered/node-red:latest
    container_name: node-red
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

Wizualne narzędzie do programowania przepływów danych. Popularne w automatyzacji IoT i Home Assistant.

**✅ Plusy:** Ogromna społeczność, IoT, 1000+ node'ów, lekki

**❌ Minusy:** Bardziej dla deweloperów, mniej gotowych integracji SaaS
