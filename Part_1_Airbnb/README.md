# Part 1: Airbnb Price Prediction

## Introduction

In the field of accommodation, traditional hotel accommodation still occupies a huge market share, whereas Airbnb is growing as one of the largest accommodation providers. The supply of the accommodation market is highly dynamic and influenced by various factors such as economic conditions, government policies, and external factors like natural disasters or pandemics. Additionally, the features of an apartment or a room such as an area, construction quality, location, and amenities can also significantly impact its price. As a result, it can be challenging for real estate players or property owners to estimate the accurate price of a hotel room on the Airbnb platform.

This project aims to develop a regression model using ensemble learning that can accurately predict the prices of accommodations on the Airbnb platform in New York City.


## Files 
**Preliminary models and grid searches folder** contains both EDA and all the grid searches of ensemble models.\
**Airbnb_EDA.ipynb** contains what we found and created for the section EDA\
**Airbnb_models.ipynb** contains all the details of modelling process\
**Airbnb_prepocessing.ipynb** contains the needed steps to get data ready for modelling\
**airbnb_preprocessed.csv** is the saved csv after preprocessing.


## Project Report Overview
The project report is structured as follows:

     1. Problem statement and motivation
     2. Preprocessing
              2.1 Exploratory Data Analysis
              2.2 Feature Selection
              2.3 Feature Engineering
     3. Methodology
              3.1 Decision Tree
              3.2 Bagging
              3.3 Random Forest & Extremely Random Forest
              3.4 Boosting
              3.5 Stacking
     4. Model Evaluation
     5. Results and comparison
     6. Conclusions
     
      
## Usage

To run the code, follow these steps:

1. Clone the repository.
2. Install the required packages in the pynotebook

import pandas as pd\
import numpy as np\
import matplotlib.pyplot as plt\
import seaborn as sns\
from sklearn.linear_model import LogisticRegression\
from sklearn.linear_model import LinearRegression\
from sklearn.model_selection import cross_val_score, train_test_split, GridSearchCV\
from sklearn.metrics import classification_report \
from sklearn.metrics import confusion_matrix\
from sklearn.tree import DecisionTreeRegressor\
from sklearn.metrics import r2_score\
from sklearn.preprocessing import MaxAbsScaler\
from sklearn.metrics import mean_squared_error\
from sklearn.ensemble import ExtraTreesClassifier\
from sklearn.preprocessing import StandardScaler\
from sklearn.preprocessing import LabelEncoder

3. Run the all the Jupyter notebooks to train the model and make predictions.

## Datasets used

New York City Airbnb Open Data

Airbnb listings and metrics in NYC, NY, USA (2019)
https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data


## Conclusion

This project demonstrates the effectiveness of ensemble learning in predicting the prices of accommodations on the Airbnb platform in New York City. The model can be used by real estate players or property owners to estimate the accurate price of a hotel room on the Airbnb platform.
