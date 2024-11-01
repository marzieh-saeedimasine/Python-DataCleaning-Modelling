Python Data Cleaning and Machine Learning modelling Repo:  

This repository provides a guide for data cleaning and machine learning modelling of different datasets using python.  

## Overview of data cleaning and modelling for APS Failure at Scania Trucks project   
1- APS Failure and Operational Data for Scania Trucks has been downloaded from this page:  
https://archive.ics.uci.edu/dataset/421/aps+failure+at+scania+trucks  
2- data cleaning has been performed with different Imputation methods (SimpleImputer, KNNImputer) as well as treating imbalanced data with SMOTETomek method  
3- APS Failure at Scania Trucks has been modelled with different ML boosting techniques (XGBClassifier,CatBoostClassifier,AdaBoostClassifier)  

## Overview of the Energy Consumption forcasting project   
1- Downlaod hourly energy consumption data form kaggle:  
 https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption  
2-Feature Engeneering for time series data   
3-Data modelling with XGBRegressor regression modelling  
4-Data modelling with Dense Neural Network (DNN) and Autoencoder model  
5-Data modelling with LSTM model  
6-Data modelling with Conv1D, Conv1DTranspose  

## Overview of data cleaning and modelling for wind-power project    
1-Downlaod wind power dataset form kaggle:    
 https://www.kaggle.com/datasets/theforcecoder/wind-power-forecasting      
2-drop_duplicate    
3-select important features (using corrolation function)     
4-handel missing values (using interpolate function)   
5-normalize data wtih MinMaxScaler() function  
6-data modelling with regression modellings  


## Overview of Telco Customer Churn data cleaning and modelling project         
1-Downlaod Telco churn dataset form kaggle:     
https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data    
2-Exploratory Data Analysis (EDA), data cleaning and transformation was performed     
3-Imblanced dataset was handelled with under sampling or SMOTETomek techniques    
4-binary classification was implemented with ANN method to predict behavior of customers in customer retention program    


## Overview of AutoML Machine learning modelling for Classification and Regression Projects   
1- Here we use AutoML PyCaret to streamline the process of building and deploying machine learning models for both Classification and Regression Projects.    
2- It tests and selects the best-performing models automatically.    


## Overview of data modelling using sklearn.datasets and Machine learning methods      
1-LinearRegression-SupportVectorMachine.ipynb: describes Linear Regression/Logistic Regression Modelling and Support Vector Machine methods      
2-Clustering-knn.ipynb describes clustering methods (KMeans, Agglomerative Clustering, DBSCAN), methods to determine the optimal number of clusters (elbow method, silhouette score, gap statistics), and how to evaluate the quality of clustering (Dunn index and Rand index). In addition, it includes k-nearest neighbors voting machine learning algorithms.    
3-DecisionTree-NaiveBayes.ipynb: describes Decision Tree and Gaussian Naive Bayes        
4-FeatureSelection-Outlier.ipynb: describes Feature Selection has been explored with SelectKBest, ExtraTreeClassifier and LinearSVC modelling.   Feature extraction and visualization of high-dimensional data has been tested with PCA, t- SNE and Umap methods. Outlier Detection has been shown with quantile varience method. IsolationForest has also been used to detect anomalies or outliers           
5-NeuralNetwork-code.ipynb: implement Neural Network from scratch. It describes how to program model of neural network with one neuron and implement data for training and prediction  