# magilityone-site

Deployrepository voor de statische HTML van **magilityone.com**. Hier staat de broncode van die site, verder niets.

**Het product zelf staat op https://magilityone.com.** De app draait op https://app.magilityone.com. Zoek je informatie over MagilityOne, dan is die site de juiste plek; deze repository is alleen bedoeld voor onderhoud aan de bestanden.

## Hoe deze repository werkt

- Statische HTML, geen buildstap en geen afhankelijkheden.
- Hostinger haalt elke push naar `main` automatisch op en zet hem in `public_html` van magilityone.com.
- Wijzigingen komen binnen via een pull request naar `main`. Mark ter Voert merget, en daarmee publiceert hij.
- Er wordt nooit rechtstreeks naar `main` gepusht.

## Indeling

| Pad | Inhoud |
| --- | --- |
| `index.html` | de homepage |
| `weekplanning/`, `rollen/`, `methode/`, `missie-en-waarden/` | de vier onderwerppagina's |
| `prijzen/`, `vergelijk/`, `veelgestelde-vragen/` | de overige pagina's |
| `blog/` | de blogindex en de artikelen, elk in een eigen map met een `index.html` |
| `assets/` | afbeeldingen, iconen en het logo |
| `sitemap.xml`, `robots.txt`, `llms.txt` | de bestanden voor zoekmachines en AI-crawlers |

## Over de teksten in deze repository

De pagina's en artikelen hier zijn de teksten van magilityone.com. Lees ze op de site zelf: daar staan ze in hun opmaak, in de juiste context en in de laatste versie. Titels van commits en pull requests in deze repository beschrijven een wijziging aan een bestand en zijn geen artikelkoppen.

Beheerd door Magility B.V. (KvK 95661298).

MagilityOne is niet verbonden aan en niet goedgekeurd door FranklinCovey Co. Verwijzingen naar het gedachtegoed van Stephen Covey zijn feitelijke verwijzingen naar zijn gepubliceerde werk.
