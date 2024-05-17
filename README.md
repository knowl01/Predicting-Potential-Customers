# Data Science:Predicting-Potential-Customers
# Project Overview
This project involves identifying which leads are more likely to convert to paid customers based on attributes of leads and their interaction details.

# Data Overview
1. Missing value treatment
2. Feature engineering
3. Outlier detection and treatment
4. Preparing data for modelling

# Code and resources used
**Jupyter notebook**
**Packages:** numpy, pandas, matplotlib, sklearn, seaborn, statsmodels
**Sources:** FrOM MIT, Data Science and Machine Learning online course

# Web Scraping
Features included;
* ID
* Age
* Current occupation
* First interaction
* Profile completed
* Website visits
* Time spent on website
* Page views per visit
* Last activity
* Print media type1
* Print media type2
* Digital media
* Edcational channels
* Referral
* Status

# EDA 
I looked at the distributions of the data and the value counts for the various categorical variables. Below are some of the highlights;


# Model Building
First I transformed the categorical variables into dummy variables. I also split the data into train set and test set with a test size of 30%.

I tried different 4 models and evaluated them using Mean Absolute Error, R-squared, Adjusted R-squared, Mean Absolute Percentage Error. I chose all these so that we can compare the differences. 
These are the 3 different models I chose;
1. Decision Tree Model
2. Tuned Decision Tree
3. Random Forest Model
4. Tuned Random Foest Model

# Feature Importance
   These are the important features form the tuned random forest model. 

   
# Model Performance
The Tuned Random Forest Model performed well compared to all the other models.



