# Capstone Project: Network Load Forecasting Using Machine Learning
Author: Harry Yau

Presented the results on Demo Day, Sept 4, 2019.

## Summary
The objective of this project is to apply Machine Learning techniques, such as gradient boosting and neural networks, to forecast the number of bike trips on a given day in Vancouver. In addition, this project also investigates the feasibility of applying deep learning techniques to simulate bike movements with a network of bike stations. 

## Comment
This repository is a collection of Jupyter Notebooks that was used for the capstone project for the Data Science Diploma program at BrainStation.

## Data Source
- Bike data source: https://www.mobibikes.ca/en/system-data 
  - The data was retrieved on July 29, 2019. Only data up to March 2019 was available on retrieval date.
- Weather data source: https://envistaweb.env.gov.bc.ca/DynamicTable2.aspx?G_ID=331
  - The data from 'Vancouver International Airport #2' was used for the capstone project.

## Softwares/Tools used
Python, Scikit-Learn, Keras

## Files
1.  Loading Data to Pickle File - <a href="https://github.com/vrif/capstone-mobi-bike/blob/master/00%20Load%20Data%20To%20Pickle.ipynb">00 Load Data To Pickle.ipynb</a>
2.  Cleaning the Data - <a href="https://github.com/vrif/capstone-mobi-bike/blob/master/01%20Cleaning%20the%20Data.ipynb">01 Cleaning the Data.ipynb</a>
3.  Daily Count Regression - <a href="https://github.com/vrif/capstone-mobi-bike/blob/master/02%20Daily%20Count%20Regression.ipynb">02 Daily Count Regression.ipynb</a>
    - Part 1: Regression scheme that investigated different regression techniques.
      - eg. Linear Regression, Random Forest, XgBoost, CatBoost, Neural Network
4.  Exploratory Graphs - <a href="https://github.com/vrif/capstone-mobi-bike/blob/master/03%20Exploratory%20Graphs.ipynb">03 Exploratory Graphs.ipynb</a>
5.  Region Classification - <a href="https://github.com/vrif/capstone-mobi-bike/blob/master/04%20Region%20Classification.ipynb">04 Region Classification.ipynb</a>
    - Part 2: Classification scheme that investigated different classification techniques.
      - eg. Logistic Regression, Support Vector Machines, LightGBM, CatBoost, Neural Network
