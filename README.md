# Urban Heat and Vegetation Change in Zurich between 1985 and 2024

## Project Description
This project analyzes and seeks to understand long term changes in surface temperature and vegetation in Zurich using Landsat imagery. Specifically, it investigates the relationship between land surface temperature (LST) and vegetation density (NDVI) between 1985 and 2024.

## Data Sources
The dataset for this project was provided in the course materials. 
- The course server provided: course/sds210/data/projects/project_3/
- The Google Drive link for the data: https://drive.google.com/drive/folders/1SmEzlCAJJGYY-TdB58JX6ADvVxSQrMqj
This dataset contains Landsat composite imagery for Zurich every three years between 1985 and 2024.

## Setup instructions
 To reproduce this project:
 1. Download the dataset from Google Drive
 2. Create the following folder structure: data/Project_3_time-series/
 3. Place all .tif raster files into this folder
 4. Install the following required Python libraries: rasterio, numpy, pandas, matplotlib, scipy

## Execution Order
 1. Download or clone the repository
 2. Download the dataset from the course server or Google Drive
 3. Place the dataset in: data/Project_3_time-series/
 4. Open the Jupyter Notebook: urban_heat_analysis.ipynb 
 5. Run all cells from top to bottom 