# Bike Sharing Regression Model
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
This regression model will help to predict demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. Management can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown ends. 
BoomBikes aspires to understand the demand for shared bikes among the people.
The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Conclusions
- The linear regression model explains approximately 80.2% of the variance in the dependent variable (R-squared = 0.802, adjusted R-squared = 0.797).
- The "const" coefficient (4044.92) is the estimated baseline value of "cnt".
- "yr" (year) has a strong positive influence, increasing "cnt" by about 2159.94 units per year.
- "workingday" increases "cnt" by 487.13 units, suggesting higher counts on working days.
- "windspeed" negatively affects "cnt" (coefficient -1578.30), indicating that higher wind speeds reduce "cnt."
- Seasonal effects like "spring" (-1639.31) and "winter" (-345.08) have negative coefficients, suggesting lower counts during these seasons.
- The months with positive coefficients
    -- August (Aug)
    -- June
    -- May
    -- September (Sept)
- Weather conditions "Light Snow" (-2677.30) and "Mist" (-813.89) substantially decrease counts.

## Technologies Used (Python Liberaries)
- Pandas
- Numpy
- Matplotlib
- Seaborn
- statsmodels
- sklearn

## Acknowledgements
- This project was based on US bike-sharing provider BoomBikes problem statement.
- Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


## Contact
Created by Tarun Garg
