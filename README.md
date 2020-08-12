# Used_Car_Price
Predict the car price in used vehicles listings from Craigslist.org

## Context
Craigslist is the world's largest collection of used vehicles for sale, yet it's very difficult to collect all of them in the same place. I built a scraper for a school project and expanded upon it later to create this dataset which includes every used vehicle entry within the United States on Craigslist.

## Content
This data is scraped every few months, it contains most all relevant information that Craigslist provides on car sales including columns like price, condition, manufacturer, latitude/longitude, and 18 other categories. For ML projects, consider feature engineering on location columns such as long/lat. For previous listings, check older versions of the dataset.

This is a Kaggle dataset which can be found in this link: https://www.kaggle.com/austinreese/craigslist-carstrucks-data

<p align="center">
  <img src="https://github.com/panambY/Used_Car_Price/blob/master/image/used_car.jpg">
</p>

I followed in this project the steps of the project management method called CRISP-DM. This method has undergone modifications aimed at the reality of a Data Science project and with that it was called CRISP-DS.

Your main principle is doing the project following multiples cycles as the necessity.

### 1 - Business Question

### 2 - Understanding the Business

### 3 - Data Collection
**0.0 - IMPORTS** <br>
	0.1 - Helper Function <br>
	0.2 - Loading Data <br>
### 4 - Data Cleaning
**1.0 - DESCRIPTION OF DATA** <br>
	1.1 - Rename Columns <br>
	1.2 - Data Dimensions <br>
	1.3 - Data Types <br>
	1.4 - Check NA <br>
	1.5 - Fillout NA <br>
	1.6 - Change Types <br>
	1.7 - Descriptive Statistical <br>
		- 1.7.1 - Numerical Attributes <br>
		- 1.7.2 - Categorical Attributes <br>
**2.0 FEATURE ENGINEERING** <br>
	2.1 - Creation of Hyphoteses <br>
		- 2.1.1 - Demographic Hyphoteses <br>
		- 2.1.2 - Geographic Hyphoteses <br>
		- 2.1.3 - Sociocultural Hyphoteses <br>
	2.2 - Final list of Hypotheses <br>
	2.3 - Feature Engineering <br>
**3.0 - VARIABLE FILTERING** <br>
	3.1 - Line filtering <br>
	3.2 - Column Selection <br>
### 5 - Data Exploration
**4.0 - EXPLORATORY DATA ANALYSIS** <br>
	4.1 - Univariate Analysis <br>
		- 4.1.1 - Response Variable <br>
		- 4.1.2 - Numerical Variable <br>
		- 4.1.3 - Categorical Variable <br>
	4.2 - Bivariate Analysis <br>
		- 4.2.1 - Summary of Hyphoteses <br>
	4.3 - Multivariate Analysis <br>
		- 4.3.1 - Numerical Attributes <br>
		- 4.3.2 - Categorical Attributes <br>
### 6 - Data Modeling
**5.0 - DATA PREPARATION** <br>
	5.1 - Normalization <br>
	5.2 - Rescaling <br>
	5.3 - Transformation <br>
		- 5.3.1 - Encoding <br>
		- 5.3.2 - Response Variable Transformation <br>
		- 5.3.3 - Nature Transformation <br>
**6.0 - FEATURE SELECTION** <br>
	6.1 - Split dataframe into training and test dataset <br>
	6.2 - Boruta as Feature Selection <br>
		- 6.2.1 - Best Feature from Boruta  <br>
### 7 - Machine Learning Algorithms
**7.0 - MACHINE LEARNING MOMDELLING** <br>
	7.1 - Average Model <br>
	7.2 - Linear Regression Model <br>
		- 7.2.1 - Linear Regression Model - Cross Validation <br>
	7.3 - Linear Regression Regularized Model <br>
		- 7.3.1 - Linear Regression - Lasso - Cross Validation <br>
	7.4 - Random Forest Regressor <br>
		- 7.4.1 - Random Forest Regressor - Cross Validation <br>
	7.5 - XGBoost Regressor <br>
		- 7.5.1 - XGBoost Regressor - Cross Validation <br>
	7.6 - Compare Model's Performance <br>
		- 7.6.1 - Single Performance <br>
		- 7.6.2 - Real Performance - Cross Validation <br>
**8.0 - HYPERPARAMETER FINE TUNING** <br>
	8.1 - Random Search <br>
	8.2 - Final Model <br>
### 8 - Evaluation of Algorithms
**9.0 - TRANSLATION AND INTERPRETATION OF THE ERROR** <br>
	9.1 - Business Performance <br>
	9.2 - Total Performance <br>
	9.3 - Machine Learning Performance <br>
### 9 - Production Model
**10.0 - DEPLOY MODEL TO PRODUCTION** <br>
	10.1 - Energy Consumption Class <br>
	10.2 - API Handler <br>
	10.3 - Tester <br>
