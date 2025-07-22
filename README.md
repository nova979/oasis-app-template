# oasis-app-template

## Overview
Questo template ti fornisce la struttura di base per costruire mini‑app modulari in React/Flutter.

## Struttura
- `app_config.json` → metadati (id, titolo, autore, descrizione, tag)
- `manifest.yaml` → integrazione futura in Oasis
- `.env.example` → variabili ambiente
- `components/` → componenti UI riusabili (OasisButton, OasisCard…)
- `screens/` → viste principali (Home.jsx, Settings.jsx…)
- `core/` → logica condivisa (analytics, adsManager…)
- `style/` → tema CSS (palette, variabili)
- `main.jsx` → entrypoint
- `tests/` → test base

## Setup
```bash
git clone <https://github.com/nova979/oasis-app-template.git>
cd oasis-app-template
npm install           # o flutter pub get
cp .env.example .env
npm start             # o flutter run
