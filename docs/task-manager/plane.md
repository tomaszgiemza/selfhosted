---
layout: default
title: Plane
parent: Task Manager
nav_order: 2
description: "Alternatywa dla Jira i Linear. Zarządzanie projektami z Issues, Cycles, Modules i Analytics."
permalink: /task-manager/plane/
---

# ✅ Plane

{: .highlight }
Alternatywa dla Jira i Linear. Zarządzanie projektami z Issues, Cycles, Modules i Analytics.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Python/Next.js |
| **Wymagania RAM** | 2 GB |
| **Dysk** | 5 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/makeplane/plane)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 2 GB |
| Dysk | 5 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  plane:
    image: makeplane/plane-backend:latest
    container_name: plane
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

Alternatywa dla Jira i Linear. Zarządzanie projektami z Issues, Cycles, Modules i Analytics.

**✅ Plusy:** Alternatywa dla Jira, Issues, Cycles, Analytics, nowoczesny UI

**❌ Minusy:** Duże wymagania zasobów, złożona instalacja
