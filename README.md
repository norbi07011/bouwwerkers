# I&M Bouwwerkers – website

Statische website (één `index.html` + `img/`), 1:1 gebaseerd op de Premium CoatUp-site (zelfde animaties, 3D-hero, voor/na-slider, offerteformulier), met naam, logo, kleuren (logo-blauw) en foto's van I&M Bouwwerkers.

- Talen: NL (standaard), EN, PL
- Hash-routing: `#home`, `#services`, `#pmma`, `#epoxy`, `#pu`, `#troffel`, `#industrial`, `#balcony`, `#garage`, `#process`, `#projects`, `#standards`, `#about`, `#faq`, `#contact`
- Geen build-stap: open `index.html` of host de map op Netlify / GitHub Pages

## Foto's
- `img/p01–p15.jpg` – projectfoto's (nu: één balkonproject, vóór / tijdens / na)
- `img/ba/1–4.jpg` – voor/na-slider: uitgangssituatie → voorbereiding → membraan → opgeleverd
- Nieuwe projecten: foto toevoegen als `img/pNN.jpg` en een regel in `PHOTOS()` / `FEAT()` in `index.html`

## TODO vóór livegang (gegevens I&M nodig)
- In `index.html` (zoek op `TODO`): e-mail, telefoon, WhatsApp-nummer (`WA_NUM` + knop `wa-float`), KvK, BTW, adres, plaats
- Controleren of de teksten kloppen voor I&M: systemen (PMMA/epoxy/PU/troffelvloer), VCA, 2 jaar garantie, merken (Sika, Mapei, Triflex …), werkgebied
- Partnerpagina is verwijderd (waren partners van Premium CoatUp) – `PARTNERS()` kan later gevuld worden
- Logo: originele afbeelding heeft een watermerk van de logogenerator; vraag de klant om het officiële bestand (PNG/SVG)
