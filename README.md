# Savior at Home

Data analysis of air quality change and mobility change in the US during COVID-19 pandemic. 

![Team-Logo](https://raw.githubusercontent.com/Savior-at-Home/source-code/master/icon.png)

## Contributor
Team Savior at Home, UCLA DataFest 2020  
Team member: Bingcui Guo, Wanxin Xie, Qing Shi  

## Introduction
Trying to stay optimistic during this challenging time, we started our project by wondering if this COVID-19 pandemic brings us any positive change. We were inspired by one research which claims that the decrease in mobility reduced carbon emission by a drastic 25 percent in China. This finding drove us to investigate the relationship between the mobility change and the air quality change in the US during the COVID-19 period. 

## Research Questions  
1. Is there a significant improvement in air quality level in the US before and after the outbreak of COVID-19? 
2. If there is any change in air quality levels, does the change vary by states? 
3. Is there a relationship between the mobility change in transit stations and air quality level? 
4. What are some factors influencing these trends? 


## Methodology
Our study is based on data analysis from Google COVID-19 community mobility reports and outdoor air quality data from United States Environmental Protection Agency. We used R to clean the data, implemented statistical testing, and used Tableau to visualize our results in order to conduct our analysis. 


## Tableau Visualization 
https://public.tableau.com/profile/violet.guo#!/vizhome/airqualitypercentagechange/airqualitypercentagechange?publish=yes
https://public.tableau.com/profile/violet.guo#!/vizhome/DataFest2020/transitmobilitychangebystate?publish=yes
https://public.tableau.com/profile/violet.guo#!/vizhome/airqualitybaseandchange/airqualitybeforeandafter?publish=yes

## Data Source
Google COVID-19 Community Mobility Reports: https://www.google.com/covid19/mobility/  
Outdoor Air Quality Data: https://www.epa.gov/outdoor-air-quality-data/download-daily-data

## Side Notes about Data
The COVID-19 Community Mobility data from Google show how visits and length of stay at different places change compared to a baseline. The visits data were collected by using aggregated and anonymized data from users who have opted in to Google Location History. The baseline is calculated by using the median value, for the corresponding day of the week, during Jan 3 to Feb 6. To represent mobility data for COVID-19 period, we selected data from Mar 21 to May 1. Similarly, we process our air quality data to show its change compared to the baseline, which is calculated using the same method as described before.
