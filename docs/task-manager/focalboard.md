---
layout: default
title: Focalboard
parent: Task Manager
nav_order: 3
description: "Alternatywa dla Trello i Notion od Mattermost. Tablice Kanban, tabele i galerie."
permalink: /task-manager/focalboard/
---

# ✅ Focalboard

{: .highlight }
Alternatywa dla Trello i Notion od Mattermost. Tablice Kanban, tabele i galerie.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/mattermost/focalboard)

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
  focalboard:
    image: mattermost/focalboard:latest
    container_name: focalboard
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

Alternatywa dla Trello i Notion od Mattermost. Tablice Kanban, tabele i galerie.

**✅ Plusy:** Alternatywa dla Trello/Notion, Kanban, tabele, lekki

**❌ Minusy:** Mniej aktywny od czasu integracji z Mattermost
