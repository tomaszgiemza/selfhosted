---
layout: default
title: OpenVPN
parent: VPN
nav_order: 4
description: "Klasyczny, sprawdzony protokół VPN. Szeroko wspierany przez routery i urządzenia sieciowe."
permalink: /vpn/openvpn/
---

# 🔒 OpenVPN

{: .highlight }
Klasyczny, sprawdzony protokół VPN. Szeroko wspierany przez routery i urządzenia sieciowe.

## O narzędziu

| | |
|---|---|
| **Licencja** | GPL-2.0 |
| **Typ hostingu** | VPS/Docker |
| **Język** | C |
| **Wymagania RAM** | 256 MB |
| **Dysk** | 1 GB |

## 🔗 Linki

- [Strona / GitHub](https://github.com/OpenVPN/openvpn)

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
  openvpn:
    image: kylemanna/openvpn:latest
    container_name: openvpn
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
**Moja ocena: 7/10**

Klasyczny, sprawdzony protokół VPN. Szeroko wspierany przez routery i urządzenia sieciowe.

**✅ Plusy:** Wszechobecne wsparcie, sprawdzony, konfigurowalne

**❌ Minusy:** Wolniejszy niż WireGuard, bardziej złożona konfiguracja
