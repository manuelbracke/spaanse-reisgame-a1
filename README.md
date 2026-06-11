# Pasaporte A1 — Spaanse reiswoordenschat

Browsergame in één HTML-bestand voor Spaanse reiswoordenschat op A1-niveau.

## Publiceren op GitHub Pages

Upload `index.html` naar een publieke repository en zet GitHub Pages aan via `Settings > Pages > Deploy from a branch > main > /(root)`.

## Aanpassen van de woordenlijst

Open `index.html` en vervang alleen de JSON-array tussen:

```html
<!-- JSON WOORDENLIJST — VERVANG ALLEEN DE ARRAY HIERONDER -->
...
<!-- EINDE JSON WOORDENLIJST -->
```

Vereiste velden per item: `es`, `nl`, `thema`, `afleiders`, `zin`.
Optioneel maar aanbevolen voor Engelstalige spelers: `en`.
