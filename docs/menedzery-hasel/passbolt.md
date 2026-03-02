---
layout: default
title: Passbolt
parent: Menedżery haseł
nav_order: 2
description: "Menedżer haseł stworzony z myślą o zespołach. Oparty na szyfrowaniu PGP, z rozszerzeniem do przeglądarki i API REST."
permalink: /menedzery-hasel/passbolt/
---

# 🔐 Passbolt

{: .highlight }
Menedżer haseł stworzony z myślą o zespołach. Oparty na szyfrowaniu PGP, z rozszerzeniem do przeglądarki i API REST.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | PHP |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/passbolt/passbolt_api)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 512 MB |
| Dysk | 2 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  passbolt:
    image: passbolt/passbolt:latest-ce
    container_name: passbolt
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

Menedżer haseł stworzony z myślą o zespołach. Oparty na szyfrowaniu PGP, z rozszerzeniem do przeglądarki i API REST.

**✅ Plusy:** Świetny dla zespołów, szyfrowanie PGP, REST API, rozszerzenie przeglądarki

**❌ Minusy:** Bardziej złożona instalacja, wymaga MariaDB
