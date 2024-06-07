# Capstone_Property_Price

## Overview:
This project aims to predict property prices based on various features such as location, size, amenities, etc. It involves collecting and cleaning real estate data, performing exploratory data analysis (EDA), developing machine learning models, and evaluating their performance.

## Project Steps:
###1. Data Collection and Cleaning:
Collect real estate data from a specific location.
Clean the data by handling missing values, outliers, and inconsistencies.

### 2. Handling Ordinal and Nominal Columns:
Utilize the provided metadata sheet to identify which columns are ordinal or nominal.
Handle ordinal and nominal columns separately during preprocessing.

### 3. Preprocessing Techniques:
Implement scaling to standardize numerical features.
Apply PCA to reduce dimensionality if necessary.
Use fillna() to handle missing data by imputing appropriate values.

### 4. Exploratory Data Analysis (EDA):
Conduct EDA to identify key variables influencing property prices.
Explore correlations between features and the target variable.
Visualize distributions and relationships using plots and graphs.

### 5. Encoding Techniques:
Choose appropriate encoding techniques for ordinal and nominal variables based on model requirements.
Use methods like one-hot encoding for nominal variables and label encoding for ordinal variables.

### 6. Machine Learning Model Development:
Develop machine learning models to predict property prices.
Select relevant features and split the data into training and testing sets.
Experiment with various algorithms such as linear regression, random forest, etc.

### 7. Model Evaluation:
Evaluate the performance of the developed model using metrics like RMSE, MAE, etc.
Compare the performance with other machine learning algorithms.
Fine-tune hyperparameters to optimize model performance if necessary.

### Dependencies:
Python 3.x
Pandas
NumPy
Matplotlib
seaborn 
matplotlib.pyplot 
StandardScaler, OrdinalEncoder, OneHotEncoder
train_test_split
LinearRegression
DecisionTreeRegressor
RandomForestRegressor
mean_absolute_error, mean_squared_error
