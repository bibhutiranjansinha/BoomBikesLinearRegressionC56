# Bike Sharing Assignment
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contacts](#contacts)


## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Above information will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Conclusions
- Train dataset R^2 : 0.834
- Test dataset R^2 : 0.804
- Train dataset Adjusted R^2 : 0.830
- Test dataset Adjusted R^2 : 0.794

Significant variables to predict the demand for shared bikes

- year
- holiday
- temperature
- windspeed
- Season(Winter, Spring)
- months(January, July, September)
- weathersit( Light Snow, Mist + Cloudy)

Analysing the above model, the comapany should focus on the following features:
- Company should focus on expanding business during Spring.
- Company should focus on expanding business during September.
- Based on previous data it is expected to have a boom in number of users once situation comes back to normal, compared to 2019.
- There would be less bookings during Light Snow or Rain, they could probably use this time to serive the bikes without having business impact.


## Technologies Used
Data loading and manipulation libraries
- pandas : Version - 2.0.3

Data visualization libraries
- seaborn : Version - 0.12.2
- matplotlib.pyplot : Version - 3.7.2
- plotly.express : Version - 5.9.0

Stats and LR libraries
- sklearn : Version - 1.3.0
- statsmodels: Version - 0.14.0

Utility
- IPython.display
 - Markdown
 - display
- warnings


## Acknowledgements
This assignment was while doing MS in Artificial Intelligence and Machine Learning from IIIT Bangalore


## Contact
Created by [Bibhuti Ranjan Sinha](https://www.linkedin.com/in/bibhutiranjansinha/)  - feel free to contact me!