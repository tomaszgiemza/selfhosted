---
layout: default
title: Jitsi Meet
parent: Komunikacja
nav_order: 5
description: "Darmowy serwer wideokonferencji bez konta. Alternatywa dla Zoom i Google Meet."
permalink: /komunikacja/jitsi/
---

# 💬 Jitsi Meet

{: .highlight }
Darmowy serwer wideokonferencji bez konta. Alternatywa dla Zoom i Google Meet.

## O narzędziu

| | |
|---|---|
| **Licencja** | Apache-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Java/JavaScript |
| **Wymagania RAM** | 2 GB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/jitsi/jitsi-meet)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 2 GB |
| Dysk | 2 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  jitsi:
    image: jitsi/web:latest
    container_name: jitsi
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

Darmowy serwer wideokonferencji bez konta. Alternatywa dla Zoom i Google Meet.

**✅ Plusy:** Brak konta wymagany, E2E szyfrowanie, nagrywanie, udostępnianie ekranu

**❌ Minusy:** Wymaga mocnego CPU przy dużych spotkaniach, złożona instalacja
