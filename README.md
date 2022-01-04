# Interactive Apps R:

## [Security Characteristic Line Web App](https://alex-hl.shinyapps.io/scl_app/)

App: [https://alex-hl.shinyapps.io/scl_app/](https://alex-hl.shinyapps.io/scl_app/)  
Code: [here](https://github.com/alex-hl/securitymarketline_webapp)

The web app is a calculator that allows the user to find out which publicly traded security has generated positive alpha in the past 5 years for any inputted ticker. The calculator also provides the security's beta, and its security characteristic line. The data used is updated in real time every time the user presses compute. Everything is hosted using shinyapp.io. Some of the tools used to code the app include:
* The shiny apps package in R
* The tidyquant package which provides real time updated stock and economic data
* The plotly package to make a user interactive plot of the security characteristic line

## [LSTM Stock Price Prediction App](https://github.com/alex-hl/lstm_stock_prediction_app)

Built a Long Short-Term Memory model integrated in an app. It allows the app user to predict the closing prices of any publicly traded security. Some of the tools used to code the model and the app include:
* The numpy, pandas, and sklearn packages to manipulate data in python
* The shiny, tidyquant, and plotly packages in R
* Tensorflow is used to run the LSTM model

# Data Analysis in R:

## [Analyzing Volatility of foreign exchanges (EUR/CAD and USD/CAD)](https://github.com/alex-hl/analyzing_volatility_of_foreign_exchanges)

The goal of this analysis is to explore degrees of uncertainty for Canadian foreign exchange rates using
bootstrap sampling Distribution of Variances. The method was performed for the EUR/CAD and USD/CAD exchange rates. The tidyverse library was used to perform the EDA and showcase results. 

## [Regression Analysis of Apartment Building Evaluation in Toronto](https://github.com/alex-hl/regression_analysis_of_appartment_building_evaluation_in_toronto)

The goal of this analysis is to use multiple linear regression models in order to predict the evaluation score of a
building. This is achieved by examining the number of units in a building, the age of the building, and the property type of the building. Multiple models were built to see which variables best explain the evalution score. This analysis is conducted using the Apartment Building Evaluation data set provided by the Toronto open data portal. 

## [Predicting the Canadian Popular Vote](https://github.com/alex-hl/predicting_the_canadian_popular_vote)

The goal of this analysis is to predict the Canadian federal election popular vote using logistic regression models and post-stratification.
* Statistical methods were used to find which logistic regression model would best predict popular vote shares. 
* Post-stratification was then used to determine which party would win the popular vote. 

# Python Projects:

## [An Experiment to Compare Algorithms for Parcel Delivery](https://github.com/alex-hl/comparing_algorithms_for_parcel_delivery)

In this project I have made the use a of a random algorithm and a greedy algorithm to schedule a truck route for parcels delivery. The goal was to analyze which algorithm was most efficient in mapping the truck's route. Some highlights of the steps taken are:
* Using hash tables in order to create a distance map
* Modeling a domain to implement necessary classes
* Implementing the algorithms

## [Automated Puzzle Solving](https://github.com/alex-hl/automated_puzzle_solving)

In this project I have implemented breadth-first search and depth-first search algorithms to solve logic puzzles. The algorithms were able to solve sodkus, word ladders, and expression tree puzzles. Some highlights of the steps taken are:
* Implement clases for the bfs and dfs solver
* Implement classes for each puzzles which specifies conditions on how to be solved
