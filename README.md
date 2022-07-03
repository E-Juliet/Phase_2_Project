# Phase_2_Project

## House Price Prediction in King County

## Problem Statement

As a junior data scientist in a real estate company in King county that helps homeowners to sell and buy houses,my first project was to determine

and analyse the factors affecting the house prices and further build a pricing algorithm for the houses based on the factors.The goal is to help

the agency advice homeowners on the factors that might increase the estimated value of their homes and by what amount.

## Components
__Data__

Data was provide in csv form


This project focused on one data set

__ kc_house_data.csv __

__Column Names and descriptions for Kings County Data Set__

* id - unique identified for a house

* dateDate - house was sold

* pricePrice - is prediction target

* bedroomsNumber - of Bedrooms/House

* bathroomsNumber - of bathrooms/bedrooms

* sqft_livingsquare - footage of the home

* sqft_lotsquare - footage of the lot

* floors - floors (levels) in house

* waterfront - House which has a view to a waterfront

* view - Has been viewed

* condition - How good the condition is ( Overall )

* grade - overall grade given to the housing unit, based on King County grading system

* sqft_above - square footage of house apart from basement

* sqft_basement - square footage of the basement

* yr_built - Built Year

* yr_renovated - Year when house was renovated

* zipcode - zip

* lat - Latitude coordinate

* long - Longitude coordinate

* sqft_living15 - The square footage of interior housing living space for the nearest 15 neighbors

* sqft_lot15 - The square footage of the land lots of the nearest 15 neighbors

__Jupyter Notebook__

The Jupyter Notebook is our key deliverable and contains details of our approach and methodology, data mining and cleaning, visualisations, conclusions and recommendations.

__Non Technical Presantation__

An overview of the project's objectives,analysis,conclusion and recomendations

## Technologies used

* Python

* Pandas

* Matplotlib

* Seaborn

* Visual Studio Code

## Objectives

* Which factors affect house prices?

* Which house atributes increase sale price?

* What is the average cost of a house?

## Key Findings

* Adding interaction increased the value of our R_squared in our model

* The best predictors for home prices in King County are sqft_living, grade and latitude.

* The average house cost in King county is 450000 USD

* Although latitude seemed to have high correlation with price,it cannot really define the location on its own.

* Houses sold in January were the cheapest and in April the houses were more expensive.Maybe  this could be attributed to fewer houses being sold in January as compared to April.

## Visualizations

Sqft_living and price

![Sqft_living with price](https://github.com/E-Juliet/Phase_2_Project/blob/main/sqft_living.png)

Grade and price

![Grade with price](https://github.com/E-Juliet/Phase_2_Project/blob/main/grade.png)

Month sold and price

![month_sold with price](https://github.com/E-Juliet/Phase_2_Project/blob/main/month1.png)

## Summary of models
![summary of models](https://github.com/E-Juliet/Phase_2_Project/blob/main/models.png)

## Recommendations
* The real estate agency should consider how different combinations of house features may increase sales than focusing on just individual variables

* They should consider houses that have a higher grading as this will increase their sales,grading higher than 7

* They should also consider houses with larger living spaces as they sell more and have a very linear relationship with price.As the sqft_living increases the price also increases
