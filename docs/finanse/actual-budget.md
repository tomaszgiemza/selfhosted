---
layout: default
title: Actual Budget
parent: Finanse
nav_order: 1
description: "Aplikacja budżetowa oparta na metodzie zero-sum budgeting (YNAB-like). Synchronizacja między urządzeniami, reguły automatyczne."
permalink: /finanse/actual-budget/
---

# 💰 Actual Budget

{: .highlight }
Aplikacja budżetowa oparta na metodzie zero-sum budgeting (YNAB-like). Synchronizacja między urządzeniami, reguły automatyczne.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Node.js |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/actualbudget/actual)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 256 MB |
| Dysk | 1 GB |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  actual-budget:
    image: actualbudget/actual-server:latest
    container_name: actual-budget
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

Aplikacja budżetowa oparta na metodzie zero-sum budgeting (YNAB-like). Synchronizacja między urządzeniami, reguły automatyczne.

**✅ Plusy:** YNAB-like, synchronizacja, reguły, import CSV/OFX, piękny UI

**❌ Minusy:** Wymaga nauczenia się metody zero-sum
