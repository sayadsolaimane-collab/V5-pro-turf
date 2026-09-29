# V5 Turf Pro - Méthode SOREC Météo
17 Quintés / 31 - 55% - Safi Maroc
WhatsApp: 0678025358 - FB: https://www.facebook.com/share/1EHp9RfZmf/

## Install
npm install
npm run dev -> http://localhost:3000

## ENV (.env.local)
APIFY_TOKEN=xxx
ODDSPAPI_KEY=xxx
OPENWEATHER_KEY=xxx
WHATSAPP_TOKEN=xxx

## Flow quotidien 10h
1. scripts/meteo.js -> pluie24h + etat piste + vent
2. scripts/apify.js -> forme Geny/Letrot (ferrure, corde, jockey)
3. scripts/oddspapi.js -> drift cotes 7h-10h
4. src/lib/fusion-v5.js -> score final + 2 tickets (Principal 15-4-14-5-7 + Surprise 15-6-12-8-18)
5. src/pages/api/send.js -> envoie WhatsApp aux abonnés (99/199 DH)

Mise de base SOREC: Quinté+ 12 DH desordre, Tierce/Quarte 6 DH
Phrase distributeur: "Quinté+ 12 DH 5 chevaux désordre : 15-4-14-5-7"

Offre: 14j gratuits lun-jeu (pas ven/dim) puis 99 DH (1 ticket) / 199 DH Pro (2 tickets + meteo + non-partant 12h30)
