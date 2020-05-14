# Savior at Home

Data analysis of air quality change and mobility change in the US during COVID-19 pandemic. 

## Contributor
Team Savior at Home, UCLA DataFest 2020
Team member: Bingcui Guo, Wanxin Xie, Qing Shi

## Inspiration
Since the outbreak of COVID-19, we’ve been surrounded by horrible news about this global pandemic and its negative influences on various aspects of our lives. Trying to find the positivity in this challenging time, we started our project by wondering if this pandemic brings us any positive change. We began our brainstorming by reflecting on the biggest change in our lives caused by this pandemic. As college students who have to stay at home and study online, we agreed that the reduction of mobility has the most significant impacts on our lives and decided to explore if there are any positive side-effects of the stay-at-home order. After browsing through recent scholarly papers, we were inspired by one research from China, which claims that the reduction of mobility reduced carbon emission by a drastic 25 percent in China. This finding drove us to investigate the mobility change in the US and the corresponding change in air quality before and during the COVID-19 period. 

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
