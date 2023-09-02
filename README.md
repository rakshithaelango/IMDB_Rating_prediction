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

STEP 4: Exploring, Data cleaning And Data preprocessing. 

   * Dropping null values.
   * Duplicates values identifying.
   * Changing data types.
   * statistical Analysing.
       
STEP 5: Exploratory data analysis (EDA)

* Splitting train / test
* Applying Machine Learning (Supervised ML)
* Evaluating Model 

# Data set link:
https://www.kaggle.com/datasets/karrrimba/movie-metadatacsv
