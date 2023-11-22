# COVID-19-Cases-in-Continental-United-States-for-Year-2020

## Introduction
This project focuses on analyzing and visualizing COVID-19 cases per 100,000 residents in continental United States as of April 21, 2020, using R programming. The analysis excludes data from Louisiana and Alaska.

## Objectives
- Visualize the spread of COVID-19 across various U.S. counties.
- Highlight the areas with the highest concentration of cases.

## Data Source
The analysis is based on data from `usmap.csv`, which contains information about COVID-19 cases in each county. Counties with small number of cases are ignored (threshold is 22). We calculated cases per 100000 residents.

## Tools and Technologies Used
- R Studio, R Markdown
- R Libraries: ggmap, ggplot2, dplyr

## Results
The map shows the continental United States with numerous circles of varying sizes scattered across it, indicating the number of COVID-19 cases per 100,000 residents in different counties as of a specific date. The larger the circle, the higher the number of cases in that county. The concentrations of cases seem to be higher in the eastern part of the country, with dense clusters visible in areas that likely represent major urban centers. The map is overlaid with a coordinate grid showing latitude and longitude, labeled 'lat' and 'lon' respectively.
