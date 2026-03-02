---
layout: default
title: n8n
parent: Automatyzacja
nav_order: 1
description: "Potężne narzędzie do automatyzacji workflow z wizualnym edytorem. Ponad 400 integracji z popularnymi usługami."
permalink: /automatyzacja/n8n/
---

# ⚙️ n8n

{: .highlight }
Potężne narzędzie do automatyzacji workflow z wizualnym edytorem. Ponad 400 integracji z popularnymi usługami.

## O narzędziu

| | |
|---|---|
| **Licencja** | Fair-code |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/n8n-io/n8n)

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
  n8n:
    image: n8nio/n8n:latest
    container_name: n8n
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

Potężne narzędzie do automatyzacji workflow z wizualnym edytorem. Ponad 400 integracji z popularnymi usługami.

**✅ Plusy:** 400+ integracji, wizualny edytor, JavaScript w nodach, aktywna społeczność

**❌ Minusy:** Fair-code licencja (nie w pełni OSS), duże zużycie RAM przy wielu workflow
