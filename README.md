# Lola Español — Spaans met Lola / Spanish with Lola / Španielčina s Lolou

Kindvriendelijke Spaanse woordenschatgame als offline mobiele PWA.

## Wat is nieuw in v2.0

Deze versie tilt de game van één werkvorm naar een echte taalgame met diepgang én speelplezier:

- **Vijf adaptieve werkvormen** die meegroeien met het spaced-repetition-niveau van elk woord — van *herkennen* (luister & kies) naar *terughalen* (plaatje↔woord) naar *produceren* (spreek na Lola).
- **Spraakoefening**: het kind zegt het woord hardop; waar de browser spraakherkenning toelaat luistert de app mee, anders bevestigt het kind zelf.
- **Geheugenspel** (woord ↔ beeld) als beloning na elke missie.
- **Lola als personage**: ze reageert, moedigt aan en viert mee.
- **Offline geluid** via de Web Audio API (juist/fout/level-up), plus confetti en een XP/niveau-systeem bovenop sterren en stickers.
- **Reiskaart**: de 13 missies als route door Lola's jungle.
- Behouden uit v1.3: 132 woorden, 28 chunks, 13 thema's, 3 talen, Leitner-herhaling, lokale voortgang, `?test=1`-zelfcheck, géén account/reclame/tracking.

## Bestanden uploaden naar GitHub Pages

Upload alle bestanden naar de root van de repository:

- `index.html`
- `manifest.webmanifest`
- `service-worker.js`
- `voor-leerkrachten.html`
- `native-review-list.csv`
- `README.md`
- `icons/icon-192.png`
- `icons/icon-512.png`

## Privacy

Geen persoonsgegevens, geen login, geen advertentiecode, geen analytics, geen externe tracking. Voortgang wordt lokaal bewaard via de browser (`localStorage`).

## Native review

De Spaanse woorden en zinnen zijn intern gecontroleerd op basisniveau. Dit vervangt geen officiële native-speaker-validatie. Gebruik `native-review-list.csv` om alles door een moedertaalspreker Spaans (en desgewenst Slovaaks) te laten nakijken.

## Testen vóór gebruik met kinderen

1. Open de app via GitHub Pages.
2. Speel minstens drie missies en kom alle vijf werkvormen tegen.
3. Test audio op iPhone Safari, Android Chrome en laptop.
4. Test na "Zet op beginscherm" en daarna offline (na één online bezoek).
5. Open `index.html?test=1` voor de ingebouwde zelfcheck.
6. Open `voor-leerkrachten.html`.
7. Wis voortgang en controleer of alles opnieuw start.

## Cache

Service worker cache: `lola-espanol-kids-v2.0.0`. Door de nieuwe versienaam worden oude caches automatisch opgeruimd na deploy.

## Publicatiestatus

Sterke testversie / release candidate voor gecontroleerde kindertests. Voor brede publieke verspreiding blijven aanbevolen: echte kindtest, native-speaker review, test op echte toestellen en eventueel opgenomen native audio.
