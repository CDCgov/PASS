# SGMC Pipeline

Welcome to the SGMC Pipeline repository! This Python-based information-retrieval application aims to automate and streamline the process of collecting and curating geospatial metadata from the NCBI SRA (Sequence Read Archive). The pipeline consists of four main steps: data retrieval, web scraping, institution identification, and location identification.

## Prerequisites

To use the SGMC Pipeline, you will need the following:

- Python version: 3.10.6
- R version: 4
- Jupyter Notebook

The following keys are also required at various points in the pipeline.  Instructions on how to generate each key are included in the notebook file where each one is required:

- Google Service Account Key
- AWS Credentials Access Key  
- OpenAI API key

## Installation options

### **Installation via pip**

To get started with the SGMC Pipeline, follow these steps:

1. Navigate to the directory where you want to install the repository, and then clone the repository to your local machine:

```shell
$ git clone https://github.com/CDCgov/PASS.git
```

2. Navigate to the repository directory:

```shell
$ cd PASS/SGMC
```

3. Install the required dependencies:

```shell
$ pip install -r requirements.txt
```
### **Installation via [Poetry](https://python-poetry.org/docs/basic-usage/)**

To get started with the SGMC Pipeline, follow these steps:

1. Navigate to the directory where you want to install the repository, and then clone the repository to your local machine:

```shell
$ git clone https://github.com/CDCgov/PASS.git
```

2. Navigate to the repository directory:

```shell
$ cd PASS/SGMC
```

3. Install the Poetry:

```shell
$ pip install poetry
```
4. Activate the enviroment:

```shell
$ poetry shell
```

5. Create jupyter kernel:

```shell
$ poetry run ipython kernel install --user --name=sgmc_kernel
$ jupyter notebook
```
And then select the created kernel in “Kernel” -> “Change kernel” -> "sgmc_kernel".  Make certain that the "sgmc_kernel" is selected in each notebook file.

## Usage

The SGMC Pipeline consists of several Jupyter Notebook files that represent each step of the pipeline. Here's a brief description of each file:

- `00_GCP_SRA_Cloud_metadata.ipynb` and `00_AWS_SRA_Cloud_metadata.ipynb` : These notebooks handle the preliminary SRA in the cloud data retrieval. Options `GCP` and `AWS`.

- `01_NCBI_webScrape.ipynb`: This notebook handles the data retrieval and web scraping process to extract relevant information from the NCBI SRA.

- `02_ChatGPT_API_Institution Imputation.ipynb`: This notebook utilizes the ChatGPT API for institution identification. It leverages artificial intelligence to curate and update geospatial metadata.

- `03_rmaps.ipynb`: This notebook runs R code to performs map generation from in this pipeline geospatial metadata.

Please note that the `data` directory contains the data files necessary for the pipeline execution, and the `rstudio_maps` directory stores the generated map visualization.

Feel free to customize and modify the pipeline as per your specific requirements. You can add additional steps or modify the existing ones to suit your needs.

## Acknowledgments

This pipeline is developed to automate the geospatial metadata curation process. The study demonstrates the effectiveness of the pipeline in saving human efforts, reducing errors, and improving the quality of public data.

**Note:** This README provides an overview of the SGMC Pipeline and how to use it. For more detailed instructions, refer to the individual notebook files and their corresponding documentation within the repository.
