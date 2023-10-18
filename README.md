# LST-GEE and Jupyter Notebook
This GEE code retrieves LST for the study area (Ethiope East and West) in selected towns in Nigeria from 2001 to 2021. 
Landscape spectral indices (e.g., NDVI, NDWI, NDBI, NDSI) were computed and used as independent parameters to predict LST. 
We developed a regression model to estimate the predictive capacity of the independent variables over the dependent variables. 
The machine learning model was executed in Jupyter Notebook.
LST retrieval and spectral indices computation were performed in Google Earth Engine.
NB: For the shapefiles of the study area, it was sourced from open-source ESRI website and added as an asset in GEE. So to replicate this, you need to download the shapefile and add as an asset.
