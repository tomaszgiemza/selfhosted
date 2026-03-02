---
layout: default
title: AppFlowy
parent: Task Manager
nav_order: 5
description: "Alternatywa dla Notion z lokalnym przechowywaniem danych. Dokumenty, bazy danych, kalendarze i Kanban."
permalink: /task-manager/AppFlowy/
---

# ✅ AppFlowy

{: .highlight }
Alternatywa dla Notion z lokalnym przechowywaniem danych. Dokumenty, bazy danych, kalendarze i Kanban.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Rust/Flutter |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/AppFlowy-IO/AppFlowy)

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
  AppFlowy:
    image: appflowyio/appflowy_client:latest
    container_name: AppFlowy
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

Alternatywa dla Notion z lokalnym przechowywaniem danych. Dokumenty, bazy danych, kalendarze i Kanban.

**✅ Plusy:** Alternatywa dla Notion, offline-first, piękny UI, aplikacje desktopowe

**❌ Minusy:** Wciąż w aktywnym rozwoju, niektóre funkcje niestabilne
