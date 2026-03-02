---
layout: default
title: Netdata
parent: Monitorowanie
nav_order: 4
description: "Monitoring w czasie rzeczywistym z automatycznym wykrywaniem usług. Piękny dashboard bez konfiguracji."
permalink: /monitorowanie/netdata/
---

# 📊 Netdata

{: .highlight }
Monitoring w czasie rzeczywistym z automatycznym wykrywaniem usług. Piękny dashboard bez konfiguracji.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | C |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/netdata/netdata)

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
  netdata:
    image: netdata/netdata:latest
    container_name: netdata
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

Monitoring w czasie rzeczywistym z automatycznym wykrywaniem usług. Piękny dashboard bez konfiguracji.

**✅ Plusy:** Zero konfiguracji, real-time, auto-discovery, lekki

**❌ Minusy:** Retencja danych limitowana w wersji darmowej
