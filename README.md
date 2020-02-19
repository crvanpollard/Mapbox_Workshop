[![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/mapbox_logo.PNG)](https://mapbox.com) 
## Intro to Mapbox workshop - Rowan University - Cartography (2/19/2020)

Christopher Pollard, pollardc@rowan.edu, [@CRVanPollard ](https://twitter.com/CRVanPollard)

### Today's goal - design a custom basemap with local datasets
[![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/todaysmap.png)](https://api.mapbox.com/styles/v1/crvanpollard/ck6s980mv09oh1iqppo5rusgo.html?fresh=true&title=view&access_token=pk.eyJ1IjoiY3J2YW5wb2xsYXJkIiwiYSI6Ii00ZklVS28ifQ.Ht4KwAM3ZUjo1dT2Erskgg)

### How are we going to get there...
- Overview of Mapbox Studio
- Getting started 
- Importing data into Mapbox Studio
- Visualizing data in Mapbox Studio
- Publishing your style

## Overview of Mapbox Studio
#### Mapbox Studio - https://www.mapbox.com/mapbox-studio/
Design and style custom basemaps that are fully interactive with Mapbox Studio
- Full basemap design control
- Data visualization
- Publish across multiple platforms

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
This is where you view and manage your account and settings
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/dashboard.png)

## Mapbox Studio
Mapbox Studio has 3 main componets that will allow you to store different collections (Styles, Tilesets, and Datasets)
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/std.png)

<b>Styles</b> are your customized basemaps with all your custom settings for font, layer zoom levels, color and symbology for your tilesets.
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/styles1.png)
 
The <b>Tilesets</b> are a collection of raster or in most cases the vector data. The tilesets are broken up into a uniform grid of square tiles for all 22 preset zoom levels.
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/zoom.png)

<b>Datasets</b> are an editable collection of GeoJSON features. 
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/dataset1.png)



## Importing data into Mapbox Studio
### Supported geospatial data formats
https://docs.mapbox.com/help/glossary/dataset/
- GeoJson (an open standard file format for representing map data)
https://docs.mapbox.com/help/glossary/geojson

- JSON (JavaScript Object Notation is an open-standard file format or data interchange format that uses human-readable text to transmit data objects consisting of attribute–value pairs and array data types or any other serializable value)

- CSV (is common for table data file format used in Excel or other spreadsheets programs)
https://docs.mapbox.com/help/glossary/csv/

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
Once you have downloaded the GeoJson or in some cases a CVS (that has Latitude and Longitude values) it is a simple drag n' drop or select file process to upload your geospatial data to mapbox
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/newdataset.png)

### Dataset Editor 
This is a tool that allows you to create, import, and edit your geographic data as well as attribute information. 
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/editor.png)
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/data_editor.png)

### Import - add new GeoJson features or CSV files that contain latitude and longitude coordinates 
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/import.png)

### Draw - add new geometry to existing datasets or draw your own from scratch 
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/draw.png)

### Export - you will need to export your dataset before you can use in a styled map
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/export.png)

### Toolbar - a set a tools that help with map navigation and basemap options
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/toolbar.png)

### Edit - modify geometry and attribute values
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/highpoverty.png)

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
Cartogram allows you to create a map from your favorite photo's colors and then fine tune the rest of the design with Style Components - - -  “All the pretty colors--crafting themes”
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/cartogram.gif)

### Style Componets
Style components provide sensible defaults and quick opportunities for customization by optimizing the most common property changes for styles and packaging them into drop-down options, sliders, and toggles.
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/componets.png)

### Layers
Detailed breakdown of all the layers within the style
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/layers.png)

### Creating a map with your data
The easiest option is to select from one of the Mapbox-designed map styles or use your Cartogram to get started. Next, you will add a new layer and select your tileset that you created, or you can add a few Mapbox tilesets such as terrian or satellite.
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/addlayer.png)

Once you have added your tileset you now have several options to style the symbology of that layer.
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/customdata.png)

### Style with data conditions
Next we are going to add the <b>Neighborhood Food Retail</b> tileset 
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/style2.png)

Once you have added your layer you can filter that layer to only show features based on an attribute value by selecting the 'Style with data condtions' button 
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/style3.png)

### Choose a data field
Select the data field you want to filter by and set the values or conditions. In our example we are choosing <b>High_Poverty is Yes</b>
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/style4.png)

### Fallback Value
You'll also need to set the <b>Fallback Value</b> to have a transparency value of zero (0) so that the other features are hidden. This is the input box with an a that is right below the HSL/RGB selectors.
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/style5.png)

Then style your neighborhood food retail dataset 
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/style6.png)

### Layer Ordering
Arrange datsets within the Layers Table of Content so that the appear below text and other layers
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/style7.png)

### Publish
Once you are ready to share your visualization you'll click the `Publish` button. You can share this interactive map with anyone.
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/publish.png)

### Print
The other option is to <b>Print</b> your map. You have a few options for exporting your map as a jpg or png. 
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/print.png)

## Mapbox Resources

### Mapbox Studio Manual - https://docs.mapbox.com/studio-manual/overview/
This handy Mapbox Studio manual contains a comprehensive explanation of each section of Mapbox Studio, including general descriptions of individual components and detailed information on specific tools. It can be used either as a reference when using specific tools in Mapbox Studio, or as a way to understand the general pieces of how a Mapbox map is constructed.

### How to create a custom Mapbox map style using a template - https://www.mapbox.com/videos/how-to/create-a-custom-map-style-using-a-template/
[![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/video1.png)](https://www.mapbox.com/videos/how-to/create-a-custom-map-style-using-a-template/)

### Mapbox Storytelling - https://www.mapbox.com/solutions/interactive-storytelling
A simple way for journalists, designers, bloggers, and others to publish stories that combine narratives with map interactions. Allows creative minded people to weave interactive stories with images, maps, and compeling narritives.
[![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/mapboxstory.gif)](https://www.mapbox.com/solutions/interactive-storytelling)




