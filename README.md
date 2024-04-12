# BOOM BIKE SHARING  - LINEAR REGRESSION ASSIGNMENT
*********************************************************
A Mutiple Linear Regression Assignment with RFE and MinMax Scaling
**********************************************************
## Introduction
This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes. You will need to submit a Jupyter notebook for the same.
***********************************************************
## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.
**********************************************************
## Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
***********************************************************
## Table of Contents
* [Introduction](#general-information)
* [Problem Statement](#problem-statement)
* [Business Goal](#business-goal)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1  - Equation of best fit line is <br>
**Demand  =  0.08 + 0.23 x yr + 0.06 x workingday +0.55 x temp - 0.16 x windspeed + 0.09 x summer + 0.13 x winter + 0.10 x Sept + 0.07 x Sat - 0.08 x Cloudy_mist - 0.29 x Light_Rain**
- Conclusion 2 - The coefficient yr,workingday,temp,summer,winter,Sept,Sat are positive.
- Conclusion 3 - The coefficient windspeed,Cludy_mist, Light_Rain are negative.
- Conclusion 4 - Constant is 0.08 i.e if all variables are kept 0, the demand will be 0.08.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 
- Jupyter Notebook

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->




<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->