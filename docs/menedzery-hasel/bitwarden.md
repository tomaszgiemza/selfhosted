---
layout: default
title: Bitwarden / Vaultwarden
parent: Menedżery haseł
nav_order: 2
description: "Vaultwarden – lekki, open-source menedżer haseł kompatybilny z Bitwarden. Opinia, wymagania, konfiguracja Docker."
permalink: /menedzery-hasel/bitwarden/
---

# 🔑 Bitwarden / Vaultwarden

{: .highlight }
Najczęściej polecany menedżer haseł do self-hostingu – działa nawet na Raspberry Pi

## O narzędziu

Bitwarden to popularny open-source menedżer haseł. Do self-hostingu najlepiej użyć
**Vaultwarden** – nieoficjalnego, lżejszego backendu napisanego w Rust,
w pełni kompatybilnego ze wszystkimi oficjalnymi aplikacjami Bitwarden.

| | |
|---|---|
| **Licencja** | AGPL-3.0 |
| **Język** | Rust |
| **Aktualizacje** | Aktywne |
| **Wersja** | najnowsza `:latest` |

---

## 🔗 Linki

- [Strona oficjalna Bitwarden](https://bitwarden.com)
- [GitHub Vaultwarden](https://github.com/dani-garcia/vaultwarden)
- [Wiki / Dokumentacja](https://github.com/dani-garcia/vaultwarden/wiki)
- [Docker Hub](https://hub.docker.com/r/vaultwarden/server)

---

## ⚙️ Wymagania

| Zasób | Minimum | Zalecane |
|-------|---------|----------|
| RAM | 256 MB | 512 MB |
| CPU | 1 vCPU | 1 vCPU |
| Dysk | 1 GB | 5 GB |
| OS | Linux / Docker | Docker |
| Sieć | HTTPS wymagany | HTTPS + domena |

{: .warning }
Vaultwarden **wymaga HTTPS** – bez certyfikatu SSL aplikacje mobilne nie będą działać.
Użyj Let's Encrypt z Nginx Proxy Manager lub Traefik.

---

## 🐳 Szybki start (Docker Compose)

Utwórz plik `docker-compose.yml`:

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
      - ./vw-data:/data
    environment:
      DOMAIN: "https://hasla.twojadomena.pl"
      SIGNUPS_ALLOWED: "false"   # wyłącz rejestrację po założeniu konta
      ADMIN_TOKEN: "zmien-na-losowy-ciag-znakow"
```

Uruchom:

```bash
docker compose up -d
```

---

## 🔒 Bezpieczeństwo po instalacji

1. Zaloguj się do panelu admin: `https://twojadomena.pl/admin`
2. Wyłącz rejestrację: `SIGNUPS_ALLOWED=false`
3. Włącz 2FA dla swojego konta
4. Ustaw automatyczny backup bazy danych (`/data/db.sqlite3`)

---

## 💬 Opinia

{: .note }
**Moja ocena: 9/10**

Vaultwarden to najlepsza opcja dla zdecydowanej większości użytkowników.
Działa bezbłędnie z aplikacjami mobilnymi na Android i iOS oraz
rozszerzeniami do wszystkich popularnych przeglądarek.

**✅ Plusy:**
- Bardzo niskie zużycie zasobów (działa na RPi 3)
- Świetne, dopracowane aplikacje klienckie
- Wbudowany TOTP (kody 2FA)
- Bezpłatny – wszystkie funkcje premium Bitwarden za darmo
- Aktywna społeczność i regularne aktualizacje

**❌ Minusy:**
- Wymaga HTTPS (trzeba skonfigurować SSL)
- Baza SQLite – trzeba pamiętać o backupie
- Nieoficjalny fork – nie wspierany przez Bitwarden Inc.
