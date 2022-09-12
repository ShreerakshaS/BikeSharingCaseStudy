# BIKE SHARING CASE STUDY

A brief description: A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

The objective is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 



## Table Of Contents:

* [General Info](#General-Information)
* [Technologies Used](#Technologies-Used)
* [Conclusions](#Conclusions)
* [Acknowledgements](#Acknowledgements)



## General-Information

BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

     - Which variables are significant in predicting the demand for shared bikes.
     - How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

Here we are using Bike Sharing Dataset.



## Technologies-Used:

- Jupyter Notebook(Anaconda 3) - version 6.4.8
- Python3 - version 3.10
- numpy - version 1.21.5
- pandas - version 1.4.2
- matplotlib - version 3.5.1
- seaborn - version 0.11.2
- sklearn
- statsmodels


## Conclusions:

Conclusions from the analysis-
- The top three features contributing significantly towards the demand of shared bikes are: 
           1.  Weathersit: Light rain_Light snow_Thunderstorm with negative coefficient 0.3045. 
           2.  Yr: 2018 year with positive coefficient 0.2468. 
           3.  Season: spring season with negative coefficient 0.1973.

- Some of the conclusions drawn from the categorical variables are:
           1. Season: Spring season has the lowest rentals and demand is high in fall. 
           2. Yr: We can see a significant increase in the bike rentals demand for the year 2019. 
           3. Mnth: The demand gradually increases from jan till sept and drops for the next 3 months. 
           4. Workingday: The number of rentals is high in workingday. 
           5. Weathersit: the rentals are highest in 'Clear_Few Clouds' weather condition and lowest in        'Lightrain_Light snow_Thunderstorm'. 
           6. Weekday: there is not much difference in rentals in the weekdays; however we can see Sunday has low rentals.



## Acknowledgements:

- This project was inspired by UpGrad Linear Regression Course
- References - google.com, quora.com, stackoverflow.com



## Contact:

Created by ShreerakshaS - feel free to contact me!