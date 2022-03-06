# CIND820_InitialResults

This repository contains the following technical documents:

1. Data preparation - Imputation results using MICE and cleaning the data table to remove any columns / attributes that are not relevant or would cause issues during the modelling 
3. Visualizations - Data clustering
4. Data modelling - Decision Tree, Logistic Regression, K-Nearest Neighbours 

These technical documents will provide a first look into how the data is peforming and if there are any issues requiring any other further steps as we move forward through the research project. 

At this point it was decided that the dataset to be used for the project is below:

https://www.kaggle.com/brsdincer/all-natural-disasters-19002021-eosdis

We will be utilizing the second .csv file that has data on natural disasters that have occurred between 1970 and 2021. 

The tentative stages of this project is to retrieve initial results to answer the following research questions with the respective technique that will be used listed underneath:

(a) How have different natural disasters (types) been trending over the years? 
  - Data clustering and analysis 
  - So far it seems like storms and floods are most common


(b) Which countries are experiencing the most natural disasters and which type?
  - Data clustering and analysis 
  - China and the US have the most reported cases 


(c) Can we predict which natural disaster will become more common or likely to occur? 
  - Decision tree, Logistic Regression, K-Nearest Neighbours will be tested out 
  - Decision tree - a classification tree will be used and the data will be split into a test and training set 

Keeping in mind that we need to choose a dependent variable, it was decided that we should be able to still predict natural disasters based on regions/countries. Those variables are currently character variables and will need to be converted into factor variables in order to complete our proposed classification models. 

Furthermore, this will be a classification problem. We will be using decision trees, KNN, and logisitic regression to understand and classify the most important factors to use when predicting natural disasters. The three methods will be compared based on their accuracies.
