# PASS - Data Curation  
Polio and Picornavirus Laboratory Branch (PPLB)

This folder contains the necessary scripts and data files to scrape, geolocate, and process data from the National Center for Biotechnology Information (NCBI). 
## Installation

The following libraries need to be installed to run the scripts: 

```bash 
beautifulsoup: pip install beautifulsoup 
tqdm: pip install tqdm 
googlemaps: pip install googlemaps 
folium: pip install folium 
```
The following libraries are used for geocoding: 
```bash 
Nominatim: Installed as part of the geopy library. To install, 
            run pip install geopy. 
GoogleV3: Installed as part of the googlemaps library. To install, 
            run pip install googlemaps. 
```
## API Reference


An API key is required to use the Google Maps API. To obtain one, follow the instructions on the Google Maps API website. Once you have obtained an API key, store it in a secure location and use it in the geolocator_google_API.ipynb script where indicated. 



## Natural Language Processing 

The scripts make use of Natural Language Processing (NLP) techniques to perform fuzzy matching between datasets. The necessary NLP libraries and modules will be imported as needed in the Fuzzy_match.ipynb script.
