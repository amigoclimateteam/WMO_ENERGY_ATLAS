# DEM Data

This folder is dedicated to the products derived from **Digital Elevation Models (DEMs)**.  
For storage reasons, the files themselves are not included here but can be accessed in the shared drive at the following link: https://drive.google.com/drive/folders/1frbtl0kBfv89CsfdVoFQbHnYptvBCYWt.  

## Available datasets

- **ERA5-Land resolution (9 km):**  
  One of the files enables the retrieval of *orography* and *aspect* at the ERA5-Land resolution (9 km).  
  This is obtained by processing the geopotential NetCDF file using the methodology implemented in the notebook  
  `1.0_Orography_processing.ipynb`, saving the outputs first as GeoTIFF and then as NetCDF.  

- **Country-level GeoTIFFs (90 m):**  
  Additional DEM files, divided by country, are GeoTIFF images downloaded from **OpenTopography**.  
  They contain the orography of the selected areas at a spatial resolution of 90 m.  
  Using the same notebook (`1.0_Orography_processing.ipynb`), it is possible to calculate the *aspect* and save the resulting datasets in NetCDF format.  
