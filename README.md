BIKE SHARING SYSTEM

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands.
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.


## Table of Contents
 General Info
 Conclusions
 Technologies Used
 Acknowledgements

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Objectives- 
Create a linear model that describes various features on price.
The model should be interpretable so that the management can understand it.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

EDA-
Effect of Categorical variables-
weekday- cnt is highest on Tuesday and lowest on Sunday. 

season- During fall cnt is highest followed by summer, winter and spring. Spring has lowest cnt.

yr- There is sigficant rise of cnt in 2019 compared to 2018

mnth- cnt has positive impact on the month Sep and Oct.

day- cnt is highest on Thursday and lowest on Monday and Tuesday. Though there is no significant difference between highest and lowest value.

holiday- cnt is less in holidays.

workingday - cnt is more in workingday.

weathersit - cnt is highest on Clear, Few clouds, Partly cloudy, Partly cloudy weather followed by Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist.cnt 
is lowest during Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds. We donot have any records for cnt during 
Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog in our dataset.


Effect of numerucal variables-

Temp has a linear relationship with cnt

Model-

We have built a model having R-sqare 0.800(that is 80.0%) for train data. Using that got R-qsuare for test model as 0.792(that is 79.2%).

The model gives us the below insight-

We have introdeced some new features from existing features in the dataset.

The below features significantly contributes towards explaining the demand of the shared bikes 

- yr- There is sigficant rise of cnt in 2019 compared to 2018. yr-2019 has a significant imapct on the demand of shared bikes.

- holiday- holiday has negative imapct on the demand of shared bikes.

- temp- temp has significant positive imapct on the demand of shared bikes.

- windspeed - windspeed has negative imapct on the demand of shared bikes.

- season_summer and season_winter- season_summer and season_winter have positive imapct on the demand of shared bikes.

- weathersit_Ligh_Snow - weathersit_Ligh_Snow has negative impact one shared bike.

- mnth- Sep and Oct have positive imapct on shared bike price.

- day - Monday,Tuesday,Wednesday have negative impact on the demand of shared bikes.

## Technologies Used
  numpy 1.26.4
  pandas 2.2.3
  matplotlib 3.9.2
  seaborn 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.


## Contact
Created by  rituparna.biswas2010@gmail.com - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->