---
layout: default
title: Nextcloud
parent: Chmura plików
nav_order: 1
description: "Najpopularniejsza platforma do przechowywania plików. Zawiera edytor dokumentów, kalendarz, kontakty, czat i setki aplikacji."
permalink: /chmura-plikow/nextcloud/
---

# ☁️ Nextcloud

{: .highlight }
Najpopularniejsza platforma do przechowywania plików. Zawiera edytor dokumentów, kalendarz, kontakty, czat i setki aplikacji.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker/PHP |
| **Język** | PHP |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB + pliki |

## 🔗 Linki

- [Strona / GitHub](https://github.com/nextcloud/server)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 512 MB |
| Dysk | 2 GB + pliki |
| Typ | VPS/Docker/PHP |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  nextcloud:
    image: nextcloud:latest
    container_name: nextcloud
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

Najpopularniejsza platforma do przechowywania plików. Zawiera edytor dokumentów, kalendarz, kontakty, czat i setki aplikacji.

**✅ Plusy:** Ogromny ekosystem, edytor Office, kalendarz, kontakty, aplikacje mobilne

**❌ Minusy:** Może być wolny bez optymalizacji, złożona konfiguracja przy dużych instalacjach
