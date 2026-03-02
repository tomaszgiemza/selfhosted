---
layout: default
title: AdGuard Home
parent: Ad Blocking
nav_order: 2
description: "Nowoczesna alternatywa dla Pi-hole. DNS-over-HTTPS, DNS-over-TLS, piękny UI i więcej opcji filtrowania."
permalink: /ad-blocking/adguard-home/
---

# 🚫 AdGuard Home

{: .highlight }
Nowoczesna alternatywa dla Pi-hole. DNS-over-HTTPS, DNS-over-TLS, piękny UI i więcej opcji filtrowania.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-3.0 |
| **Typ hostingu** | VPS/Docker/RPi |
| **Język** | Go |
| **Wymagania RAM** | 128 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/AdguardTeam/AdGuardHome)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 128 MB |
| Dysk | 1 GB |
| Typ | VPS/Docker/RPi |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  adguard-home:
    image: adguard/adguardhome:latest
    container_name: adguard-home
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

Nowoczesna alternatywa dla Pi-hole. DNS-over-HTTPS, DNS-over-TLS, piękny UI i więcej opcji filtrowania.

**✅ Plusy:** DOH, DOT, piękny UI, lekki, aktywny rozwój, rewrite DNS

**❌ Minusy:** Mniej list niż Pi-hole community
