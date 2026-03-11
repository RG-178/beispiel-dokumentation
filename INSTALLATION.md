# Installation

Diese Anleitung beschreibt die lokale Installation.

---

## Requirements

Liste der Voraussetzungen:

- Node.js
- Python
- Docker
- PostgreSQL

(Optional je nach Projekt)

---

## Schritt 1 – Repository klonen

git clone REPOSITORY_URL

---

## Schritt 2 – Environment konfigurieren

cp .env.example .env

Bearbeite anschließend die Werte.

---

## Schritt 3 – Dependencies installieren

Beispiele:

npm install

oder

pip install -r requirements.txt

---

## Schritt 4 – Anwendung starten

docker compose up

ODER

python main.py

---

## Troubleshooting

Häufige Probleme:

Port bereits belegt  
→ anderen Port verwenden

Database Verbindung schlägt fehl  
→ .env prüfen