---
layout: default
title: WeKan
parent: Task Manager
nav_order: 4
description: "Klasyczna tablica Kanban podobna do Trello. Prosta, sprawdzona i bogata w funkcje."
permalink: /task-manager/wekan/
---

# ✅ WeKan

{: .highlight }
Klasyczna tablica Kanban podobna do Trello. Prosta, sprawdzona i bogata w funkcje.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/wekan/wekan)

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
  wekan:
    image: wekanteam/wekan:latest
    container_name: wekan
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

Klasyczna tablica Kanban podobna do Trello. Prosta, sprawdzona i bogata w funkcje.

**✅ Plusy:** Podobny do Trello, bogaty w funkcje, LDAP, REST API

**❌ Minusy:** Starszy UI, wymaga MongoDB
