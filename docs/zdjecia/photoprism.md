---
layout: default
title: PhotoPrism
parent: Zdjęcia
nav_order: 2
description: "Zaawansowana galeria zdjęć z AI, rozpoznawaniem twarzy i map. Świetna jakość interfejsu."
permalink: /zdjecia/photoprism/
---

# 📷 PhotoPrism

{: .highlight }
Zaawansowana galeria zdjęć z AI, rozpoznawaniem twarzy i map. Świetna jakość interfejsu.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 2 GB |
| **Dysk** | 2 GB + zdjęcia |

## 🔗 Linki

- [Strona / GitHub](https://github.com/photoprism/photoprism)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 2 GB |
| Dysk | 2 GB + zdjęcia |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  photoprism:
    image: photoprism/photoprism:latest
    container_name: photoprism
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

Zaawansowana galeria zdjęć z AI, rozpoznawaniem twarzy i map. Świetna jakość interfejsu.

**✅ Plusy:** AI, mapy, rozpoznawanie twarzy, świetny UI

**❌ Minusy:** Wolniejszy indeks, część funkcji w płatnej wersji
