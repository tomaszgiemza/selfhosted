---
layout: default
title: Vikunja
parent: Task Manager
nav_order: 1
description: "Nowoczesna aplikacja do zarządzania zadaniami. Lista, Kanban, Gantt, kalendarze – wszystko w jednym."
permalink: /task-manager/vikunja/
---

# ✅ Vikunja

{: .highlight }
Nowoczesna aplikacja do zarządzania zadaniami. Lista, Kanban, Gantt, kalendarze – wszystko w jednym.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/go-vikunja/vikunja)

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
  vikunja:
    image: vikunja/vikunja:latest
    container_name: vikunja
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

Nowoczesna aplikacja do zarządzania zadaniami. Lista, Kanban, Gantt, kalendarze – wszystko w jednym.

**✅ Plusy:** Listy, Kanban, Gantt, kalendarze, aplikacje mobilne, lekki

**❌ Minusy:** Mniejsza społeczność niż Nextcloud Tasks
