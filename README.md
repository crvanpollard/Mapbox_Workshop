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

## Visualizing data in CartoDB
### Style Wizard
CartoDB comes with some great map design tools that allow the user to pick from multple layer styles (simple, cluster, choropleth, category, bubble, torque, heatmap, intensity, and density).
![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/mapview_style.png)

### Infowindows
You can also turn on infowindows which allow users to click or hover over a feature and view specific attribute information. You, as the map maker, can select which attributes you allow your users to view.
![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/mapview_info.png)

### Filters
There is also a function that will allow you to set custom filters or parameters on your layer based off attribute information. For instance, in the map below, the filter is set to only show bicycle counts that have an `ADB` over 100.
![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/mapview_filter.png)

### CartoCSS
If you wish to have more advanced map styling you can do that with CartoCSS editor.
![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/mapview_cartocss.png)

### Creating a map of your data
Once you are ready to make a map you click the `Visualize` button and you will now have several map layout tools available. Here you can add a title, text, annotaion, and images, as well as, select from other map options.
![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/mapview_map.png)

## Publishing your visualization
### Time to share you map with the world
Once you are ready to share your visualization you click the `Publish` button. There are a few options to choose from such as: a link that you can send via email or social media, embed your map into a blog or website, or add it to an existing or custom web mapping applications using CartoDB.js.
![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/publish.png)

## Cartogram
Use Cartogram to create a map from your favorite photo's colors and then fine tune the rest of the design with Style Components - https://apps.mapbox.com/cartogram/
![alt text](https://raw.githubusercontent.com/crvanpollard/Mapbox_Workshop/master/img/cartogram.gif)

## CartoDB Resources
#### CartoCSS Reference Sheet - http://ebrelsford.github.io/talks/2014/Methods3/week7/materials/cartocss-reference.pdf
This handy CartoCSS Reference Sheet is a quick guide for beginners to CartoCSS

#### CartoDB Academy - http://academy.cartodb.com
The CartoDB Academy is great for recapping the basics, starting to use their APIs, and growing your design capabilities.
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/mapacademy.png)](http://academy.cartodb.com)

#### Odyssey - http://cartodb.github.io/odyssey.js/
A simple way for journalists, designers, bloggers, and others to publish stories that combine narratives with map interactions. Allows creative minded people to weave interactive stories with images, maps, and compeling narritives.
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/odyssey.png)](http://cartodb.github.io/odyssey.js/)

#### Preparing CSV files for use in CartoDB - https://vimeo.com/channels/cartodb/100105203
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/csv.png)](https://vimeo.com/channels/cartodb/100105203)

#### Using Column Join to Merge Tables - https://vimeo.com/channels/cartodb/100105201
[![alt text](https://raw.githubusercontent.com/crvanpollard/PWT2016_CartoDB/master/img/merge.png)](https://vimeo.com/channels/cartodb/100105201)


