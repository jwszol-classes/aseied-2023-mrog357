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




# Code

### Overall idea
1. Download of necessary data from the database
2. Sorting data by coordinates
3. Calculating the altitude of every point
4. Calculating the altitude change trend
5. Presenting data on the map
#### Functions
1. 

# Results
