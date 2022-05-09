# Multiple Linear Regression - Bike Sharing Assignment
> This repository holds code to build a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- This assignment attempts to identify ‘key’ features that help business to predict the demand of shared bikes.
- It also creates a Multiple Linear Regression Model to predict the demand of shared bikes.
- It also includes a 'Linear Regression Subjective Questions - Solution.pdf' with answers to subjective questions, that are part of the assignment evaluation.
- This project is an assignment submission for Upgrad AI & ML course.
- The dataset used is the `day.csv(attached)` dataset provided by upgrad.


## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- statsmodels

## Conclusions
1. The business should focus on expansion before the month of september, since this is the month with highest demand.
2. Looking at the year on year trend, there is increase in demand. The business can expect increased demand during the coming years post pandemic.
3. There will be less demand during moderate weather(Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist) and bad weather conditions(Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds), so the business can focus on maintainance activities during this time.
4. During the weekday saturdays, demand is comparatively on the higher side. So the business should focus on making more bikes available on Saturdays.
5. The business should expect an increase in demand during the seasons of summer and winter.
6. The demand comparatively more during working days comparaed to holidays, so it is better to focus on workingdays for driving business decisions like advertisement and making more bikes available during working days.
7. The most significant features driving(both increasing as well as decreasing) business demand are:
    1. workingday.
    2. temp.
    3. windspeed.
    4. summer season.
    5. winter season.
    6. September month.
    7. Saturday.
    8. Moderate weather(Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist).
    9. Bad weather(Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds)
    