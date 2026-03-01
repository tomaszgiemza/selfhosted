---
layout: default
title: Jellyfin
parent: Media
nav_order: 1
description: "Jellyfin – darmowy open-source serwer mediów. Opinia, wymagania, konfiguracja Docker, transkodowanie."
---

# 🎬 Jellyfin

{: .highlight }
Najlepsza darmowa alternatywa dla Plex i Emby – bez opłat, bez chmury, bez telemetrii

## O narzędziu

Jellyfin to w pełni open-source serwer mediów pozwalający strumieniować
filmy, seriale, muzykę i zdjęcia na dowolne urządzenie.
W przeciwieństwie do Plex nie wymaga konta ani abonamentu.

| | |
|---|---|
| **Licencja** | GPL-2.0 |
| **Język** | C# / .NET |
| **Aktualizacje** | Aktywne |
| **Aplikacje** | Android, iOS, TV, Web, Kodi |

---

## 🔗 Linki

- [Strona oficjalna](https://jellyfin.org)
- [GitHub](https://github.com/jellyfin/jellyfin)
- [Dokumentacja](https://jellyfin.org/docs/)
- [Docker Hub](https://hub.docker.com/r/jellyfin/jellyfin)

---

## ⚙️ Wymagania

| Zasób | Minimum | Zalecane |
|-------|---------|----------|
| RAM | 1 GB | 2–4 GB |
| CPU | 2 vCPU | 4 vCPU (transkodowanie) |
| Dysk (system) | 1 GB | 5 GB |
| Dysk (media) | dowolny | NAS / HDD |
| OS | Linux / Docker | Docker |

{: .note }
Transkodowanie 4K wymaga CPU z AVX2 lub GPU z NVENC (NVIDIA) / VAAPI (Intel/AMD).
Direct Play nie obciąża CPU – klient sam dekoduje plik.

---

## 🐳 Szybki start (Docker Compose)

```yaml
version: '3'
services:
  jellyfin:
    image: jellyfin/jellyfin:latest
    container_name: jellyfin
    restart: unless-stopped
    ports:
      - "8096:8096"
    volumes:
      - ./config:/config
      - ./cache:/cache
      - /sciezka/do/filmow:/media/filmy:ro
      - /sciezka/do/seriali:/media/seriale:ro
      - /sciezka/do/muzyki:/media/muzyka:ro
    environment:
      - JELLYFIN_PublishedServerUrl=https://media.twojadomena.pl
```

Uruchom:

```bash
docker compose up -d
```

Panel dostępny pod: `http://localhost:8096`

---

## 💬 Opinia

{: .note }
**Moja ocena: 9/10**

Jellyfin to mój główny serwer mediów od ponad 2 lat.
Działa stabilnie, aplikacje na TV (Android TV, Apple TV) są dopracowane,
a brak wymogu konta to ogromna zaleta względem Plex.

**✅ Plusy:**
- W 100% darmowy – bez subskrypcji, bez konta
- Brak telemetrii i śledzenia
- Świetne aplikacje na Smart TV i Kodi
- Hardware acceleration (NVENC, VAAPI, QSV)
- Aktywna społeczność, częste aktualizacje

**❌ Minusy:**
- Transkodowanie 4K wymaga mocnego sprzętu
- Aplikacja iOS mniej dopracowana niż Plex
- Brak oficjalnego wsparcia komercyjnego
