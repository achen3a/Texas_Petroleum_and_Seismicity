# Texas Petroleum and Seismicity
An exploratory analysis of the relationship between petroleum production and seismic activity in Texas.

## Overview
Combines Texas crude oil production with earthquake records to investigate how seismic activity has changed alongside petroleum production.
Analysis include:
- Exploratory data analysis (EDA)
- Chi-square hypothesis testing
- Linear regression analysis and testing

## Data
The petroleum data can be found from [US Energy Information Administration](https://www.eia.gov/dnav/pet/hist/LeafHandler.ashx?n=pet&s=mcrfptx2&f=a) and the earthquake data can be found from [USGS Earthquakes](https://earthquake.usgs.gov/earthquakes/map/?extent=5.52851,-128.32031&extent=51.89005,-72.24609&range=search&timeZone=utc&map=false&search=%7B%22name%22:%22Search%20Results%22,%22params%22:%7B%22starttime%22:%221800-01-01%2000:00:00%22,%22endtime%22:%222026-05-21%2023:59:59%22,%22maxlatitude%22:37.132,%22minlatitude%22:25.483,%22maxlongitude%22:-93.162,%22minlongitude%22:-107.316,%22minmagnitude%22:2.5,%22orderby%22:%22time%22%7D%7D).

## Tools
Python · Pandas · NumPy · SciPy · Matplotlib · Jupyter

## Results
The analysis finds a significant positive correlation between petroleum production and earthquake frequency, as well as a significant negative correlation between petroleum production and average earthquake magnitude. These results show correlation, not causation. 
