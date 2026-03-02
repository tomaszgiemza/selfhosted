---
layout: default
title: Padloc
parent: Menedżery haseł
nav_order: 3
description: "Nowoczesny, open-source menedżer haseł z eleganckim interfejsem. Obsługuje aplikacje mobilne i desktopowe."
permalink: /menedzery-hasel/padloc/
---

# 🔐 Padloc

{: .highlight }
Nowoczesny, open-source menedżer haseł z eleganckim interfejsem. Obsługuje aplikacje mobilne i desktopowe.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/padloc/padloc)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 256 MB |
| Dysk | 1 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  padloc:
    image: padloc/padloc:latest
    container_name: padloc
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

Nowoczesny, open-source menedżer haseł z eleganckim interfejsem. Obsługuje aplikacje mobilne i desktopowe.

**✅ Plusy:** Piękny UI, aplikacje mobilne, szyfrowanie E2E

**❌ Minusy:** Mniej popularny, mniejsza społeczność
