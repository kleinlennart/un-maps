# UN Maps

How to use official UN Maps in interactive Quarto documents.

## Resources

- https://quarto.org/docs/interactive/
- https://geoportal.un.org/arcgis/home/item.html?id=541557fd0d4d42efb24449be614e6887
- https://www.un.org/geospatial/
- https://r-graph-gallery.com/interactive-charts.html
- https://r-graph-gallery.com/package/leaflet.html
- https://github.com/holtzy/quarto-tricks/blob/main/interactive-map/index.qmd
- https://leafletjs.com/

## Maps

This is the WMS server link to enter:
https://geoservices.un.org/arcgis/rest/services/ClearMap_WebTopo/MapServer/WMSServer?

https://geoservices.un.org/arcgis/rest/services/ClearMap_WebGray/MapServer

## Dev

```
quarto preview un-maps.qmd --port 1945
quarto render un-maps.qmd
```

http://localhost:1945/un-maps.html