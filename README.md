
# Linear Regression Assignment - Shared Bikes Demand Case Study
> This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes. 


## Table of Contents
* [Problem Statement](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, **BoomBikes** aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.



They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

-   Which variables are significant in predicting the demand for shared bikes.
-   How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

**Business Goal:**  
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
-   Python : 3.11.7
-   Pandas : 2.1.4
-   numpy : 1.26.4
-   matplotlib: 3.8.0
-   seaborn : 0.12.2
-   plotly : 5.9.0
-   statsmodels : 0.14.0
-   scikit-learn : 1.2.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
- Comparing the years 2018 and 2019, **most bike rentals happened in the year 2019**
- Most bikes are rented during **Fall Season** and the least during **Spring Season**
- Most bikes are rented during **Clear Weather** followed by **Mist + Cloudy, Light Snow**
- Most bike rentals happen during the month of **September**
- Most bikes are rented during **non-holiday** days
- Most bikes are rented on **Thursday** compared with other weekdays.
- We can conclude that the equation of our best-fitted line is,
_**cnt** = **(0.4033 x temp)** + **(0.0646 x winter)** + **(0.2352 x (year 2019))** + **(0.0533 x sep.)** + **(0.0204 x sun.)** + **(-0.0880 x holiday)** + **(-0.1563 x windspeed)** + **(-0.1033 x spring)** + **(dec. x -0.0520)** + **(-0.0562 x jan)** + **(-0.0649 x jul.)** + **(-0.0484 x nov.)** + **(-0.2954 x light snow.)** + **(-0.0813 x (mist + cloudy.))**_
- The calculated R-squared Score is **0.8162**
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Acknowledgements

- https://en.wikipedia.org/wiki/Linear_regression
- https://en.wikipedia.org/wiki/Anscombe%27s_quartet
- https://en.wikipedia.org/wiki/Pearson_correlation_coefficient
- https://www.wallstreetmojo.com/pearson-correlation-coefficient/
- https://www.youtube.com/watch?v=Ftp3mmItV-k

## Contact
Created by @Ishkhan


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
