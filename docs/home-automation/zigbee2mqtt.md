---
layout: default
title: Zigbee2MQTT
parent: Home Automation
nav_order: 5
description: "Most między urządzeniami Zigbee a MQTT. Pozwala używać urządzeń Zigbee bez chmury producenta."
permalink: /home-automation/zigbee2mqtt/
---

# 🏠 Zigbee2MQTT

{: .highlight }
Most między urządzeniami Zigbee a MQTT. Pozwala używać urządzeń Zigbee bez chmury producenta.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-3.0 |
| **Typ hostingu** | VPS/Docker/RPi |
| **Język** | Node.js |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 512 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/Koenkk/zigbee2mqtt)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 256 MB |
| Dysk | 512 MB |
| Typ | VPS/Docker/RPi |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  zigbee2mqtt:
    image: koenkk/zigbee2mqtt:latest
    container_name: zigbee2mqtt
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

Most między urządzeniami Zigbee a MQTT. Pozwala używać urządzeń Zigbee bez chmury producenta.

**✅ Plusy:** Brak chmury, 3000+ obsługiwanych urządzeń, integracja z HA i MQTT

**❌ Minusy:** Wymaga adaptera Zigbee (np. Sonoff Zigbee 3.0)
