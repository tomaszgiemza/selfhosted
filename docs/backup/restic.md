---
layout: default
title: Restic
parent: Backup
nav_order: 2
description: "Nowoczesne narzędzie do backupu z szyfrowaniem i deduplikacją. Obsługuje S3, B2, SFTP, lokalny dysk i wiele innych."
permalink: /backup/restic/
---

# 💾 Restic

{: .highlight }
Nowoczesne narzędzie do backupu z szyfrowaniem i deduplikacją. Obsługuje S3, B2, SFTP, lokalny dysk i wiele innych.

## O narzędziu

| | |
|---|---|
| **Licencja** | BSD-2-Clause |
| **Typ hostingu** | VPS/Linux/Docker |
| **Język** | Go |
| **Wymagania RAM** | 256 MB |
| **Dysk** | zmienny |

## 🔗 Linki

- [Strona / GitHub](https://github.com/restic/restic)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 256 MB |
| Dysk | zmienny |
| Typ | VPS/Linux/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  restic:
    image: restic/restic:latest
    container_name: restic
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
**Moja ocena: 10/10**

Nowoczesne narzędzie do backupu z szyfrowaniem i deduplikacją. Obsługuje S3, B2, SFTP, lokalny dysk i wiele innych.

**✅ Plusy:** Szyfrowanie, deduplikacja, wiele backendów (S3, B2, SFTP), szybki

**❌ Minusy:** Tylko CLI (można użyć Autorestic jako wrapper)
