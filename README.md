ten20tileServer
===============

Generates map tiles on the fly from Mapnik XML or serves tiles from an [mbtiles](https://www.mapbox.com/developers/mbtiles/) file.

ten20tileServer generates map tiles on the fly from Mapnik XML or serves tiles from an mbtiles file. ten20tileServer is a simple [Express](http://expressjs.com/) based wrapper around [tilelive.js] (https://github.com/mapbox/tilelive.js) library.


## Tile scheme
Uses leaflet compabtilble {z}/{x}/{y} tile scheme

## Leaflet tile layer url
By default:
http://localhost:7777/v2/tiles/{z}/{x}/{y}.png

## Installation
```npm install -g ten20-tile-server```


## Usage Examples

### Mapnik
```ten20-tile-server --url mapnik:///home/alex/Documents/mapbox-osm-bright-86bc63f/build/ten20.xml```

### mbtiles
```ten20-tile-server --url mbtiles:///home/alex/Documents/MapBox/tiles/ten20.mbtiles```
