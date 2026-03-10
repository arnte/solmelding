# ☀️ Arntes solservice

En enkel webapp som viser solstatistikk for valgfritt sted og dato i Norge.

## Funksjoner

- **Dagslys i dag** (tt:mm:ss) for valgfritt sted og dato
- **Mer lys enn i går** (mm:ss)
- **Mer dagslys siden vintersolverv** (tt:mm:ss)
- **Sist like lyst** – hvilken dato hadde tilsvarende dagslys før solverv
- **Dager siden like lyst**
- **Klokkeslett** for demring, soloppgang, solnedgang og skumring
- **Merkedager** – banner vises når dagslyset passerer en halvtime-grense
- **Visuell solbane** over horisonten
- **Sol-grafikk** av Arnte tegnet av Oda 10 år ;)
- **Instagram-eksport** – last ned 1080×1920 px PNG med gjennomsiktig bakgrunn
- Husker **siste posisjon** (localStorage)
- Fungerer **offline** (NOAA-algoritme, ingen ekstern API)

## Nøyaktighet

Beregningene bruker [NOAA Solar Calculator](https://gml.noaa.gov/grad/solcalc/)-algoritmen og er nøyaktig til ±10–20 sekunder sammenlignet med timeanddate.com for norske breddegrader (som er litt ekstra krevende).

## Bruk

Åpne `index.html` i en nettleser – ingen installasjon eller server nødvendig. Kan lagres på hjemskjem på iPhone e.l.

Eller besøk den publiserte versjonen via GitHub Pages.

## Teknisk

- Ren HTML/CSS/JavaScript – ingen avhengigheter, ingen build-steg
- Geokoding via [OSM Nominatim](https://nominatim.openstreetmap.org/)
- All solberegning skjer lokalt i nettleseren

## Kreditering

- Solberegning: [NOAA Solar Calculator](https://gml.noaa.gov/grad/solcalc/)
- Geokoding: [OpenStreetMap Nominatim](https://nominatim.openstreetmap.org/)
- Instagram: [@arntessolservice](https://www.instagram.com/arntessolservice/)
