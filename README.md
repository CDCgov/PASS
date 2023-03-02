# PASS - Data Curation  
Polio and Picornavirus Laboratory Branch (PPLB)

This folder contains the necessary scripts and data files to scrape, geolocate, and process data from the National Center for Biotechnology Information (NCBI). 
## Installation

The following libraries need to be installed to run the scripts: 

```bash 
python version -3.10.6 up
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




## First Step

run 'NCBI_webScrape.ipynb'

## Second Step

run 'Fuzzy_match.ipynb'

## Third Step

run 'geolocator_google_API.ipynb'

