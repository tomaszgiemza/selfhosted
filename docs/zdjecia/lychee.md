---
layout: default
title: Lychee
parent: Zdjęcia
nav_order: 3
description: "Elegancka galeria zdjęć z pięknym interfejsem. Prosta instalacja, obsługa albumów i udostępniania."
permalink: /zdjecia/lychee/
---

# 📷 Lychee

{: .highlight }
Elegancka galeria zdjęć z pięknym interfejsem. Prosta instalacja, obsługa albumów i udostępniania.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/PHP |
| **Język** | PHP/Laravel |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB + zdjęcia |

## 🔗 Linki

- [Strona / GitHub](https://github.com/LycheeOrg/Lychee)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 256 MB |
| Dysk | 1 GB + zdjęcia |
| Typ | VPS/PHP |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  lychee:
    image: lycheeorg/lychee:latest
    container_name: lychee
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

Elegancka galeria zdjęć z pięknym interfejsem. Prosta instalacja, obsługa albumów i udostępniania.

**✅ Plusy:** Piękny UI, lekki, prosta instalacja, udostępnianie

**❌ Minusy:** Brak aplikacji mobilnej, brak AI
