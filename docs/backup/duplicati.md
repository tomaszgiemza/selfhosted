---
layout: default
title: Duplicati
parent: Backup
nav_order: 3
description: "Backup z GUI i harmonogramem. Obsługuje chmury (Google Drive, S3, OneDrive) i szyfrowanie AES."
permalink: /backup/duplicati/
---

# 💾 Duplicati

{: .highlight }
Backup z GUI i harmonogramem. Obsługuje chmury (Google Drive, S3, OneDrive) i szyfrowanie AES.

## O narzędziu

| | |
|---|---|
| **Licencja** | LGPL-2.1 |
| **Typ hostingu** | VPS/Docker/Desktop |
| **Język** | C# |
| **Wymagania RAM** | 512 MB |
| **Dysk** | zmienny |

## 🔗 Linki

- [Strona / GitHub](https://github.com/duplicati/duplicati)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 512 MB |
| Dysk | zmienny |
| Typ | VPS/Docker/Desktop |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  duplicati:
    image: linuxserver/duplicati:latest
    container_name: duplicati
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

Backup z GUI i harmonogramem. Obsługuje chmury (Google Drive, S3, OneDrive) i szyfrowanie AES.

**✅ Plusy:** GUI webowe, harmonogram, chmury, szyfrowanie, dla zwykłych użytkowników

**❌ Minusy:** .NET, czasem niestabilny przy dużych backupach
