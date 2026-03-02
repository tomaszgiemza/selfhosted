---
layout: default
title: Nextcloud Photos
parent: Zdjęcia
nav_order: 5
description: "Moduł zdjęć wbudowany w Nextcloud. Jeśli już masz Nextcloud, to świetna opcja bez dodatkowej instalacji."
permalink: /zdjecia/nextcloud-photos/
---

# 📷 Nextcloud Photos

{: .highlight }
Moduł zdjęć wbudowany w Nextcloud. Jeśli już masz Nextcloud, to świetna opcja bez dodatkowej instalacji.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | PHP |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB + zdjęcia |

## 🔗 Linki

- [Strona / GitHub](https://github.com/nextcloud/photos)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 512 MB |
| Dysk | 2 GB + zdjęcia |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  nextcloud-photos:
    image: nextcloud:latest
    container_name: nextcloud-photos
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
**Moja ocena: 7/10**

Moduł zdjęć wbudowany w Nextcloud. Jeśli już masz Nextcloud, to świetna opcja bez dodatkowej instalacji.

**✅ Plusy:** Wbudowany w Nextcloud, backup mobilny, udostępnianie

**❌ Minusy:** Wymaga Nextcloud, słabszy niż Immich
