---
layout: default
title: Grafana
parent: Monitorowanie
nav_order: 2
description: "Potężna platforma do wizualizacji metryk i logów. Współpracuje z Prometheus, InfluxDB i setkami innych źródeł danych."
permalink: /monitorowanie/grafana/
---

# 📊 Grafana

{: .highlight }
Potężna platforma do wizualizacji metryk i logów. Współpracuje z Prometheus, InfluxDB i setkami innych źródeł danych.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go/TypeScript |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/grafana/grafana)

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
  grafana:
    image: grafana/grafana:latest
    container_name: grafana
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

Potężna platforma do wizualizacji metryk i logów. Współpracuje z Prometheus, InfluxDB i setkami innych źródeł danych.

**✅ Plusy:** Potężny, piękne dashboardy, tysiące wtyczek, standardem branżowym

**❌ Minusy:** Wymaga osobnego źródła danych (np. Prometheus)
