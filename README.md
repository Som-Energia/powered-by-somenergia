# Projecte #

Això és un mapa interactiu amb els clients (empreses, associacions o persones) que usen <a href="http://www.somenergia.coop">Som Energia</a> com a proveïdora d'energia elèctrica. La informació de quines empreses tenen contractada somenergia s'ha obtingut o bé amb previ permís seu o bé amb ús de referències públiques (diaris, blogs, etc.)

La idea va sorgir a l'*Assamblea de Som Energia Mallorca 2015*, que va tenir lloc el 28 de març de 2015 al Museu del Calçat i de la Pell (Inca).

Existeix un projecte similar *[Negocios Amigos](https://blog.somenergia.coop/grupos-locales/larioja/gl-la-rioja/2015/05/negocios-amigos-de-som-energia-en-la-rioja-2/)* de Som Energia La Rioja, del qual vàrem tenir constància a posteriori.

## Instal·lació ##

Descarregueu-vos el contingut d'aquest directori (botó dret `Download ZIP` o bé premeu [aquí](https://github.com/somenxavier/powered-by-somenergia/archive/gh-pages.zip)) i obriu el fitxer `index.html` amb el vostre navegador web. Si disposeu de git, podeu [clonar](https://github.com/somenxavier/powered-by-somenergia.git) aquest repositori.

## Llicència ##

La llicència de les dades es distribueix sota domini públic (veure llicència al repositori). La resta de continguts es distribuixen segons les seves respectives llicències, en particular el programari.

## Programari emprat ##

La llista del programari emprat és:

  * [Leaflet Simple CSV](https://github.com/perrygeo/leaflet-simple-csv)
  * [Leaflet](https://github.com/Leaflet/Leaflet)
  * [Leaflet.geoCSV](https://github.com/joker-x/Leaflet.geoCSV)
  * [Leaflet.markercluster](https://github.com/Leaflet/Leaflet.markercluster)
  * [Twitter Boostrap](http://twitter.github.io/bootstrap/)
  * [jQuery](http://jquery.com/)


# Arxiu CSV #

L'arxiu de les dades es troba a la ruta `data/data.csv`. Aquest arxiu és un arxiu de tipus CSV separat per `|`. Els camps que conté són:
  * `Nom`: el nom del client. Per exemple `Botiga de taps de Suro Joan X`
  * `Paraules clau`: les paraules clau que surtiran a la cerca. Per exemple, `suro`, `taps`, `botiga`
  * `Adreça`: adreça completa
  * `lat`: latitud
  * `lng`: longitud
  * `Web`: web oficial
  * `Referències`: referències oficials on apareix la informació de què és soci de somenergia. Opcional.
  