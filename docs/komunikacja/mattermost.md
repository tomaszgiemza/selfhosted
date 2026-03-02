---
layout: default
title: Mattermost
parent: Komunikacja
nav_order: 3
description: "Alternatywa dla Slack dla firm. Kanały, wątki, integracje i rozbudowane API."
permalink: /komunikacja/mattermost/
---

# 💬 Mattermost

{: .highlight }
Alternatywa dla Slack dla firm. Kanały, wątki, integracje i rozbudowane API.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 1 GB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/mattermost/mattermost)

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
  mattermost:
    image: mattermost/mattermost-team-edition:latest
    container_name: mattermost
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

Alternatywa dla Slack dla firm. Kanały, wątki, integracje i rozbudowane API.

**✅ Plusy:** Podobny do Slack, szybki (Go), integracje, aplikacje mobilne

**❌ Minusy:** Część funkcji w płatnej wersji
