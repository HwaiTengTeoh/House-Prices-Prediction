# House Prices Prediction Using Advanced Regression Techniques
*Note: This repository shares the group project in fulfillment of the Data Analytics class for Data Science coursework.*

## Work Summary
The strategy to decide on the value of a property (i.e., a house) should not be based on pure intuition. Instead, there are multiple aspects to look into, such as the property's built location, the location accessibility, the number of rooms and bathrooms, the construction year, and the availability of other house equipment. These aspects are usually considered the main factors that add or drop a house's value. Hence, this project aims to predict the house price accurately based on the historical data by applying a regression algorithm along with some pre-processing techniques

## Objectives
The primary goal of this work is to predict house prices. To attain this goal, a few objectives are outlined:
- To visualize the past trends in housing market prices
- To explore the relationship between features that cause a house to be the most expensive in the market
- To identify the influential features for building the house price prediction model
- To develop and evaluate models that predict a house’s selling price using advanced regression techniques

## Data Sources
- The historical house pricing data used for this work was prepared by Dean De Cock in 2011, which was made publicly available in conjunction with the Kaggle’s GettingStarted Prediction Competition to encourage Data Scientist’s contribution in employing feature engineering and advanced regression techniques that help generate input for house pricing prediction. 
- For practice purposes, we adopted the **<ins>train.csv</ins>** data set, which contains details of 1460 residential homes sold from 2006 to 2010 in Ames, Iowa, United States, with prices ranging between $34,900 and $755,000. 
- In this work, we omitted using the **<ins>test.csv</ins>** data set as the actual house prices were not explicitly available for performance evaluation. The train set was renamed **<ins>Ames House Prices.csv</ins>**, consisting of 1460 observations and 81 variables (38 numerical and 43 categorical). 
- The target variable is **<ins>SalePrice</ins>** which displays the selling price of the house. 
- The details of competition can be accessed [here](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview).
- Further details on the metadata of the variables can be found [here](https://github.com/HwaiTengTeoh/House-Prices-Prediction/blob/main/data/data_description.txt).

## WorkFlow
Refer the [code](https://github.com/HwaiTengTeoh/House-Prices-Prediction/blob/main/code/Predicting%20House%20Prices%20Using%20Advanced%20Regression%20Techniques.ipynb) in Jupyter Notebook for the output of the following:
- Data Processing and Cleaning
- Exploratory Data Analysis (EDA) and Visualization
- Model Development: Linear Regression, Polynomial Regression, Boosting: Extreme Gradient Boosting (XGBoost), Bagging: Random Forest
- Model Evaluation
