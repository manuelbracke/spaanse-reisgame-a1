# Spaanse Reisgame A1

Educatieve browsergame voor Spaanse reiswoordenschat op A1-niveau.

## Publiceren met GitHub Pages

1. Maak een publieke repository aan op GitHub, bijvoorbeeld `spaanse-reisgame-a1`.
2. Upload `index.html` en `README.md` naar de repository.
3. Ga naar **Settings > Pages**.
4. Kies **Deploy from a branch**.
5. Kies branch **main** en folder **/(root)**.
6. Klik **Save**.
7. Wacht tot GitHub de publieke link toont.

De game werkt volledig in de browser. Leerlingen hebben geen GitHub-account nodig.

## Game aanpassen

Open `index.html` en zoek naar:

```html
<!-- JSON WOORDENLIJST — VERVANG ALLEEN DE ARRAY HIERONDER -->
```

Vervang alleen de JSON-array tussen dat commentaar en:

```html
<!-- EINDE JSON WOORDENLIJST -->
```

Elk woord moet deze structuur behouden:

```json
{
  "es": "el tren",
  "nl": "de trein",
  "thema": "vervoer",
  "afleiders": ["el pan", "el hotel"],
  "zin": "Tomamos ____ a Madrid."
}
```

## Problemen

- Zie je een 404? Controleer of het bestand exact `index.html` heet.
- Controleer of de repository publiek is.
- Controleer of GitHub Pages op **main / root** staat.
- Wacht enkele minuten na elke wijziging.
