# IMDB_Rating_prediction:

In this DataSet you can able to see prediction of IMDB rating.

# Problem Statement:
   Every year, thousands of movies are produced in the film industry. It is a multi-billion dollar industry where a tremendous amount of investment and funding is involved with each project yet so few of them achieve the commercial success. These datasets are accessible through major platforms such as Internet Movie Database (IMDB), Rotten Tomatoes, and Metacritic and contain details about the movie, ranging from the budget of a movie to the number of likes of the director. The analysis of such datasets would prove which factors are more important than others and how these factors influence the ratings of the movies. The findings of this study may be useful to the stakeholders whose decisions can greatly influence how their movie will turn out.
  
# Porject in Detailed:

* STEP 1: Understanding Data.
  
* STEP 2: Importing necessary libraries.

import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sns

%matplotlib inline

from sklearn.model_selection import train_test_split

from sklearn.linear_model import LinearRegression

from sklearn.ensemble import RandomForestRegressor

from sklearn.tree import DecisionTreeRegressor

* STEP 3: Loading Dataset.

Loading dataset by using pd.read_csv file 

* STEP 4: Exploring, Data cleaning And Data preprocessing. 

   * Dropping null values.
   * Duplicates values identifying.
   * Changing data types.
   * statistical Analysing.
       
* STEP 5: Exploratory data analysis (EDA)
  
   * IMBD SCORES:
      
![1693650612186](https://github.com/rakshithaelango/IMDB_Rating_prediction/assets/116090323/048cd174-ce77-44d1-b13a-38eb04e5d5bb)

   * IMBD SCORES VS DIRECTOR FACEBOOKS LIKES:
    
![1693650612192](https://github.com/rakshithaelango/IMDB_Rating_prediction/assets/116090323/36fa627d-8ec2-4d59-bf44-457b0035ae39)

   * IMBD SCORES VS GROSS REVENUE:
       
![1693650612198](https://github.com/rakshithaelango/IMDB_Rating_prediction/assets/116090323/c0cb82a9-78e5-4689-acf2-456e028e2c5f) 

   * AVERAGE IMBD RATING BY YEAR:

![1693650612174](https://github.com/rakshithaelango/IMDB_Rating_prediction/assets/116090323/2c2152cb-9dc1-4a27-8226-789e376ff79d)

* STEP 6: Correlation using heat map And Feature selection.

![1693650612181](https://github.com/rakshithaelango/IMDB_Rating_prediction/assets/116090323/d4ed2496-96e2-42b9-889f-02191bb88005)

* STEP 7: Splitting the data into train / test And Building Machine learning Model.

        *  Linear Regression             :0.22920676184692867
        *  Random Forest Regression      :0.5630884461372567
        *  Decision Tree Regression      :0.36204154088068385
  
* STEP 8: Final Conclusion.
  
       * Random Forest Model perform good in IMDB Rating Prediction.
  
# Data set link:

https://www.kaggle.com/datasets/karrrimba/movie-metadatacsv
