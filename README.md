# CIND820_InitialResults

This repository contains the following technical documents:

1. Imputation results using MICE
2. Data cleaning 
3. Data clustering
4. Decision Tree, Logistic Regression, K-Nearest Neighbours 

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
  - It seems like we may not be able to predict which one is more common exactly rather we can predict which natural disasters will have more damaging effects
  - This is because our previous data clustering and analysis kind of answers this question since we can see trends of natural disasters 
  - It would be better to be able to predict the damages (deaths or total damages) 

Keeping in mind that we need to choose a dependent variable, it was decided that since we have shifted to predicting damages then total deaths would be the main focus and our dependent variable. This is because previous research articles and journals conducted by other data scientists already cover economic effects such as building damages and other economic factors thus it would be more interesting to focus on how humans will be effected physically and or mentally rather than economically. 

Furthermore, this will be a classification problem. We will be using decision trees, KNN, and logisitic regression to understand and classify the most important factors to use when predicting deaths caused by natural disasters. 
