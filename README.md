# Data Science:Predicting-Potential-Customers
# Project Overview
This project involves identifying which leads are more likely to convert to paid customers based on attributes of leads and their interaction details.

# Course 
Classification and Hypothesis testing

**Skills and Tools covered**

* Decision Trees
* Random Forests
* Hyperparameter tuning

# Data Overview
1. Missing value treatment
2. Feature engineering
3. Outlier detection and treatment
4. Preparing data for modelling

# Code and resources used

**Jupyter notebook**

**Packages:** numpy, pandas, matplotlib, sklearn, seaborn, statsmodels

**Sources:** From MIT; Data Science and Machine Learning online course

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

**Plot of one categorical variable**

![Screenshot 2024-05-17 153850](https://github.com/knowl01/Predicting-Potential-Customers/assets/135021827/ebf7c6f0-3f6f-4229-afd9-56f04106c7bb)

**Statistics summary:**

<img width="533" alt="Statistics2" src="https://github.com/knowl01/Predicting-Potential-Customers/assets/135021827/c49d74a8-1b52-49fc-8d87-6ec03774e67e">

 **Correlation Matrix:**
 
 <img width="817" alt="Corr_matrix" src="https://github.com/knowl01/Predicting-Potential-Customers/assets/135021827/d2b9114c-965d-4071-ba81-9795aa6a567a">


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

**Precision Recall**

<img width="656" alt="Precision_Recall2" src="https://github.com/knowl01/Predicting-Potential-Customers/assets/135021827/00c4c3b7-4447-49a8-9e93-9913c2a92e65">

 **Important Features**
 
<img width="755" alt="Imp_Features2" src="https://github.com/knowl01/Predicting-Potential-Customers/assets/135021827/d3e399c6-43a4-43d5-9c48-4aa2e0abd5c3">

   
# Model Performance
The Tuned Random Forest Model performed well compared to all the other models.

**Confusion matrix on train set**

<img width="491" alt="Tuned_rf2" src="https://github.com/knowl01/Predicting-Potential-Customers/assets/135021827/f870ef09-e5a1-44af-bf15-c7eac7da8f56">






