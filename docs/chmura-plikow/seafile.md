---
layout: default
title: Seafile
parent: Chmura plików
nav_order: 2
description: "Szybki i niezawodny serwer plików. Obsługuje szyfrowanie po stronie klienta i wersjonowanie plików."
permalink: /chmura-plikow/seafile/
---

# ☁️ Seafile

{: .highlight }
Szybki i niezawodny serwer plików. Obsługuje szyfrowanie po stronie klienta i wersjonowanie plików.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Python/C |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB + pliki |

## 🔗 Linki

- [Strona / GitHub](https://github.com/haiwen/seafile)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 512 MB |
| Dysk | 2 GB + pliki |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  seafile:
    image: seafileltd/seafile-mc:latest
    container_name: seafile
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

Szybki i niezawodny serwer plików. Obsługuje szyfrowanie po stronie klienta i wersjonowanie plików.

**✅ Plusy:** Bardzo szybki, szyfrowanie client-side, wersjonowanie, niezawodny

**❌ Minusy:** Mniej funkcji niż Nextcloud, mniejsza społeczność
