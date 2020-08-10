# Machine-Learning
This repository includes predictive modeling projects for online competitions (Kaggle & DrivenData) and assignments from the Master in Business Analytics & Big Data at IE HST.


## 1. The HR Dataset: Determining the probability of employees' attrition from the company
The goal here is to model the probability of attrition (employees leaving, either on their own or because they got fired) of each individual, as well as to understand which variables are the most important ones and need to be addressed right away.
The goal of this notebook is to highlight the importance of the feature engineering process.

To be able to build a predictive model on this data, I first start a thorough exploration of the data, I then create a baseline model that I improve on by applying Feature Engineering.

This is an individual work and the code can be found in the folder *1_HR_Dataset_Feature_Engineering* and the dataset is from Kaggle and can be found here: https://www.kaggle.com/giripujar/hr-analytics.

## 2. Pump it up Competition (DrivenData)
The goal here is to try helping the Tanzanian Ministry of Water to predict the operating condition of a waterpoint accross the country. We want to predict which pumps are going to continue working, which ones are going to need repairs and which ones are going to fail. We are thus dealing here with a multiclass classification problem for which we develop and Ensemble model.

The link to the competition is the following: https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/.

This work was done with the help of my colleagues Marang Mutloatse and Nisrine Ferahi. The model we developped ended up in the **top 15% out of more than 8900 people listed on the Leaderboard with a score of 0.8147.**

The script associated with this model is found in the file *2_Pump_it_up_competition*. It contains the following: Feature Engineering and Modeling, Feature Creation, Decision Tree with depth optimization, Bagging, Random Forest with hyperparameter tunning, Principal Components Analysis.


## 3. Model for predicting short-term Solar Energy Production
The goal of this project is to discover which machine learning methods would provide the best short term predictions of solar energy production. 
This project is based on a Kaggle Competition: https://www.kaggle.com/c/ams-2014-solar-energy-prediction-contest/overview.

We were given pre-processed data with PCA that we had to model. We tried various approaches before and the last model chosen is a SVM on the clustered stations' data with hyperparameter tunning. 

Our model's score would be ranked in the top 20% of the competition and achieved the 3rd highest score in class. This work was done with the help of my colleagues Nalisha Men and Paula San Roman. It can be found in the file *3_Predicting_solar_energy_production*.

![EDA Solar Energy Production](/3_Predicting_solar_energy_production/Solar.jpg)
