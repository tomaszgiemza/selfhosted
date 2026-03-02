---
layout: default
title: Gitea
parent: Git / Hosting kodu
nav_order: 1
description: "Lekka, szybka platforma Git podobna do GitHub. Zawiera Issues, Pull Requests, Actions i Pages."
permalink: /git/gitea/
---

# 🐙 Gitea

{: .highlight }
Lekka, szybka platforma Git podobna do GitHub. Zawiera Issues, Pull Requests, Actions i Pages.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB + repo |

## 🔗 Linki

- [Strona / GitHub](https://github.com/go-gitea/gitea)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 256 MB |
| Dysk | 1 GB + repo |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  gitea:
    image: gitea/gitea:latest
    container_name: gitea
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

Lekka, szybka platforma Git podobna do GitHub. Zawiera Issues, Pull Requests, Actions i Pages.

**✅ Plusy:** Bardzo lekki, szybki, podobny do GitHub, Actions, darmowy

**❌ Minusy:** Mniej funkcji niż GitLab
