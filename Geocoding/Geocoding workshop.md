# Geocoding workshop

https://github.com/StanfordGeospatialCenter/SGC-Workshop-Series/blob/main/Geocoding/Geocoding%20workshop.md 

## Getting Ready

### Data Download

https://raw.githubusercontent.com/mapninja/Earthsys144/master/data/SantaClara_TattooParlors.csv


### Software Installation

If you would like to follow along with the "hands-on" sections of this workshop, you will need the following software:

* QGIS (PR)
* OpenRefine

## Overview of the Geocoding Process

### Slides
https://slides.com/staceymaples/geocoding-101/ 

### Tour of locator.stanford.edu

## Desktop Software Geocoding

### Hands-on with ArcGIS Online Geocoding

#### Limitations

#### Uploading to ArcGIS Online

#### Service Areas in ArcGIS Online

### Geocoding Workflows in ArcGIS Pro

#### Requirements

Where to get ArcGIS Pro: 

You can login to https://stanford.maps.arcgis.com using your SUNETID and password. Once you have logged in, you should be able to follow these directions to download ArcGIS Pro for installation on your own Windows Machine: https://support.esri.com/en/technical-article/000025335 

#### Geocoding with ArcGIS Pro from the ArcGIS.com World Geocoder

#### Geocoding with ArcGIS Pro from the locator.stanford.edu service

### Demonstration of Geocoding with MMQGIS 

#### Installing plugins in QGIS
#### Getting the right URL for the geocoding service
`https://locator.stanford.edu/arcgis/rest/services/geocode/USA/GeocodeServer/findAddressCandidates`

Be sure to save your output files to a real folder!

Note the terrible feedback on the progress of the geocoding job!

## Geocoding with APIs

### Hands-on Geocoding with OpenRefine and the locator.stanford.edu API

https://github.com/mapninja/Earthsys144/blob/master/Labs/Week_07/Geocoding_with_Locator.md


#### Intro to Open Refine & Creating a Project

#### Building a GET Request using the browser

#### Data Docs
https://locator.stanford.edu/NA2021.4/helpcontents/index.htm

Start at https://locator.stanford.edu/arcgis/rest/services/geocode/USA/GeocodeServer/findAddressCandidates 

## More Geocoding Resources

### Geocoding Crash Course
http://mapninja.github.io/Tutorial-Geocoding-Crash-Course/

With info about building custom geocoders, from your own data, as well as using Geocoding APIs other than locator

### Data Docs
https://locator.stanford.edu/NA2021.4/helpcontents/index.htm

### ArcGIS Server REST API
https://locator.stanford.edu/arcgis/sdk/rest/index.html#/Geocode_Addresses/02ss00000040000000/

### Python
A mostly working Python Notebook:
https://github.com/StanfordGeospatialCenter/SGC-Python-Geocoder 

### R
Claudia Engel's excellent R Geocoding repo:
https://github.com/cengel/ArcGIS_geocoding

### Other APIs

#### Geonames.org
http://www.geonames.org/ - Excellent free geocoder + with CC licensing  
https://www.geonames.org/export/ws-overview.html


#### Geo-locate.org
For working with biodiversity and specimen collection locations. Good at esoteric localities ("5km north of Stanford")
https://www.geo-locate.org/
JSON API Wrapper:
http://www.geo-locate.org/files/glcJSON.pdf




