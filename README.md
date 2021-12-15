# Multiple Linear Regression Model For The Prediction Of Demand For Shared Bikes
 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)




## General Information

* Problem Statement

  A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

  In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

* The company wants to know:

* Which variables are significant in predicting the demand for shared bikes.
* How well those variables describe the bike demands.

* Business Goal:
To model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Conclusions
As per our final Model, the top 3 predictor variables that influences the bike booking are:

    * Temperature (temp) - A coefficient value of ‘0.441121’ indicated that a unit increase in temp variable increases the bike hire numbers by 0.441121 units. 

    * Weather Situation 3 (weathersit_Light_Snow_Rain)(Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered) - A coefficient value of ‘-0.328180’ indicated that, w.r.t Weathersit_3, a unit increase in Weathersit_3 variable decreases the bike hire numbers by 0.328180 units.

    * Year (yr) - A coefficient value of ‘0.231005’ indicated that a unit increase in yr variable increases the bike hire numbers by 0.231005 units.

* Variables significant in predicting the demand for shared bikes are :

Temp
Season: Spring(-ve),  Winter(+ve)
Months: Dec,  Jul, Nov [all -ve] ; Mar, Sep[both +ve]
Year:  2019
Weather  Situation: Light Snow, Light Rain + Thunderstorm + Scattered clouds [-ve] 


## Technologies Used

- Python - version 3.0
- Numpy
- Pandas
- Seaborn
- Matplotlib
