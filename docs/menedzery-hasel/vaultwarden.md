---
layout: default
title: Vaultwarden
parent: Menedżery haseł
nav_order: 1
description: "Nieoficjalny, lekki backend Bitwarden napisany w Rust. Kompatybilny ze wszystkimi oficjalnymi aplikacjami Bitwarden – mobilnymi, desktopowymi i rozszerzeniami przeglądarek."
permalink: /menedzery-hasel/vaultwarden/
---

# 🔐 Vaultwarden

{: .highlight }
Nieoficjalny, lekki backend Bitwarden napisany w Rust. Kompatybilny ze wszystkimi oficjalnymi aplikacjami Bitwarden – mobilnymi, desktopowymi i rozszerzeniami przeglądarek.

## O narzędziu

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | Rust |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/dani-garcia/vaultwarden)

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
  vaultwarden:
    image: vaultwarden/server:latest
    container_name: vaultwarden
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

Nieoficjalny, lekki backend Bitwarden napisany w Rust. Kompatybilny ze wszystkimi oficjalnymi aplikacjami Bitwarden – mobilnymi, desktopowymi i rozszerzeniami przeglądarek.

**✅ Plusy:** Bardzo lekki, działa na RPi, wszystkie funkcje premium za darmo, TOTP wbudowany

**❌ Minusy:** Wymaga HTTPS, nieoficjalny fork, baza SQLite wymaga backupu
