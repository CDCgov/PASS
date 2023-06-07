# SGMC Pipeline

Welcome to the SGMC Pipeline repository! This Python-based information-retrieval application aims to automate and streamline the process of collecting and curating geospatial metadata from the NCBI SRA (Sequence Read Archive). The pipeline consists of four main steps: data retrieval, web scraping, institution identification, and location identification.

## Prerequisites

To use the SGMC Pipeline, you will need the following:

- Python v3
- OpenAI API key.
- Google Maps API key.

## Installation

To get started with the SGMC Pipeline, follow these steps:

1. Clone the repository to your local machine:

```shell
$ git clone https://github.com/CDCgov/PASS.git
```

2. Navigate to the repository directory:

```shell
$ cd SGMC
```

3. Install the required dependencies:

```shell
$ pip install -r requirements.txt
```

## Usage

The SGMC Pipeline consists of several Jupyter Notebook files that represent each step of the pipeline. Here's a brief description of each file:

- `01_NCBI_webScrape.ipynb`: This notebook handles the data retrieval and web scraping process to extract relevant information from the NCBI SRA.

- `02_ChatGPT_API_Institution Imputation.ipynb`: This notebook utilizes the ChatGPT API for institution identification. It leverages artificial intelligence to curate and update geospatial metadata.

- `03_geolocator_google_API.ipynb`: This notebook performs location identification using the Google Geocoding API. It helps in standardizing and enriching the geospatial metadata.

- `04_Map_Visualization.ipynb`: This notebook allows you to visualize the curated geospatial metadata on a map.

Please note that the `data` directory contains the data files necessary for the pipeline execution, and the `rstudio_maps` directory stores the generated map visualization.

Feel free to customize and modify the pipeline as per your specific requirements. You can add additional steps or modify the existing ones to suit your needs.

## Acknowledgments

This pipeline is developed to automate the geospatial metadata curation process. The study demonstrates the effectiveness of the pipeline in saving human efforts, reducing errors, and improving the quality of public data.

**Note:** This README provides an overview of the SGMC Pipeline and how to use it. For more detailed instructions, refer to the individual notebook files and their corresponding documentation within the repository.