Project Name: Bike Sharing System - Multi Linear Regression

Problem Statement:
    A bike-sharing system is a service where bikes are available for shared use to individuals on a short term basis for a price or free. Bike-sharing system allows people to borrow a bike from a computer controlled "dock" where user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the Bike-sharing system.
    A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain the business in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end.
    BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profit.

    BoomBikes wants to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
    -The variables which are significant in predicting the demand for shared bikes.
    -How well those variables describe the bike demands

Scope of Analysis:
    It is required to model the demand for shared bikes with the available independent variables. It will be used by the BoomBikes management to understand how exactly the demands vary with different features. The model will help BoomBikse to manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market

Approach:
    Reading, Understanding and visualizing the data
    Preparing the data for modelling (train-test split, rescaling, etc.)
    Building the model
    Residual analysis
    Prediction and evaluation on the test data

Source of Data:
    Data are provided in the file “day.csv”. The "day.csv" file contains private data coming from BoomBikes. No additional details are expected to be analyzed as part of the study..

Final Linear Regression model for project is given below
    Target variable (cnt) = 0.1994 + 0.2336 x yr - 0.0975 x holiday + 0.4910 x temp - 0.1479 x windspeed - 0.0672 x spring + 0.0465 x summer + 0.0817 x winter - 0.0521 x Jul + 0.0768 x Sep - 0.2842 x Lightsnow+raing - 0.0802 x Mist+cloud

Recommendation:
    Bike sharing demand is mainly dependent on variables yr, holiday, temp, windspeed, spring, summer, winter, Jul, Sep, Lightsnow+rain and Mist+cloud.
    Independent variables yr, temp, summer, winter and sep have positive impact on Bike sharing count as per the model built. While deciding the sales strategy, these variables should be taken into account to increase the sales.

Acknowledgemnts
    The project was assigned and guided by Upgrad

Contact
    Created by Suresh

