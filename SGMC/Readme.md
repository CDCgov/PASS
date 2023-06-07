## Data Curation Folder 

This folder contains the necessary scripts and data files to scrape, geolocate, and 
process data from the National Center for Biotechnology Information (NCBI). 



# Install all Packages
 
1. Install the required dependencies:

```shell
$ pip install -r requirements.txt
```

# Files 

NCBI_webScrape.ipynb: A Jupyter Notebook script for scraping data from the NCBI website. 

geolocator_google_API.ipynb: A Jupyter Notebook script for geolocating institutions based on their addresses using Google Maps API. 

ChatGPT_API.ipynb: 

sample_data.csv: A sample dataset with 30 records used for testing the scraping and geolocation scripts. 

Globe-institution_data.csv: A dataset containing geolocated institutions from around the world. Read.me: This file. 

#  Required Libraries:

The following libraries need to be installed to run the scripts: 

beautifulsoup: pip install beautifulsoup 
tqdm: pip install tqdm 
googlemaps: pip install googlemaps 
folium: pip install folium 

# API Key 
An API key is required to use the Google Maps API. To obtain one, 
follow the instructions on the Google Maps API website. Once you have 
obtained an API key, store it in a secure location and use it in 
the geolocator_google_API.ipynb script where indicated. 

# Geocoding Libraries 


The following libraries are used for geocoding: 

Nominatim: Installed as part of the geopy library. To install, run pip install geopy. 
GoogleV3: Installed as part of the googlemaps library. To install, run pip install googlemaps. 


# First Step
run '01_NCBI_webScrape.ipynb'

This Python script extracts specific data from the NCBI (National Center for Biotechnology Information) website using web scraping techniques. The script pulls data related to the Submitted_by, ID, Biosample_Submission, and Bioproject_Submission fields for a given set of accession numbers (Acc).

# Second Step

run '02_ChatGPT_API_Institution Imputation.ipynb'

# Third Step

run '03_geolocator_google_API.ipynb'
