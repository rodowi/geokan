# geokan

Find geodata in CKAN

Flow:

- Search recursively for well-known geo formats
- Look for longitude/latitude properties in text formats
- Search for name of places in the remaining datasets, e.g. 'Baja California'
- Stream results to the console

Usage:

```bash
% npm install -g geokan
% geokan --format geojson,GeoJSON,shp,SHP,kml,KML,kmz,KMZ > geo.json
```
