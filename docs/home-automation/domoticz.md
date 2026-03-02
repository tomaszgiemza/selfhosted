---
layout: default
title: Domoticz
parent: Home Automation
nav_order: 3
description: "Lekki system automatyzacji domu napisany w C++. Działa świetnie na Raspberry Pi."
permalink: /home-automation/domoticz/
---

# 🏠 Domoticz

{: .highlight }
Lekki system automatyzacji domu napisany w C++. Działa świetnie na Raspberry Pi.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-3.0 |
| **Typ hostingu** | VPS/Docker/RPi |
| **Język** | C++ |
| **Wymagania RAM** | 128 MB |
| **Dysk** | 512 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/domoticz/domoticz)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 128 MB |
| Dysk | 512 MB |
| Typ | VPS/Docker/RPi |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  domoticz:
    image: domoticz/domoticz:latest
    container_name: domoticz
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

Lekki system automatyzacji domu napisany w C++. Działa świetnie na Raspberry Pi.

**✅ Plusy:** Bardzo lekki (C++), działa na RPi zero, Z-Wave, Zigbee

**❌ Minusy:** Starszy UI, mniejsza społeczność niż HA
