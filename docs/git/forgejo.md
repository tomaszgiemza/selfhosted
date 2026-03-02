---
layout: default
title: Forgejo
parent: Git / Hosting kodu
nav_order: 2
description: "Fork Gitea skupiony na prawach społeczności i prywatności. W pełni kompatybilny z Gitea API."
permalink: /git/forgejo/
---

# 🐙 Forgejo

{: .highlight }
Fork Gitea skupiony na prawach społeczności i prywatności. W pełni kompatybilny z Gitea API.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB + repo |

## 🔗 Linki

- [Strona / GitHub](https://codeberg.org/forgejo/forgejo)

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
  forgejo:
    image: codeberg.org/forgejo/forgejo:latest
    container_name: forgejo
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

Fork Gitea skupiony na prawach społeczności i prywatności. W pełni kompatybilny z Gitea API.

**✅ Plusy:** Community-driven, kompatybilny z Gitea, aktywny rozwój

**❌ Minusy:** Młodszy od Gitea, mniejsza baza użytkowników
