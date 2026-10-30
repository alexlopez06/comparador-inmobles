# Comparador d’immobles de Catalunya

Web estàtica (sense servidor): enganxes l’enllaç i el text d’un anunci i la pàgina mostra l’entorn (OpenStreetMap), el preu per m² i el cost real de compra amb ajudes.

## Publicar a GitHub Pages
1. Puja `index.html` i aquest `README.md` a la branca `main`.
2. A **Settings → Pages**, tria *Deploy from a branch*, branca `main`, carpeta `/ (root)`.
3. La web quedarà a `https://alexlopez06.github.io/comparadorinmobles/`.

## Pendent
- Verificar els tipus fiscals (`CFG` al començament del `<script>`).
- Inundabilitat (ACA) i comparació €/m² amb Idescat.

## Preus registrats (`preus.json`)
Generat a partir dels fitxers trimestrals per municipis de l’Agència Catalana de l’Habitatge (Col·legi de Registradors): preu per m² construït d’habitatge usat i nou dels darrers 12 mesos, l’any anterior i els últims 6 trimestres, per a municipis de més de 2.000 habitants. Cal regenerar-lo cada trimestre amb els fitxers nous.
