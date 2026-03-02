---
layout: default
title: Huginn
parent: Automatyzacja
nav_order: 3
description: "System agentów do monitorowania sieci i automatyzacji zadań. Może obserwować strony, wysyłać emaile i reagować na zdarzenia."
permalink: /automatyzacja/huginn/
---

# ⚙️ Huginn

{: .highlight }
System agentów do monitorowania sieci i automatyzacji zadań. Może obserwować strony, wysyłać emaile i reagować na zdarzenia.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Ruby |
| **Wymagania RAM** | 512 MB |
| **Dysk** | 2 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/huginn/huginn)

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
  huginn:
    image: ghcr.io/huginn/huginn:latest
    container_name: huginn
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

System agentów do monitorowania sieci i automatyzacji zadań. Może obserwować strony, wysyłać emaile i reagować na zdarzenia.

**✅ Plusy:** Bardzo elastyczny, agenci webowi, RSS, email

**❌ Minusy:** Stroma krzywa uczenia, starszy UI
