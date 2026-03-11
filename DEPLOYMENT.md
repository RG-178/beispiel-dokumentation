# Deployment

Diese Anleitung beschreibt die Installation auf einem Server.

---

## Empfohlene Infrastruktur

Beispiel:

- Linux Server
- Docker
- Nginx
- SSL Zertifikat

---

## Schritt 1 – Server vorbereiten

Installiere Docker und Docker Compose.

---

## Schritt 2 – Projekt kopieren

git clone REPOSITORY_URL

---

## Schritt 3 – Environment konfigurieren

.env Datei anpassen.

---

## Schritt 4 – Start

docker compose up -d

---

## Reverse Proxy (optional)

Beispiel:

Nginx Proxy auf Port 80/443.

---

## Updates

git pull  
docker compose up -d --build

---

## Backups

Empfohlen:

- Datenbank Backup
- Dateisystem Backup