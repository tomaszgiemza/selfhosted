---
layout: default
title: ownCloud Infinite Scale
parent: Chmura plików
nav_order: 4
description: "Przepisana wersja ownCloud w Go. Skalowalna platforma do przechowywania plików dla firm."
permalink: /chmura-plikow/owncloud/
---

# ☁️ ownCloud Infinite Scale

{: .highlight }
Przepisana wersja ownCloud w Go. Skalowalna platforma do przechowywania plików dla firm.

## O narzędziu

| | |
|---|---|
| **Licencja** | Apache-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 1 GB |
| **Dysk** | 2 GB + pliki |

## 🔗 Linki

- [Strona / GitHub](https://github.com/owncloud/ocis)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 1 GB |
| Dysk | 2 GB + pliki |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  owncloud:
    image: owncloud/ocis:latest
    container_name: owncloud
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

Przepisana wersja ownCloud w Go. Skalowalna platforma do przechowywania plików dla firm.

**✅ Plusy:** Wydajny (Go), skalowalna, dla firm, WebDAV

**❌ Minusy:** Mniej dojrzały niż Nextcloud, mniejsza społeczność
