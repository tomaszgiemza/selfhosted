---
layout: default
title: FileBrowser
parent: Chmura plików
nav_order: 5
description: "Prosty, lekki menedżer plików przez przeglądarkę. Idealne rozwiązanie gdy potrzebujesz tylko dostępu do plików przez web."
permalink: /chmura-plikow/filebrowser/
---

# ☁️ FileBrowser

{: .highlight }
Prosty, lekki menedżer plików przez przeglądarkę. Idealne rozwiązanie gdy potrzebujesz tylko dostępu do plików przez web.

## O narzędziu

| | |
|---|---|
| **Licencja** | Apache-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Go |
| **Wymagania RAM** | 64 MB |
| **Dysk** | 256 MB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/filebrowser/filebrowser)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 64 MB |
| Dysk | 256 MB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  filebrowser:
    image: filebrowser/filebrowser:latest
    container_name: filebrowser
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

Prosty, lekki menedżer plików przez przeglądarkę. Idealne rozwiązanie gdy potrzebujesz tylko dostępu do plików przez web.

**✅ Plusy:** Ekstremalnie lekki, prosty, podgląd plików, udostępnianie

**❌ Minusy:** Brak synchronizacji, tylko przeglądanie/upload
