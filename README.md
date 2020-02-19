[![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/mapbox_logo.PNG)](https://mapbox.com) 
## Intro to Mapbox workshop - Rowan University - Cartography (2/19/2020)

Christopher Pollard, pollardc@rowan.edu, [@CRVanPollard ](https://twitter.com/CRVanPollard)

### Today's goal - make this map
[![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/todaysmap.png)](https://api.mapbox.com/styles/v1/crvanpollard/ck6s980mv09oh1iqppo5rusgo.html?fresh=true&title=view&access_token=pk.eyJ1IjoiY3J2YW5wb2xsYXJkIiwiYSI6Ii00ZklVS28ifQ.Ht4KwAM3ZUjo1dT2Erskgg)

### How are we going to get there...
- Overview of Mapbox Studio
- Getting started 
- Importing data into Mapbox Studio
- Visualizing data in Mapbox Studio
- Publishing your style

## Overview of Mapbox Studio
#### Mapbox Studio - https://www.mapbox.com/mapbox-studio/
Design interactive maps that run on any device with Mapbox Studio
- Full basemap design control
- Data visualization
- Publish across platforms

[![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/mapboxstudio.png)](https://cartodb.com/editor/)

#### What are people doing with it
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/strava.png)
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/election.png)
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/impossible.png)
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/alltrail.png)
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/blueprint.png)
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/airports.png)
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/spiderman.png)
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/got.png)

## Getting Started

### Set up an account
If you don't have an account, go sign up: [https://account.mapbox.com/](https://account.mapbox.com/)  

### Mapbox Dashboard
This is where you can view and manage your account and settings
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/dashboard.png)

### Mapbox Studio
Mapbox Studio has 3 main componets that will allow you to store different collections (Styles, Tilesets, and Datasets)

<b>Styles</b> are your customized basemaps with all your custom settings for font, layer zoom levels, color and symbology for your tilesets.
 
The <b>Tilesets</b> are a collection of raster or in most cases the vector data. The tilesets are broken up into a uniform grid of square tiles for all 22 preset zoom levels.

<b>Datasets</b> are an editable collection of GeoJSON features. 

![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/std.png)

## Importing data into Mapbox Studio
### Supported geospatial data formats
https://docs.mapbox.com/help/glossary/dataset/
- GeoJson
- JSON
- CSV

### Datasets
Today, we are going to work with a few local datasets that focus on Bicycle Planning in Philadelphia.
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/opendataphilly.png)
Please go to the following URLs listed below, download and save the <b><u>geojsons</u></b> files.

- Philadelphia Bike Network ([Open Data Philly](https://www.opendataphilly.org/dataset/bike-network))
`https://www.opendataphilly.org/dataset/bike-network`
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/bn_geojson.png)

- Indego Bike Share Stations ([Open Data Philly](https://www.opendataphilly.org/dataset/bike-share-stations))
`https://www.opendataphilly.org/dataset/bike-share-stations`
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/i_geojson.png)

- Neighborhood Food Retail ([Open Data Philly](https://www.opendataphilly.org/dataset/neighborhood-food-retail))
`https://www.opendataphilly.org/dataset/neighborhood-food-retail`
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/nfr_geojson.png)

### Uploading a New Dataset
Once you have your GeoJson or CVS (that has Latitude and Longitude values) it is a simple drag n' drop process to upload your data
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/newdataset.png)

### Dataset Editor 
This is where you can create, import, and edit geographic data. 
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/editor.png)
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/data_editor.png)

### Import
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/import.png)

### Draw
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/draw.png)

### Export
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/export.png)

### Toolbar
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/toolbar.png)

## TileSets
A tileset is a collection of raster or vector data broken up into a uniform grid of square tiles at 22 preset zoom levels. Mapbox will render vector tiles from your dataset so you can create styles from it. 

### Exporting your Dataset to Tilesets
Once you have your dataset uploaded and ready to use you will need to "Export to tileset". You can do this in the main dataset page or in the Data Editor
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/exporttile.png)
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/exporttileset.png)

### How to use tilesets
Once your vector tiles are baked, you'll then be able to add them to a new or existing style. 

## Styles
### Style Editor
The Mapbox Studio style editor is your visual interface for creating custom map styles. A style is a set of rules for how your map will be rendered on a page. It includes references to your data, map images (icons, markers, patterns), fonts, and, most importantly, it defines how all your data should be styled on your map.
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/styleeditor.png)

### Template Styles
There are several Mapbox-designed map styles that can either be used directly in your web or mobile application or be used as a starting point for creating a new custom style in Mapbox Studio. 
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/template.png)

### Cartogram - https://apps.mapbox.com/cartogram/
Cartogram allows you to create a map from your favorite photo's colors and then fine tune the rest of the design with Style Components 
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/cartogram.gif)

### Style Componets
Style components provide sensible defaults and quick opportunities for customization by optimizing the most common property changes for styles and packaging them into drop-down options, sliders, and toggles.
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/componets.png)

### Style Layers
Detailed breakdown of all the layers within the style
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/layers.png)

### Creating a map of your data
First open your style in the style editor. Next, you can either create a new layer with this tileset as the source, or you can change an existing layer's data source to this tileset.
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/customdata.png)

### Publish
Once you are ready to share your visualization you click the `Publish` button.
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/publish.png)

## Mapbox Resources

### Mapbox Studio Manual - https://docs.mapbox.com/studio-manual/overview/
This handy Mapbox Studio manual contains a comprehensive explanation of each section of Mapbox Studio, including general descriptions of individual components and detailed information on specific tools. It can be used either as a reference when using specific tools in Mapbox Studio, or as a way to understand the general pieces of how a Mapbox map is constructed.

### How to create a custom Mapbox map style using a template - https://www.mapbox.com/videos/how-to/create-a-custom-map-style-using-a-template/
[![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/video1.png)](https://www.mapbox.com/videos/how-to/create-a-custom-map-style-using-a-template/)

### Mapbox Storytelling - https://www.mapbox.com/solutions/interactive-storytelling
A simple way for journalists, designers, bloggers, and others to publish stories that combine narratives with map interactions. Allows creative minded people to weave interactive stories with images, maps, and compeling narritives.
[![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/mapboxstory.gif)](https://www.mapbox.com/solutions/interactive-storytelling)




