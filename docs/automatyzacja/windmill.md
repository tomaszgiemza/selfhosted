---
layout: default
title: Windmill
parent: Automatyzacja
nav_order: 5
description: "Platforma do tworzenia skryptów, workflow i aplikacji wewnętrznych. Obsługuje Python, TypeScript, Go, Bash."
permalink: /automatyzacja/windmill/
---

# ⚙️ Windmill

{: .highlight }
Platforma do tworzenia skryptów, workflow i aplikacji wewnętrznych. Obsługuje Python, TypeScript, Go, Bash.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go/TypeScript |
| **Wymagania RAM** | 1 GB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/windmill-labs/windmill)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 1 GB |
| Dysk | 2 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  windmill:
    image: ghcr.io/windmill-labs/windmill:main
    container_name: windmill
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

Platforma do tworzenia skryptów, workflow i aplikacji wewnętrznych. Obsługuje Python, TypeScript, Go, Bash.

**✅ Plusy:** Wiele języków, skrypty, workflow, aplikacje wewnętrzne

**❌ Minusy:** Bardziej zaawansowany, wymaga wiedzy programistycznej
