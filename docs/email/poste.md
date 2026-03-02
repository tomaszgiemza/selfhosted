---
layout: default
title: Poste.io
parent: Email
nav_order: 3
description: "Prosta platforma email z interfejsem webowym. Darmowa wersja wystarczy dla małych instalacji."
permalink: /email/poste/
---

# 📧 Poste.io

{: .highlight }
Prosta platforma email z interfejsem webowym. Darmowa wersja wystarczy dla małych instalacji.

## O narzędziu

| | |
|---|---|
| **Licencja** | Proprietary (free tier) |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 1 GB |
| **Dysk** | 5 GB |

## 🔗 Linki

- [Strona / GitHub](https://poste.io)

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
  poste:
    image: analogic/poste.io:latest
    container_name: poste
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

Prosta platforma email z interfejsem webowym. Darmowa wersja wystarczy dla małych instalacji.

**✅ Plusy:** Bardzo prosty setup, webmail, antispam, certyfikaty auto

**❌ Minusy:** Nie w pełni open-source, płatna wersja pro
