# Plons! Meerstad

Statische Nederlandstalige website voor een educatieve phishingoefening op een basisschool. De homepage presenteert een fictief waterpark. Alle drie abonnementsknoppen verwijzen direct naar `onthulling.html`, met een vriendelijke uitleg en gesprekspunten.

## Bekijken

Open `index.html` in je browser. Alles werkt ook zonder internet. Geen installatie, JavaScript, externe lettertypen, CDN, database of buildstap nodig.

## Publiceren op GitHub Pages

1. Pak het zipbestand uit.
2. Maak een GitHub-repository en voeg de inhoud van deze map toe aan de hoofdmap van de `main`-branch. `index.html` moet direct in de hoofdmap staan, niet in een extra submap. Neem ook `.nojekyll` mee.
3. Open in de repository **Settings → Pages**.
4. Kies onder **Build and deployment → Source** voor **Deploy from a branch**.
5. Kies branch **main** en map **/(root)**, en klik **Save**.
6. Wacht tot de publicatie is afgerond. De URL staat bij Pages, doorgaans `https://GEBRUIKERSNAAM.github.io/REPOSITORYNAAM/`.
7. Open die URL en controleer de drie abonnementsknoppen en de teruglink op de uitlegpagina.

Alle paden zijn relatief en werken ook onder een repository-subpad. Een domeinnaam of servercode is niet nodig.

GitHub-documentatie: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Bestanden en aanpassen

- `index.html`: homepage, naam, promotieteksten en knoppen.
- `onthulling.html`: uitleg en gesprekspunten voor de klas.
- `style.css`: kleuren, opmaak en mobiele weergave.
- `waterpark.svg`: lokale vectorillustratie van het fantasiepark.
- `icon.svg`: favicon.
- `.nojekyll`: statische publicatie zonder Jekyll-verwerking.
- `robots.txt`: verzoek aan zoekmachines om de site niet te crawlen; beide pagina's bevatten ook noindex. Dit is geen toegangsbeveiliging. Bij een GitHub Pages-projectsite geldt robots.txt alleen als het aan de oorsprong van het domein staat; de noindex-metatags staan op elke pagina zelf.

## Gebruik in de klas

Bespreek na afloop wat aantrekkelijk en wat verdacht was. Laat kinderen de drie aanwijzingen terugzoeken: een buitensporige belofte, tijdsdruk en een onduidelijke afzender. Sluit af met **Stop. Check. Vraag.** De oefening is bedoeld om samen te leren, zonder kinderen te beschamen. Er worden geen echte organisaties als afzender nagebootst.

De website bevat geen formulieren, cookies, analytics, externe bronnen, downloads of klikregistratie. Er wordt dus ook geen deelnemerslijst bijgehouden. De hostingprovider kan wel technische toegangsgegevens verwerken. Het voorbeeldpark en de aanbieding zijn verzonnen; de site claimt geen echte gemeentelijke plannen. Er is nog niets naar GitHub gepubliceerd.
