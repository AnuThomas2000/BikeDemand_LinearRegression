# Project Name
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. Hence it is taking the help of a consulting company to understand the factors on which the demand for these shared bikes depends. The bike sharing demand in American market for 2 years is used. A linear regression model was built using this dataset provided.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Data collected for the years: 2018 and 2019.
- Information related to weather situation, temperature and feeling temperature(in Celsius), Humidity, windspeed is available along with the dates and demand
- Details on the day on whether it's a working day or holiday and which day of the week and month is available.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- A linear regression model with a training accuracy of 90.2% and a test accuracy of 86.6% was built.
- The important features selected for the model using the RFE techinique as well as manual is : Casual, year, workingday, season, Feeling Temperature and WeatherSit
- There are variables providing the same information. In order to reduce multi-collinearity, only one of them need to be kept. Example temp and atemp. 
- The formula as per the model is
  Demand(cnt) = 4505.2671  +  692.3536(workingday)  +  426.8082(atemp)  +  1063.4212(casual) +  235.8335(season_summer)  +  279.4398(season_fall)  +  543.4504(season_winter) -  177.3723(weatersit_Misty) -  291.2680(weather_LightSnowRain)  +  792.8863(yr)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.12.5
- Numpy 2.0.1
- Pandas 2.2.2
- matplotlib 3.9.2
- seaborn 0.13.2
- SKLearn - 1.2.1
- Stats Model - 0.13.5  

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was authored by Anu Thomas

## Contact
Created by [@AnuThomas2000] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
