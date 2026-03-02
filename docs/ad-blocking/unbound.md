---
layout: default
title: Unbound
parent: Ad Blocking
nav_order: 5
description: "Rekurencyjny serwer DNS od NLnet Labs. Używany razem z Pi-hole jako upstream DNS dla pełnej prywatności."
permalink: /ad-blocking/unbound/
---

# 🚫 Unbound

{: .highlight }
Rekurencyjny serwer DNS od NLnet Labs. Używany razem z Pi-hole jako upstream DNS dla pełnej prywatności.

## O narzędziu

| | |
|---|---|
| **Licencja** | BSD-3-Clause |
| **Typ hostingu** | VPS/Docker |
| **Język** | C |
| **Wymagania RAM** | 64 MB |
| **Dysk** | 256 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/NLnetLabs/unbound)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 64 MB |
| Dysk | 256 MB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  unbound:
    image: mvance/unbound:latest
    container_name: unbound
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

Rekurencyjny serwer DNS od NLnet Labs. Używany razem z Pi-hole jako upstream DNS dla pełnej prywatności.

**✅ Plusy:** Lekki, bezpieczny, rekurencyjny (bez zewnętrznego DNS), DNSSEC

**❌ Minusy:** Brak GUI, tylko resolver – nie blokuje reklam sam w sobie
