---
layout: default
title: Zulip
parent: Komunikacja
nav_order: 4
description: "Unikalna platforma czatu z organizacją wątkową. Świetna dla dużych zespołów z dużą ilością rozmów."
permalink: /komunikacja/zulip/
---

# 💬 Zulip

{: .highlight }
Unikalna platforma czatu z organizacją wątkową. Świetna dla dużych zespołów z dużą ilością rozmów.

## O narzędziu

| | |
|---|---|
| **Licencja** | Apache-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Python |
| **Wymagania RAM** | 2 GB |
| **Dysk** | 5 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/zulip/zulip)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 2 GB |
| Dysk | 5 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  zulip:
    image: zulip/docker-zulip:latest
    container_name: zulip
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

Unikalna platforma czatu z organizacją wątkową. Świetna dla dużych zespołów z dużą ilością rozmów.

**✅ Plusy:** Unikalny model wątków, potężne wyszukiwanie, archiwum

**❌ Minusy:** Wysoka krzywa uczenia, duże wymagania
