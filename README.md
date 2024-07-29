Python Data Cleaning and Machine Learning modelling Repo:  

This repository provides a guide for data cleaning and machine learning modelling of different datasets using python.  

**Overview of data cleaning and modelling for APS Failure at Scania Trucks**  
1- APS Failure and Operational Data for Scania Trucks has been downloaded from this page:  
https://archive.ics.uci.edu/dataset/421/aps+failure+at+scania+trucks  
2- data cleaning has been performed with different Imputation methods (SimpleImputer, KNNImputer) as well as treating imbalanced data with SMOTETomek method  
3- APS Failure at Scania Trucks has been modelled with different ML boosting techniques (XGBClassifier,CatBoostClassifier,AdaBoostClassifier)  


**Overview of data cleaning and modelling for wind-power project** 
1-Downlaod wind power dataset form kaggle:  
 https://www.kaggle.com/datasets/theforcecoder/wind-power-forecasting      
2-drop_duplicate  
3-select important features (using corrolation function)   
4-handel missing values (using interpolate function)   
5-normalize data wtih MinMaxScaler() function  
6-data modelling with regression modellings  

**Overview of data modelling using sklearn.datasets and Machine learning methods** 
1-LinearRegression-SupportVectorMachine.ipynb: describes Linear Regression/Logistic Regression Modelling and Support Vector Machine methods  
2-Clustering-knn.ipynb: describes Clustering (KMeans, AgglomerativeClustering, DBSCAN) and k-nearest neighbors votting Machine Learning algorithms  
DecisionTree-NaiveBayes.ipynb: describes Decision Tree and Gaussian Naive Bayes  
FeatureSelection-Outlier.ipynb: describes Feature Selection/Extraction and Outlier Detection  