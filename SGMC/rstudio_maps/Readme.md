## Rmaps Folder

The Rmaps folder contains files and R scripts needed to build the US and global heatmaps provided as PDF files. The maps show the number of accessions submitted to NCBI from each country and the corresponding number of centers from each country that submitted the accessions. 

## R Packages

fiftystater
dplyr
readxl
ggplot2

## Data Folder 
The data folder includes necessary excel spreadsheets and R scripts to create the maps. 

## Fiftystater_submissions: 
    excel spreadsheet containing data from the Fifty_stater R package to build the US map. The total number of submissions (column name: sample) from each country was added. 
## Rworldmap_submissions: 
    excel spreadsheet containing mapping data to build world map from the rworldmap R package. The total number of submissions (column name: sample) from each country was added. 
## Us_centercount: 
    excel spreadsheet containing the total number of centers in each state that submitted to NCBI in the US. Used to build the data points showing the number of centers in each state.
## World_centercount: 
    excel spreadsheet containing the total number of centers in each country that submitted to NCBI. Used to build the data points showing the number of centers in each country.
## Rmaps.rmd: 
    R markdown file containing scripts used to build the US and world heatmaps. 

Maps were exported as PDF files using US legal 8.50x14.00 inches, orientation: portrait. 
