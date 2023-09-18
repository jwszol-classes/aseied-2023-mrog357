# About the Project
### Our Problem
Perform an analysis of data containing information on terrain elevation differences by selecting groups of areas with the highest increases (continent: Europe). The elevation increase in a given location should be measured based on at least 10 measurement points. Determine 5 groups of areas based on the average elevation increase values. Please plot the detected regions on a map.
### Requirements
* Technology used: EMR/Spark
* Python (libraries)
```
sc.uninstall_package('pip')
sc.install_pypi_package("pip==22.2.2")
sc.install_pypi_package("opencv-python")
sc.install_pypi_package("numpy")
sc.install_pypi_package("matplotlib")
```

### Dataset
Mapzen Terrain Tiles provides worldwide base map coverage sourced from open data projects with several different data formats and varying levels of processing.
The following formats are available:
* `terrarium` with extension `png` in Web Mercator projection, contains raw elevation data in meters, split into the RGB channels, with 16 bits of integer and 8 bits of fraction
* `normal` with extension `png` in Web Mercator projection, tiles are processing elevation data with the RGB values corresponding to the direction the pixel “surface” is facing (its XYZ vector)
* `geotiff` with extension `tif` in Web Mercator projection, tiles are raw elevation data suitable for analytical use and are optimized to reduce transfer costs
* `skadi` with extension `hgt` in unprojected latlng, tiles are raw elevation data in unprojected WGS84 (EPSG:4326) 1°x1° tiles, used by the Mapzen Elevation lookup service


# Code

### Overall idea
1. 

# Results
