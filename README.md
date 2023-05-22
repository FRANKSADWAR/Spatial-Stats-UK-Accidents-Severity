# Spatial Statistical Analysis of Road Accidents Severity in UK

Road accidents are a menace to munipal councils, towns and cities in general. The UK 
is not an exception in this perspective. 
The data used is a record of accidents from 2005 to 20007, 2009 to 2011, and 2012 to 2014, an epoch of two years each.

This notebook is a comprehensive analysis of road accidents in the UK and it's LSOA's.

The data presented is point data, having over 2 million data points spread accross the UK.

The first step in analysing any such big data is data cleaning. This involved eliminating the 
null values from the data frame.

The data was then geo-referenced to WGS 84 (EPSG:4326) and overlayed on-top of the UK's LSOA polygon data.

## Data Visualization Techniques

1. KDE (Kernel Density Estimator)
2. Hex-bins
3. Data shader


## Questions
1. What is the epicenter(s) of road accidents in the UK ? 
2. How are the point-patterns spread across space ? 
3. What is the measure of dispersion of the road accidents ?
4. What is the pattern portrayed with the spread of road accidents in the UK ?
5. What LSOA' in the UK have the highest road accidents, lowest cases of road accidents and how do they compare to the neighboring LSOAs ? 
6. What is th correlation of the road accidents variables and the road acceident prevalance ?

## Analysis Carried out

1. Measure of centography

![/home/billy/Documents/BigData_analysis/Screenshot from 2023-05-22 12-44-33.png]
2. Measure of dispersion
3. Clustering analysis: K-Means and Spatial DBSCAN
4. Spatial auto-correlation (Global and Local Moran's I)
5. Spatial Regression