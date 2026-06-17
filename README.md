# 🦄 Veronica & Cecilias Arkade

En lille samling browserspil i et magisk univers med enhjørninger, regnbuer og glimmer — lavet til Veronica (4 år) og Cecilia (8 år).

Hele arkaden er **én enkelt fil** (`index.html`). Der skal ikke installeres eller bygges noget — det virker bare, både på computer, tablet og telefon.

## Spillene

- **🃏 Vendespil** — find parrene. Vælg antal brikker og hvor rodet de ligger, tilmeld spillere, og se hvem der finder flest par. Hver spiller er en enhjørning i sin egen farve.
- **🫧 Boblebobbel** — klassisk bobleskyder. Sigt, skyd, og pop tre eller flere ens bobler.
- **⭐ Stjernefangst** — flyt enhjørningen og fang faldende stjerner og hjerter. Pas på bomberne!

## Sådan prøver du det med det samme

Dobbeltklik på `index.html`, så åbner spillet i din browser.

## Sådan lægger du det på GitHub

1. Log ind på [github.com](https://github.com) og klik på **New** for at oprette et nyt repository (fx kaldet `arkade`). Sæt det til **Public**.
2. På repository-siden: klik **Add file → Upload files**, og træk `index.html` (og gerne denne `README.md`) ind. Klik **Commit changes**.

### Gør spillet til en hjemmeside (GitHub Pages)

Så kan I spille det fra en rigtig internetadresse — også på pigernes tablet.

3. Gå til **Settings** (øverst i dit repository) → **Pages** (i menuen til venstre).
4. Under **Branch** vælger du `main` og mappen `/ (root)`, og trykker **Save**.
5. Vent ca. et minut. Genindlæs siden, så viser GitHub en grøn boks med linket — typisk:

   `https://DIT-BRUGERNAVN.github.io/arkade/`

Det link kan du dele eller gemme som bogmærke på tabletten. 💜

## Teknisk

- Ingen afhængigheder ud over en skrifttype, der hentes fra Google Fonts (faldback til systemets skrifttype, hvis man er offline).
- Ren HTML, CSS og JavaScript i én fil — ingen build, ingen server.
