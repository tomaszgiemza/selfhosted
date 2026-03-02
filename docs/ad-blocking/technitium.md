---
layout: default
title: Technitium DNS
parent: Ad Blocking
nav_order: 4
description: "Pełnoprawny serwer DNS z blokowaniem reklam. Autorytatywny i rekurencyjny DNS z panelem webowym."
permalink: /ad-blocking/technitium/
---

# 🚫 Technitium DNS

{: .highlight }
Pełnoprawny serwer DNS z blokowaniem reklam. Autorytatywny i rekurencyjny DNS z panelem webowym.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | C# |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/TechnitiumSoftware/DnsServer)

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
  technitium:
    image: technitium/dns-server:latest
    container_name: technitium
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

Pełnoprawny serwer DNS z blokowaniem reklam. Autorytatywny i rekurencyjny DNS z panelem webowym.

**✅ Plusy:** Pełny serwer DNS, blokowanie, DOH/DOT, rekurencyjny

**❌ Minusy:** .NET runtime, bardziej złożony niż Pi-hole
