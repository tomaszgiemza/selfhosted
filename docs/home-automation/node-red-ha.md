---
layout: default
title: Node-RED + HA
parent: Home Automation
nav_order: 4
description: "Node-RED zintegrowany z Home Assistant. Wizualne tworzenie automatyzacji z zaawansowaną logiką."
permalink: /home-automation/node-red-ha/
---

# 🏠 Node-RED + HA

{: .highlight }
Node-RED zintegrowany z Home Assistant. Wizualne tworzenie automatyzacji z zaawansowaną logiką.

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
  node-red-ha:
    image: nodered/node-red:latest
    container_name: node-red-ha
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

Node-RED zintegrowany z Home Assistant. Wizualne tworzenie automatyzacji z zaawansowaną logiką.

**✅ Plusy:** Wizualny programming, zaawansowana logika, świetna integracja z HA

**❌ Minusy:** Wymaga Home Assistant, bardziej dla zaawansowanych
