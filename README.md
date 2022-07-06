# House price prediction assignment 


## Table of Contents
* [Problem Statement](#problem-statement)
* [Steps followed](#steps-followed)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->
# Problem Statement

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

## The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.

### Business Goal:

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


- Dataset being used
  - I have used train.csv file for this analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
# Steps followed
Steps 
  - Step 1: Read understand and visualize the data
  - Step 2: EDA
  - Step 3: Prepare the data for modelling
  - Step 4: Building the model using RFE, Lasso and Ridge
  - Step 5: Residual analysis for each
  - Step 6: Predictions and evaluation on the test set
  - Step 7: Summary

## Conclusions
- Conclusion 1 - Following fields are impacting the house price
  - LotArea
  - OverallQual
  - OverallCond
  - BsmtFinSF1
  - TotalBsmtSF
  - 1stFlrSF
  - 2ndFlrSF
  - GrLivArea
  - BedroomAbvGr
  - TotRmsAbvGrd
  

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- sklearn
- linear_model

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was done part of my Executive PG Programme in Machine Learning & AI - February 2022 batch
- I would like to thank our Subject Matter Expert: 
  - S Anand CEO, Gramener for sharing his wealth of knowledge for EDA
  - Dinesh J Babu Associate Professor, IIIT-B
  - Mirza Rahim Baig Lead Business Analyst at Flipkart:
- Also we thanks other faculty members and support team from UpGrad who were always available for us

## Contributors - feel free to contact me!
 [@https://github.com/murthib]       

