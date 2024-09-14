# qgis-quickstart

Geospatial data + style in a single file, ready to load and edit in QGIS.

These are my personal working files and I'm making them available AS IS (bugs and all).

## Set Up

Download and install QGIS if you don't already have it: [QGIS Downloads](https://qgis.org/download/).

The following are IMPORTANT things to know about QGIS and using the files in this repo.

### Browser Panel

Add a useful browser panel to navigate and load files:

`View` > `Panel` > `Browser`

### Loading Files

Load a GPKG file by navigating to the downloaded file in the `Browser Panel`, double-click to expand the layer(s) saved in the file, select the layer(s) you want and drag them to the `Layer Panel` or right-click and select `Add Layer to Project`.

### Symbology

1. In the `Layers Panel` double-click on your layer.

2. Click on `Symbology` tab in the left panel to access symbol layers. Most of my vector layers use `Rule-based` symbology to display different layers based on expressions.

3. Click on a rule in the main window to edit its properties.

### Expressions

I make heavy use of expressions to create my QGIS styles. There are several places to use expressions:

1. The `Geometry Generator` in `Symbol layer type`.

2. The `Data defined override` button to the right of almost all options like stroke width, stroke style, fill color, etc.

## Additional Reading

For step-by-step instructions on how to use QGIS, refer to the official docs:  

[A gentle introduction to GIS](https://docs.qgis.org/3.34/en/docs/gentle_gis_introduction/)  
[Training manual](https://docs.qgis.org/3.34/en/docs/training_manual/)  
[User guide](https://docs.qgis.org/3.34/en/docs/user_manual/)  

Or the excellent tutorials at:  

[QGIS tutorials and tips](https://www.qgistutorials.com/en/)  

## Data Sources

OpenStreetMap  
[OpenStreetMap](https://www.openstreetmap.org/#map=2/71.3/-96.8.)  
[BBike city extracts](https://download.bbbike.org/osm/bbbike/)  
[GeoFabrik data Extracts](https://download.geofabrik.de/)  
