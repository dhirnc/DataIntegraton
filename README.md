Environment: Python 3.6.5 and Jupyter notebook 

Libraries used:

pandas - for dataframe manipulation
shapefile - to read shapefiles
geopandas - to read and manipulate shapefile for co-ordinate reference system
matplotlib (for plotting)
math - for mathematical functions
Sklearn libraries - for data transformation and fitting linear model
This analysis deals with Data Integration and Reshaping problems for Property data.

Task 1:The goal of the analysis is to find several relavant commute details about properties using GTFS data provided. 

Task 2: The goal of the analysis is to study the effect of different normalization/transformation methods (i.e.standardization, min-max normalization, log, power, and root transformation) on Rooms,crime_C_average, travel_min_to_CBD, and property_age attributes. Also need to observe and explain their effect assuming that we want to build a linear model on price using these attributes as the predictors of the linear model and recommend which one(s) do you think would work better on this data. When building the linear model, the same normalization/transformation method can be applied to each of these attributes.