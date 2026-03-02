---
layout: default
title: Home Assistant
parent: Home Automation
nav_order: 1
description: "Najpopularniejsza platforma automatyzacji domu. Ponad 3000 integracji z urządzeniami IoT, smart TV, asystentami głosowymi."
permalink: /home-automation/home-assistant/
---

# 🏠 Home Assistant

{: .highlight }
Najpopularniejsza platforma automatyzacji domu. Ponad 3000 integracji z urządzeniami IoT, smart TV, asystentami głosowymi.

## O narzędziu

| | |
|---|---|
| **Licencja** | Apache-2.0 |
| **Typ hostingu** | VPS/Docker/RPi |
| **Język** | Python |
| **Wymagania RAM** | 1 GB |
| **Dysk** | 32 GB (SD) |

## 🔗 Linki

- [Strona / GitHub](https://github.com/home-assistant/core)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 1 GB |
| Dysk | 32 GB (SD) |
| Typ | VPS/Docker/RPi |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  home-assistant:
    image: ghcr.io/home-assistant/home-assistant:stable
    container_name: home-assistant
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

Najpopularniejsza platforma automatyzacji domu. Ponad 3000 integracji z urządzeniami IoT, smart TV, asystentami głosowymi.

**✅ Plusy:** 3000+ integracji, ogromna społeczność, lokalna prywatność, bardzo aktywny

**❌ Minusy:** Stroma krzywa uczenia, wymaga dedykowanego sprzętu dla najlepszych efektów
