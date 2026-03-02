---
layout: default
title: GitLab CE
parent: Git / Hosting kodu
nav_order: 3
description: "Kompletna platforma DevOps – Git, CI/CD, registry, monitoring. Standard w firmach."
permalink: /git/gitlab/
---

# 🐙 GitLab CE

{: .highlight }
Kompletna platforma DevOps – Git, CI/CD, registry, monitoring. Standard w firmach.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Ruby/Go |
| **Wymagania RAM** | 4 GB |
| **Dysk** | 10 GB + repo |

## 🔗 Linki

- [Strona / GitHub](https://github.com/gitlabhq/gitlabhq)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 4 GB |
| Dysk | 10 GB + repo |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  gitlab:
    image: gitlab/gitlab-ce:latest
    container_name: gitlab
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

Kompletna platforma DevOps – Git, CI/CD, registry, monitoring. Standard w firmach.

**✅ Plusy:** Kompletny DevOps, CI/CD, registry, kubernetes integration

**❌ Minusy:** Ogromne wymagania sprzętowe, złożona konfiguracja
