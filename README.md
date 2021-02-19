# Brainome Table Compiler vs SkLearn on real datasets

Objectives:

Find 10 datasets

For each data set:

  Create three different models using Brainome (DT, RF, NN), without and with -rank flag
  
    Create 7 more models with sk learn
    
      Decision Tree
      MLP Classifier
      Random Forest
      Extra Trees Classifier
      SGD Linear Classifier
      Gaussian Naive Bayes
      Support Vector Machine  
    

Approach: 
First, I would do some exploratory data analysis and then build my baseline models with sci kit learn. 
After, I would use measurements and ranking from BTC to further improve my baseline models. 
Attribute ranking was the most useful for improving accuracy of the baseline models. 
Only after that would I create the model with the Brainome tool.


Datasets:
Spotify Music Preference
Based on song characteristics, classify if whether I like the song 
Source: self made

Credit Card Fraud Detection
Using features from a PCA, detect if a specific transaction is fraudulent
Highly unbalanced, 0.172% are frauds
Source: https://www.kaggle.com/mlg-ulb/creditcardfraud

Mushroom Classification
Based on physical attributes predict if a mushroom is edible
Source: https://www.kaggle.com/uciml/mushroom-classification

House Sales in King County
Predict house price based on size, and floor plan
Need to bin housing prices
Source: https://www.kaggle.com/harlfoxem/housesalesprediction

Red Wine Quality Classification
Based on chemical information about a wine, predict its quality score (1-10)
Source: https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009

Predicting Diabetes in Patients
Using health data, predict whether a patient is diabetes positive
Source: https://www.kaggle.com/uciml/pima-indians-diabetes-database 

Activity Levels Based on Features
Cla ssify a person’s activity level based on engineered features
Source: https://www.mldata.io/dataset-details/smartphone_activity/

Predicting Grades Based on Lifestyle
Using a person’s lifestyle data to predict their grades
Source: https://www.mldata.io/dataset-details/school_grades/
