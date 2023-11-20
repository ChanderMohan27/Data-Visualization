# Crime in India: State-wise Analysis - Data Visualization

## Overview

Crime in India is a pressing concern that demands thorough analysis and understanding. This data visualization project aims to conduct a State-wise Crime Analysis for the Year 2017. By utilizing R for data visualization, we intend to provide a comprehensive overview of crime statistics across different states in India, uncovering valuable insights from the data.

## Explore the Interactive Project Slides

[Click here to interact with the Data Analysis Slides](https://rpubs.com/Chander26/1035407).

## R Language 

Here we are using R language  for reprocessing and plotly library to do data visualization you can go though with the R markdown file to get a clear understanding 

## Objective 

The primary objective of this analysis is to explore and visualize the patterns and prevalence of crime in India. Additionally, we seek to understand the potential factors influencing crime rates by comparing them with the unemployment rate and other relevant factors. The insights derived from this analysis can contribute to a better understanding of the issue and facilitate the formulation of effective strategies for crime prevention.

## Data Sources

The data for this analysis is sourced from India Government website. It includes crime statistics and additional factors that may influence crime rates in various states.

In this project we used Data from offical website of "data.gov.in"  that contains the crime data of different years. Link to download the csv files are following 

[Sate-wise-crime-data-2016](https://data.gov.in/resource/stateut-crime-head-wise-violent-crimes-incidence-during-2016).
[Sate-wise-crime-data-2017](https://data.gov.in/resource/stateut-crime-head-wise-violent-crimes-during-2017).
[Sate-wise-crime-data-2018](https://data.gov.in/resource/stateut-crime-head-wise-violent-crimes-during-2018).
[Sate-wise-cases-registered-against-police-personnel-data-2017](https://data.gov.in/resource/stateut-wise-cases-registered-against-police-personnel-during-2017).
[Sate-wise-unemployment-data-2017-18](https://data.gov.in/resource/stateut-wise-unemployment-rate-usual-status-psss-age-group-15-29-years-during-2017-18).



## Methodology

### 1. Data Preprocessing

The initial step involves cleaning and preprocessing the data to ensure its accuracy and reliability. This includes handling missing values, standardizing formats, and ensuring data consistency.

### 2. Exploratory Data Analysis (EDA)

EDA will be conducted to understand the distribution of crime across states and identify potential trends or patterns. This phase sets the foundation for meaningful visualizations.

### 3. Data Visualization

Using R and relevant packages for geospatial data visualization, we will create interactive maps and graphs to represent crime statistics across different states. The visualizations will be designed to provide an intuitive understanding of the crime scenario in India.

## How to Replicate

To replicate this analysis and generate the visualizations, follow these steps:

1. **Data Download:** Download the dataset from the provided references.

2. **Install R Packages:** Ensure that the required R packages are installed. You can do this by running the following commands in R:

   ```R
   library(flexdashboard)
    library(ggplot2)
    library(dplyr)
    library(plotly)
    library(forcats)
    library(tidyr)
    library(rgeos)
    library(maptools)
    library(ggmap)
    library(broom)
    library(leaflet)
    library(maps)
    library(sf)
    library(ggthemes)
   
3.  **SetYour Working directory:**  provide the path while reading the csv. 
    ```R
    # Specify the path to your desired working directory
    new_working_directory <- "/path/to/your/directory"

    # Set the working directory
    setwd(new_working_directory)

    crime_2016<- read.csv("name-of-csv-file.csv")

4.  **Run R markdown File:**  After editing the working directory of data 
    Click on the  "knit" option at the Top of the bar and it will run the code and open the Sidies by runing R file. 

    
