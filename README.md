# Project Name
> ### Problem Statement:
##### A bike-sharing provider EBikes has recently suffered considerable dips in their revenues
#### They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. 
#### Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market
#### The company wants to know: Which variables are significant in predicting the demand for shared bikes
#### How well those variables describe the bike demands
#### You are required to model the demand for shared bikes with the available independent variables
#### It will be used by the management to understand how exactly the demands vary with different features
#### They can accordingly manipulate the business strategy to meet the demand levels and meet the customers expectations 
#### Further, the model will be a good way for management to understand the demand dynamics of a new market


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- client want to understand the factors affecting the demand for these shared bikes in the American market.
- A bike-sharing provider EBikes has recently suffered considerable dips in their revenues analyze the data using Linear regression
- client want to understand how exactly the demands vary with different features
- csv data provided in for boom bike co.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Positive coefficients like temp,yr indicate that an increase in these values will lead to an increase in the value of cnt. 
- We can infer that year by year popularity of bike booking is getting increased similary for if temperature is increased then bike booking are getting increased. 
- If weather is Light Snow & Rain it is negatively effected ````"0.488987 * temp + 0.234799 * yr -0.253042 * weathersit_Light Snow & Rain"````
- The demand bike cnt increased in the year 2019 when compared with year 2018
- bike demand cnt is high when weather is clear and Few clouds.
- Bike demand cnt is less in holidays in comparison to not being holiday
- demand cnt of bike is almost similar throughout the weekdays

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupiter
- python
- sklearn 
- sweetsv

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad
- This project was based on [tutorial](https://learn.upgrad.com/).


## Contact
Created by [Rakesh459] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->