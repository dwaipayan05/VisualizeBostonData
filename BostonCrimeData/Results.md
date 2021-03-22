# Boston Crime Data Report

## Overview
The aim is to conduct a exploratory data analysis between the crimes that occured in Boston from 2015 - 2018 based on various aspects. It also displays how the crime has changed over the years and how it is divided across the city based on various offenses.

## Python Libraries Used

- Data Handling :- numpy, pandas, scipy
- Plotting : - plotly, cuffinks, folium, chart_studio, seaborm
- Miscellaneous : - os, sys

## Dataset Used
Crime incident reports are provided by Boston Police Department (BPD) to document the initial details surrounding an incident to which BPD officers respond. This is a dataset containing records from the new crime incident report system, which includes a reduced set of fields focused on capturing the type of incident as well as when and where it occurred. Records in the new system begin in June of 2015. You can find more about the dataset from [here](https://data.boston.gov/dataset/crime-incident-reports-august-2015-to-date-source-new-system)

## Plots Obtained

**Distribution Of Total Number of Crimes Between 2015 - 2018**
![](https://github.com/dwaipayan05/VisualizeBostonData/blob/main/BostonCrimeData/PyPlot%20Snapshots/CrimeDistribution(15-18).png)

**Distribution Of Total Number of Crimes Based on Year & UCR Part**
![](https://github.com/dwaipayan05/VisualizeBostonData/blob/main/BostonCrimeData/PyPlot%20Snapshots/CrimeDistribution(Pie).png)

**Top 25 Crimes that Happened In Boston**
![](https://github.com/dwaipayan05/VisualizeBostonData/blob/main/BostonCrimeData/PyPlot%20Snapshots/Top25Crimes.png)

**Distribution of Crime Cases in Boston Around City Based on OFFENSE CODE**
<p style="text-align:center;"><img src="https://github.com/dwaipayan05/VisualizeBostonData/blob/main/BostonCrimeData/PyPlot%20Snapshots/Crime%20by%20Offense.gif" alt="GIF"></p>

**Hourly Crime Rate in Distribution Across Various UCRs**
![](https://github.com/dwaipayan05/VisualizeBostonData/blob/main/BostonCrimeData/PyPlot%20Snapshots/HourlyUCR.png)

**Tree Map of Crime Distribution Based on Count (Sunburst Using PyPlot)**
![](https://github.com/dwaipayan05/VisualizeBostonData/blob/main/BostonCrimeData/PyPlot%20Snapshots/CrimeDistribution(TreeMap).png)

**Spatial Distribution of Map Across Each District in Boston (Using Matplotlib)**
![](https://github.com/dwaipayan05/VisualizeBostonData/blob/main/BostonCrimeData/PyPlot%20Snapshots/MatplotLibSpatialScatter.png)

## Interactive Plots Obtained

**Heat Map of Crime Counts Across Boston (Using PyPlot)**
<p style="text-align:center;"><img src="https://github.com/dwaipayan05/VisualizeBostonData/blob/main/BostonCrimeData/PyPlot%20Snapshots/PyPlot%20Heat%20Map.gif" alt="GIF"></p>

**Cluster Map of Crime Counts Across Boston (Using folium)**
<p style="text-align:center;"><img src="https://github.com/dwaipayan05/VisualizeBostonData/blob/main/BostonCrimeData/PyPlot%20Snapshots/Folium%20Cluster%20Map.gif" alt="GIF"></p>

**Heat Map of Crime Counts Across Boston (Using folium)**
<p style="text-align:center;"><img src="https://github.com/dwaipayan05/VisualizeBostonData/blob/main/BostonCrimeData/PyPlot%20Snapshots/Folium%20Heat%20Map.gif" alt="GIF"></p>

**Bubble Map of Crime Counts Across Boston (Using folium)**
<p style="text-align:center;"><img src="https://github.com/dwaipayan05/VisualizeBostonData/blob/main/BostonCrimeData/PyPlot%20Snapshots/Folium%20Bubble%20Map.gif" alt="GIF"></p>
