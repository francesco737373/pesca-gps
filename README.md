# PESCA GPS – PWA 1.0

Prima web app progressiva del progetto PESCA GPS.

## Funzioni della versione 1.0
- GPS reale del browser con alta accuratezza
- registrazione traccia locale
- distanza percorsa
- esportazione GPX
- creazione/salvataggio evento locale
- registrazione catture con coordinate GPS
- modalità offline per i dati locali
- installazione come PWA

## Pubblicazione
Caricare questi file nella root del repository GitHub:
- index.html
- manifest.webmanifest
- sw.js
- icon.svg
- README.md

Poi GitHub > Settings > Pages > Deploy from a branch > main > /(root) > Save.

Nota: per il GPS reale il sito deve essere aperto tramite HTTPS e il browser deve avere il permesso di posizione.

## Importante
Questa è una base PWA funzionante, non ancora il sistema multiutente definitivo. La prossima fase aggiungerà cartografia, poligoni geografici, QR evento, server realtime, partecipanti multipli, geofence reale, console organizzatore, ranking e SOS.
