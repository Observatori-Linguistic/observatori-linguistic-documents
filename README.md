# Observatori Lingüístic Escolar · Documents

Els documents públics dels centres educatius de Catalunya que fa servir l'Observatori
Lingüístic Escolar: el projecte lingüístic que cada centre publica a la seva web,
tal com es va descarregar, i el text que se n'ha extret.

*Los documentos públicos de los centros educativos de Cataluña que utiliza el
Observatorio Lingüístico Escolar: el proyecto lingüístico que cada centro publica en
su web, tal como se descargó, y el texto extraído.*

## Estructura

    <comarca>/<codi del centre>/
        document.pdf      el document original (de vegades .docx, .html o .txt)
        document.md       el text del document, amb un capçal
        web.md            només en centres que no publiquen el projecte lingüístic:
                          el text de les pàgines de la seva web que parlen de llengües

El codi del centre és el del Directori de centres docents del Departament
d'Educació. Quan diversos centres comparteixen un mateix document (una ZER, o un
mateix centre amb dos codis), el document és a la carpeta d'un d'ells.

El capçal de cada `document.md` diu:

- `codi`, `centre`, `municipi`: el centre;
- `font`: l'adreça d'on es va descarregar el document;
- `descarregat`: la data de la descàrrega;
- `sha256`: l'empremta de l'original de la mateixa carpeta, per comprovar que és el
  mateix fitxer.

Els fitxers `web.md` no formen part de les xifres de l'Observatori, que només
compten els projectes lingüístics. Es conserven perquè es pugui consultar què diu
cada centre a la seva web.

## Drets

Els documents són dels centres que els han elaborat i publicat. Aquí només s'arxiven
com a font, perquè qualsevol persona pugui comprovar les dades i les cites de
l'Observatori encara que el centre canviï o retiri el document de la seva web.
