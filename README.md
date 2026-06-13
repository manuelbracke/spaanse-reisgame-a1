# Lola Español — Spaans met Lola / Spanish with Lola / Španielčina s Lolou

Kindvriendelijke Spaanse woordenschatgame als mobiele PWA voor beginners.

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

## v1.3.0-agent — agentische upgrade

Deze versie brengt de app dichter bij een echte kindertaalgame:

- missiekaart met 13 plekken/missies;
- echt stickerboek met gevonden en verborgen stickers;
- 132 Spaanse woorden;
- 22 korte Spaanse chunks/zinnen;
- 5 vragen per missie;
- automatische Spaanse audio per vraag;
- trage audio-knop;
- antwoordknoppen met pictogrammen;
- vriendelijkere foutfeedback;
- lokale herhaling van moeilijke woorden;
- lokale voortgang via `localStorage`;
- `?test=1`-debug/zelfcheckmodus;
- geen account, advertenties of externe tracking.

## Privacy

De app verzamelt geen persoonsgegevens. Er is geen login, geen advertentiecode, geen analytics en geen externe tracking. Voortgang wordt lokaal op het toestel bewaard via de browser.

## Native review

De Spaanse woorden en zinnen zijn intern gecontroleerd op basisniveau en kindvriendelijkheid. Dit is geen officiële externe native-speaker-validatie. Gebruik `native-review-list.csv` om alle woorden en chunks door een native speaker Spaans en desgewenst Slovaaks te laten valideren.

## Testen vóór gebruik met kinderen

1. Open de app via GitHub Pages.
2. Speel minstens drie verschillende missies.
3. Test audio op iPhone Safari, Android Chrome en laptop.
4. Test de app na “Zet op beginscherm”.
5. Test offline na één eerste online bezoek.
6. Open `index.html?test=1` om de ingebouwde zelfcheck te zien.
7. Open `voor-leerkrachten.html`.
8. Wis voortgang en controleer of alles opnieuw start.

## Cache

Service worker cache: `lola-espanol-kids-v1.3.0-agent`.

## Publicatiestatus

Geschikt als sterke testversie / release candidate voor gecontroleerde kindertests. Voor brede publieke verspreiding blijven aanbevolen: echte kindtest, native speaker review, test op echte toestellen en eventueel opgenomen native audio.
