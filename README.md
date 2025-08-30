# Thesis Title: 
Electricity Consumption Prediction during Ship Construction - A Machine Learning Approach

# Description: 
This repository contains the machine learning code developed for my undergraduate thesis.Here, a multivariate linear regression model to predict electricity consumption during ship construction was applied. It will help a shipbuilder to predict the electricity cost and optimize the manufacturing cost. 

# Contents

- **Machine_Learning_Code_for_Ship_Welding_Cost_Estimation.ipynb**  
  Core model training using Linear Regression on ship dimensions and type to predict filler metal and electricity consumption.

- **Data_Visualization_and_Model_Predictions.ipynb**  
  Visual exploration of the dataset, actual vs predicted results, and correlation analysis via scatter plots and heatmaps.

- **welding_cost_final.csv**  
  Dataset covering 21 ships with columns: `length`, `breadth`, `depth`, `ship_type`, `filler_metal`, and `electricity_consumption`.


# Overview
**Objective:** 
This study tries to develop a machine learning model for predicting electricity consumption during ship construction, enables to calculate approximate manufacturing costs for specific ship types at preliminary design phase according to owner's requirements and to establish comprehensive relationships between electricity consumption and different types of parameters

**Machine Learning Model:** 
Multivariate Linear Regression is used to predict welding filler metal requirements and electricity usage based on ship dimensions and type.

**Visualization:** 
Includes scatter plots (actual vs. predicted), identity line plots, and a correlation heatmap.

## ABOUT THE DATASET AND METHODOLOGY
The dataset for the machine learning model, consisting of variables such as length, breadth, depth, ship type, electrode (filler metal), and electricity consumption of 21 Different ships. It is a sinthetic dataset. The dataset was generated from the welding usage during a particular ship construction. Using the welding usage, filler metal and electricity consumption calculated. For the machine learning model, the data was standardized to place all variables on a similar scale. From this dataset, the most influential parameters: independent (input) variables affecting electricity consumption were identified. The total electricity consumption was treated as the dependent (output) variable.

The dataset was divided into training and testing sets, with 80% allocated to the training set and 20% to the testing set. The training set was used to train the model, while the testing set was employed to evaluate the model's accuracy. An appropriate machine learning algorithm was selected, and since this is a prediction problem, a regression model was chosen.

After selecting the appropriate model, it was trained using the training dataset and tested with the testing dataset. The accuracy of the model was evaluated using a confusion matrix or other relevant libraries. At this stage, the model was prepared to predict electricity consumption during ship construction. 

# Attribution
This project is part of my thesis work. For this and other research outputs, visit my portfolio:

[Research Portfolio](https://sites.google.com/view/smsheam/research?authuser=0)



