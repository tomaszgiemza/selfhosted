---
layout: default
title: Immich
parent: Zdjęcia
nav_order: 1
description: "Najlepsza alternatywa dla Google Photos. Automatyczny backup ze smartfona, rozpoznawanie twarzy, wyszukiwanie AI."
permalink: /zdjecia/immich/
---

# 📷 Immich

{: .highlight }
Najlepsza alternatywa dla Google Photos. Automatyczny backup ze smartfona, rozpoznawanie twarzy, wyszukiwanie AI.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js/Dart |
| **Wymagania RAM** | 2 GB |
| **Dysk** | 2 GB + zdjęcia |

## 🔗 Linki

- [Strona / GitHub](https://github.com/immich-app/immich)

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
  immich:
    image: ghcr.io/immich-app/immich-server:release
    container_name: immich
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
**Moja ocena: 10/10**

Najlepsza alternatywa dla Google Photos. Automatyczny backup ze smartfona, rozpoznawanie twarzy, wyszukiwanie AI.

**✅ Plusy:** Aplikacja mobilna, backup auto, AI, rozpoznawanie twarzy, aktywny rozwój

**❌ Minusy:** Duże zużycie zasobów, alpha oznaczenie (ale bardzo stabilny)
