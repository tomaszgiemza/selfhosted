---
layout: default
title: Syncthing
parent: Chmura plików
nav_order: 3
description: "P2P synchronizacja plików bez serwera centralnego. Pliki synchronizują się bezpośrednio między urządzeniami."
permalink: /chmura-plikow/syncthing/
---

# ☁️ Syncthing

{: .highlight }
P2P synchronizacja plików bez serwera centralnego. Pliki synchronizują się bezpośrednio między urządzeniami.

## O narzędziu

| | |
|---|---|
| **Licencja** | MPL-2.0 |
| **Typ hostingu** | VPS/Docker/Desktop |
| **Język** | Go |
| **Wymagania RAM** | 128 MB |
| **Dysk** | 512 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/syncthing/syncthing)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 128 MB |
| Dysk | 512 MB |
| Typ | VPS/Docker/Desktop |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  syncthing:
    image: syncthing/syncthing:latest
    container_name: syncthing
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

P2P synchronizacja plików bez serwera centralnego. Pliki synchronizują się bezpośrednio między urządzeniami.

**✅ Plusy:** P2P bez serwera, bardzo lekki, E2E szyfrowanie, działa wszędzie

**❌ Minusy:** Brak interfejsu webowego do przeglądania plików, wymaga klienta na każdym urządzeniu
