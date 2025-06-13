# TRELS-Project-Spring-2025

This Project was done by Yan Graf of the University of California, San Diego, with supervision with Dr. Gordon McCord of the University of California, San Diego's Global Policy School. 

The project is part of Tritons Research and Experiential Learning Scholarship, and seeks to analyze the economic value of Road construction using Night Time Lights data

This repository will contain all the code and information required to replicate the results found in the accompanying Research write-up. Due to Github's file size limitations, the actual files generated could not be uploaded.

The code required comes from two sources: 1. Python library OSMNX, and 2. Google Earth Engine (GEE) 

The code needed to download the data from OSMNX is provided in Code File.ipynb, and requires executing the first block. 

The code needed to download data from GEE is found on the GEE Script file. Simply copy and paste the script into a new GEE project, run the file, and save the resulting image to your google drive folder.

Running the necessary data transformations and calculations will require the user to set up directories for storage. Due to the data limitations on Github, no mock repository is provided. However, the repository can be set up however desired by simply changing the file paths on Code File. An outline of the suggested repository is found below.

**Files**
 - 2014
   - Road Network
   - Nighttime Lights Raster Points
 - 2015
   - Road Network
   - Nighttime Lights Raster Points
 - 2016
   - Road Network
   - Nighttime Lights Raster Points
 - 2017
   - Road Network
   - Nighttime Lights Raster Points
 - 2018
   - Road Network
   - Nighttime Lights Raster Points
 - 2019
   - Road Network
   - Nighttime Lights Raster Points
 - 2020
   - Road Network
   - Nighttime Lights Raster Points
 - 2021
   - Road Network
   - Nighttime Lights Raster Points
 - 2022
   - Road Network
   - Nighttime Lights Raster Points
 - 2023
   - Road Network
   - Nighttime Lights Raster Points
 - 2024
   - Road Network
   - Nighttime Lights Raster Points

Within each folder "Road Network", place the files from OSMNX and the resulting analyses. For the folder "Nighttime Lights Raster Points", add the GEE image and the shapefiles it is converted to. 

Next, there is "QGIS Workflow" to show how to do the QGIS portions of the project. There is also a shapefile included that includes the manually patched buffer geometry used for the QGIS portions. This should be downloaded and used for consistency. 

Finally, two QGIS files are included to visualize the results. While the files will not work unless the data has been generated, it does have all the visualization parameters pre-loaded. The user may want to install the QMS plugin to overlay the results on Google Maps satellite imagery. Visualization over time provides results from every year from 2014-2024, including a shapefile covering Egypt's New Administrative Capital's administrative boundaries used to generate a graph in the accompanying write-up. Sampling Error Comparison allows sampling error using different parameters to be examined. 
