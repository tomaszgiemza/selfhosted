---
layout: default
title: WriteFreely
parent: Platformy blogowe
nav_order: 2
description: "Minimalistyczna platforma blogowa skupiona na pisaniu. Obsługuje ActivityPub (federacja z Mastodon)."
permalink: /blogi/writefreely/
---

# ✍️ WriteFreely

{: .highlight }
Minimalistyczna platforma blogowa skupiona na pisaniu. Obsługuje ActivityPub (federacja z Mastodon).

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 128 MB |
| **Dysk** | 512 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/writefreely/writefreely)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 128 MB |
| Dysk | 512 MB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  writefreely:
    image: writeas/writefreely:latest
    container_name: writefreely
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

Minimalistyczna platforma blogowa skupiona na pisaniu. Obsługuje ActivityPub (federacja z Mastodon).

**✅ Plusy:** ActivityPub, minimalny, skupiony na pisaniu, lekki

**❌ Minusy:** Bardzo minimalistyczny, brak wielu funkcji CMS
