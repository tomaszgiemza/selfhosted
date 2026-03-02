---
layout: default
title: Matrix / Synapse
parent: Komunikacja
nav_order: 1
description: "Zdecentralizowany protokół komunikacji. Synapse to najpopularniejszy serwer Matrix. Klient Element dostępny na wszystkich platformach."
permalink: /komunikacja/matrix-synapse/
---

# 💬 Matrix / Synapse

{: .highlight }
Zdecentralizowany protokół komunikacji. Synapse to najpopularniejszy serwer Matrix. Klient Element dostępny na wszystkich platformach.

## O narzędziu

| | |
|---|---|
| **Licencja** | Apache-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Python |
| **Wymagania RAM** | 1 GB |
| **Dysk** | 5 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/element-hq/synapse)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 1 GB |
| Dysk | 5 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  matrix-synapse:
    image: matrixdotorg/synapse:latest
    container_name: matrix-synapse
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

Zdecentralizowany protokół komunikacji. Synapse to najpopularniejszy serwer Matrix. Klient Element dostępny na wszystkich platformach.

**✅ Plusy:** Zdecentralizowany, E2E szyfrowanie, federacja, mosty do Slacka/Telegrama

**❌ Minusy:** Wysokie zużycie RAM, złożona konfiguracja
