# About the project

In this project we analyzed environmental factors like SMI, precipitation and vegetation development were analysed for the region of Sauerland and correlation between the factors were
investigated. This was done by data processing and data visualization using Python and QGIS.

## Overview of exercises guiding the investigation:

[Exercise 1](https://github.com/Komalks0212/Geoinformatics/tree/main/Ex_1) Generate a map of the main investigation area.  
[Exercise 2](https://github.com/Komalks0212/Geoinformatics/tree/main/Ex_2) Generate SMI maps of the counties of interest for the selected dates.  
[Exercise 3](https://github.com/Komalks0212/Geoinformatics/tree/main/Ex_3)  Generate precipitation video in QGIS.  
[Exercise 4](https://github.com/Komalks0212/Geoinformatics/tree/main/Ex_4)  Calculate cumulative precipitation time series.  
[Exercise 5](https://github.com/Komalks0212/Geoinformatics/tree/main/Ex_5)  Analyse cumulative precipitation vs. altitude (from DTM).  
Exercise 6 Discuss different SMI dynamics in Olpe and Hochsauerlandkreis.  
[Exercise 7](https://github.com/Komalks0212/Geoinformatics/tree/main/Ex_7)  NDVI  
[Exercise 8](https://github.com/Komalks0212/Geoinformatics/tree/main/Ex_8)  Dimension a roof drainage for two new industrial buildings.  

## Introduction

The Soil Moisture Index (SMI) is a product from the Drought Monitor of Umweltforschungszentrum Leipzig (UFZ). It classifies the soil moisture in soil moisture index classes (drought classes) according to the long-term local soil moisture distribution. The assignment of a particular soil moisture value to a soil moisture index is not fixed but depends on the history of the local soil moisture distribution over time. Example: A soil moisture of 10% (volumetric) might be classified as very dry at a usually wet location with a higher mean moisture over the last decades but classified as moderate at another location with lower mean moisture. Dimension a roof drainage for two new industrial buildings. You will investigate SMI, precipitation, terrain and vegetation development (expressed by the normalized difference vegetation index, NDVI) as well as potential dependencies among these quantities. The focus area of your investigation is the Sauerland, a hilly region in South-East Nordrhein-Westfalen.

The report will have the structure of a scientific report with a continuous narrative flow, even if we split the investigation in several exercises to guide you through the task.

The exercises are organized such that you can use their order to structure your report. Exercise 1 helps you to locate the area of study. You get an idea of the spatial distibution of climate stations with respect of the area of study in terms of longitude, latitude and altitude.

Then you start exploring the problem statement focussing on soil moisture. In Exercise 2 you will generate four maps displaying the change of soil moisture index (SMI) of the topsoil layer for the four sucessive months May, June, July, August 2017.

In Exercise 3 you will start exploring possible explanations for the SMI differences found by investigating the precipitation dynamics in NRW. You will produce a video with the QGIS TimeManager and try to determine the prevalent direction of moving rain fronts in June/July 2017.

Afterwards, you will use Exercise 4 to reduce your study area, by analyzing the two counties Olpe and Hochsauerlankreis with strong differences in SMI development during the time period analyzed.

You will then calculate cumulative precipitation time series to find out if this SMI behavior can be explained by the total amount of rain fallen in this region. Furthermore you will investigate how the total amount of precipitation is related to the altitude of the weather stations. You will use Exercise 5 to explore this approach.

After having collected all this data you will use Exercise 6 to start integrating and discussing your observations of SMI, precipitation and altitude.

The next two exercises will narrow your study area even more. In exercise 7 you will explore whether the SMI behavior is also reflected in the NDVI. For this you will only focus on three municipalities in Olpe county.

The final exercise 8 is related to precipitation but not to drought (a bit off-topic). Two new industrial buildings are planned in the county of Olpe. The water raining on the roofs of the buildings has to be drained.
