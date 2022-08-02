#                                                                  HOUSE-PRICE-PREDICTION-PROJECT
                                        Develop and regression model for house price prediction
                                        
  **The goal of this repository was to provide an analysis for Kaggle's competition:  https://www.kaggle.com/c/house-prices-advanced-regression-techniques**

![kaggle-image](https://storage.googleapis.com/kaggle-competitions/kaggle/5407/media/housesbanner.png)


## Description

**EDA and Data tidying:**
                                      
                                        
                                        
                                        
Data Exploration
The dataset provided is captured in three csv files: train.csv, test.csv, and macro.csv. The columnar data of the csv files are described in data_dictionary.txt; please see this file for description of the individual features. The columns in train.csv and test.csv represent data about the properties themselves, along with timestamps; data such as square footage (size), number of rooms, and build year. Extrinsic properties, such as proximity to entertainment and cultural attractions, is also included in these csv files. The column price_doc denotes the sale prices of the properties, and is the target variable for the regression analysis. Data within macro.csv, as the name would indicate, presents broad macroeconomic indicators along with timestamps. These data include gross domestic product, currency exchange rates, and mortgage rates. Now, load the data using the pandas package
## Main Steps

- Dataset exploration
- Selection of features (for numerical and categorical variables)
- Data cleaning
- Feature engineering
- Trainning + testing the model
- Improving Predictions 
- Final testing

## How to run the code

1. Either clone the repository or download the files
2. Install requirements (requirements.txt)
3. Download the dataset from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
4. Open the notebook: House-prices-Advanced-Regression/main.ipynb
5. Run the notebook




#Data Processing

Deleting the huge outliners from data.
  
Log - transformation of target variable

Feature Engineering for slection of better features for our data.

Data Correlation matrix for viwing the relationship of variables.

There are many missing values in data so we will fill those values as given in the competition rules.

Label Encoding some categorical variables

Using Box Cox Transformation of (highly) skewed features

### Modelling

Importing all required libraries

Cross validation strategy definition

Base models used 

1.LASSO Regression

2.Elastic Net Regression

3.Kernel Ridge Regression

4.Gradient Boosting Regression

5.XGBoost


