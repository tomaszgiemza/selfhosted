---
layout: default
title: Activepieces
parent: Automatyzacja
nav_order: 2
description: "Nowoczesna alternatywa dla Zapier w pełni open-source. Wizualny builder workflow z rosnącą liczbą integracji."
permalink: /automatyzacja/activepieces/
---

# ⚙️ Activepieces

{: .highlight }
Nowoczesna alternatywa dla Zapier w pełni open-source. Wizualny builder workflow z rosnącą liczbą integracji.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/activepieces/activepieces)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 512 MB |
| Dysk | 2 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  activepieces:
    image: activepieces/activepieces:latest
    container_name: activepieces
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

Nowoczesna alternatywa dla Zapier w pełni open-source. Wizualny builder workflow z rosnącą liczbą integracji.

**✅ Plusy:** MIT licencja, nowoczesny UI, aktywny rozwój

**❌ Minusy:** Mniej integracji niż n8n, młodszy projekt
