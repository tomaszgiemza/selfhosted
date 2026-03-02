---
layout: default
title: OneDev
parent: Git / Hosting kodu
nav_order: 5
description: "All-in-one platforma DevOps z Git, CI/CD, issue trackerem i review kodu. Bogata w funkcje alternatywa dla GitHub."
permalink: /git/onedev/
---

# 🐙 OneDev

{: .highlight }
All-in-one platforma DevOps z Git, CI/CD, issue trackerem i review kodu. Bogata w funkcje alternatywa dla GitHub.

## O narzędziu

| | |
|---|---|
| **Licencja** | MIT |
| **Typ hostingu** | VPS/Docker |
| **Język** | Java |
| **Wymagania RAM** | 1 GB |
| **Dysk** | 2 GB + repo |

## 🔗 Linki

- [Strona / GitHub](https://github.com/theonedev/onedev)

## ⚙️ Wymagania

| Zasób | Wartość |
|-------|---------|
| RAM | 1 GB |
| Dysk | 2 GB + repo |
| Typ | VPS/Docker |

## 🐳 Szybki start (Docker)

```yaml
version: '3'
services:
  onedev:
    image: 1dev/server:latest
    container_name: onedev
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

All-in-one platforma DevOps z Git, CI/CD, issue trackerem i review kodu. Bogata w funkcje alternatywa dla GitHub.

**✅ Plusy:** Bogaty w funkcje, CI/CD wbudowane, code review, project management

**❌ Minusy:** Java (większe zużycie RAM), mniejsza społeczność
