# OpenStreetMap

## Overpass turbo

- fermate [http://overpass-turbo.eu/s/lwX](http://overpass-turbo.eu/s/lwX)

- linee [http://overpass-turbo.eu/s/pjt](http://overpass-turbo.eu/s/pjt)

# spatialite

```
ogr2ogr -append -f SQLite -dsco SPATIALITE=YES -nln linee scat.sqlite lineeOSM.geojson
ogr2ogr -append -f SQLite -dsco SPATIALITE=YES -nln fermate scat.sqlite fermateOSM.geojson

```   
mappa uMap delle linee e bus di Caltanissetta creata con i file geojson di questa directory http://u.osmfr.org/m/150723/
