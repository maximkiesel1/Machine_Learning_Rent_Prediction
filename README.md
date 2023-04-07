# Munich Renting Market Analysis and Machine Learning Prediction
![image](https://user-images.githubusercontent.com/119667336/215277641-f1677f04-63d8-490b-98cb-a192b029bb72.png)

This repository contains 3 files for analyzing the renting market in Munich, Germany. The goal of this project is to gain insight into the renting market in order to subsequently train a machine learning model that can predict rent prices based on certain features.

## File 1: Web Scraper
The first file is a web scraper that gathers renting data from a real estate website, specifically in munich, cleans and organizes the data, and stores it in a dataframe. This data includes information such as district, price, square meters, and number of rooms.

## File 2: Exploratory Data Analysis (EDA) and Data Wrangling
The third file conducts an exploratory data analysis (EDA) and Data Wrangling on the renting data, revealing key insights into the Munich renting market. The EDA found that:

- The majority of renting listings tend to be in affluent neighborhoods in Munich
- The more expensive the neighborhood, the more variation there is in renting prices
- Larger rent units are not typically found in the most expensive areas

The EDA is an important step in understanding the patterns and trends in the data and identifying areas for further investigation.

## File 3: Machine Learning Modeling
In our "Part_Three_Prediction" file, we investigated five models to make predictions for our data. These models were Linear Regression, Lasso, Ridge, Random Forest, and Gradient Boosting. After thorough testing and evaluation, the best model was found to be Gradient Boosting with a R2 score of 0.787. 

## Summary
The goal of this repository is to provide a comprehensive analysis of the Munich renting market. The web scraper gathers the data, the processed data file provides a cleaned version of the data ready for analysis, and the EDA sheds light on key insights and patterns in the market. Further analysis and modeling can be done using this data to predict housing prices and understand the factors that drive them.

## Knowledgment
The data was obtained from the website www.Immonet.de.
