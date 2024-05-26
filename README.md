# Bike Sharing Assignment

> This assignment involves building a multiple linear regression model to predict the demand for shared bikes

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- This project involves building a multiple linear regression model to predict the demand for shared bikes using a provided dataset. The goal is to analyze various factors influencing bike demand and develop a predictive model that can help a bike-sharing service provider, BoomBikes, optimize their business strategy post-pandemic.
- Bike-sharing systems are services where bikes are made available for short-term use for a fee or free. Users can borrow a bike from a dock, usually controlled by a computer system, and return it to another dock within the same network. BoomBikes, a US-based bike-sharing provider, has seen a significant decline in revenue due to the COVID-19 pandemic. As the situation improves, BoomBikes aims to prepare for an anticipated increase in bike demand by understanding the factors that influence it.
- BoomBikes is facing a challenge in sustaining their business due to decreased revenues during the pandemic. To recover and thrive once the lockdown ends, they need to understand the demand dynamics for shared bikes. Specifically, they want to identify which factors significantly impact bike demand and how these factors can be leveraged to forecast future demand. This understanding will enable BoomBikes to develop effective business strategies, meet customer needs, and stand out from competitors.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- We have selected 14 features that affect the bike demand
- The corresponding Linear regression equation is
  (0.52) _ temp + (0.26) * yr + (0.13) * sep + (0.12) * winter + (0.11) * summer + (0.06) * oct + (0.05) * workingday + (0.05) * aug + (0.04) * mon + (-0.04) * jan + (-0.04) * wed + (-0.09) * misty + (-0.15) * windspeed + (-0.27) * lightrain + 0.1
- The temperature of the day affect the most
- If there's light rain or if the windspeed is high, it reduces the demand.

## Technologies Used

- numpy
- pandas
- matplotlib
- sklearn
- statsmodels

## Contact

Created by [@anmol1vw13] - feel free to contact me!
