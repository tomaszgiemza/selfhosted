---
layout: default
title: Prometheus
parent: Monitorowanie
nav_order: 3
description: "System monitorowania i baza danych szeregów czasowych. Standard w monitorowaniu kontenerów i Kubernetes."
permalink: /monitorowanie/prometheus/
---

# 📊 Prometheus

{: .highlight }
System monitorowania i baza danych szeregów czasowych. Standard w monitorowaniu kontenerów i Kubernetes.

## O narzędziu

| | |
|---|---|
| **Licencja** | Apache-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 5 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/prometheus/prometheus)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 512 MB |
| Dysk | 5 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  prometheus:
    image: prom/prometheus:latest
    container_name: prometheus
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

System monitorowania i baza danych szeregów czasowych. Standard w monitorowaniu kontenerów i Kubernetes.

**✅ Plusy:** Standard branżowy, alerting, PromQL, ogromna społeczność

**❌ Minusy:** Sam w sobie nie ma UI (potrzeba Grafany), złożona konfiguracja
