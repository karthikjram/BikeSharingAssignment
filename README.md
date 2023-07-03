# Bike Sharing Assignment
> Build a multiple linear regression model for the prediction of demand for shared bikes.
> (using supplied data.csv of US bike-sharing provider BoomBikes)


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- What is the background of your project?
    
    - Bike sharing business

        A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
        Bike share systems allow people to borrow a bike from a "dock". (computer-controlled)
        Its computer-controlled (user enters the payment information, and the system unlocks it)
        This bike can then be returned to another dock belonging to the same system.

    - Boom Bikes company - A Bike sharing provider

        US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.
        Need business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
        BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.


- What is the business probem that your project is trying to solve?

    Boom Bikes want to understand the factors affecting the demand for these shared bikes in the American market:

    - Which variables are significant in predicting the demand for shared bikes?
    - How well those variables describe the bike demands?

- What is machine learning model requirement & importance?

    - Model the demand for shared bikes with the available independent variables.
    Management could understand how exactly the demands vary with different features.

    - Boom Bikes could manipulate the business strategy to meet the demand levels and meet the customer's expectations. (demand dynamics of a new market)


- What is the dataset that is being used?

    - Bike Sharing dataset (data.csv) and Data dictionary was provided to student.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1) Which variables are significant in predicting the demand for shared bikes?
   - The demand of shared bikes could be predicted by year 2019, temperature, windspeed, season (spring, winter), months (july, september), Day of Week (sunday) and weather situation(lightrainsnow, misty).

2) How well those variables describe the bike demands?
    - The predictor variable selection process involved usage of Recursive Feature Elimination and Manual Feature selection based on multicollinearity and statistical significance of model.
    - Model evaluation has been performed with selected predictor variables and following Linear regression assumptions (Error Normal distribution & homoscedasticity). 
    - The Adjusted R-squared value is 0.829, which may imply the model is a good fit.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - Version 1.23.5
- pandas - Version 1.5.3
- seaborn - Version 0.12.2
- matplotlib - Version 3.7.0
- sklearn - Version 1.2.1
- statsmodels - Version 0.13.5

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Liverpool John Moores University & IIIT Bangalore
AI/ML MSc. Degree assignment on Lending Club Case study


## Contact
Multiple Linear Regression Bike sharing Assignment <br>
by Karthik Jayaraman [@karthikjram] (https://www.github.com/karthikjram) - feel free to contact me!



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->