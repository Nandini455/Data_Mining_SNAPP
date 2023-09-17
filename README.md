# Data_Mining_SNAPP
# Seoul Bike Trip

## Introduction
Bike sharing system is an innovative transportation strategy that provides individuals with bikes for their common use on a short-term basis for a price or for free. Over the last few decades, there has been a significant increase in the popularity of bike-sharing systems all over the world. This is because it is an environmentally sustainable, convenient and economical way of improving urban mobility. In addition to this, this system also helps to promote healthier habits among its users and reduce fuel consumption.

### The goals of this project are:
Understand the trends in the data and identify key factors affecting the demand for rental bikes.
Build an appropriate regression model to forecast the number of rental bikes required.

### Problem Statement:
In the future, maintaining a steady supply of rental bikes for the city may prove to be a difficult undertaking due to the expanding demand and user base for bike-sharing systems. The quality of the facilities must fulfill the demands and expectations of the users in order for the bike-sharing program to be successful. As a result, it's critical to ensure that rental bikes are accessible and available at the appropriate times for riders, as doing so decreases waiting times. The management of the bike-sharing system can be substantially aided by forecasting the necessary number of bikes and identifying the major elements that affect the demand for rental bikes.

## Dataset Information
The dataset used in this project is the Seoul Bike Share program data. This dataset contains information about the total count of rented bikes, the date of observation, and meteorological information (Humidity, Snowfall, Rainfall, Temperature Season, and so on).

#### The Seoul Bike Dataset contains the following information:
Day - Day of the week
Date - Date of the month
Month - Month of the year
Year - Year of drop off/ pick up
Hour - Hour of the day
Temperature - Temperature recorded in the city in Celsius (°C).
Humidity - Relative humidity in %
Wind speed - Speed of the wind in m/s
Visibility - Measure of distance at which object or light can be clearly discerned in units of 10m
Dew point temperature - Temperature recorded in the beginning of the day in Celsius(°C).
Solar radiation - Intensity of sunlight in MJ/m^2
Rainfall - Amount of rainfall received in mm
Snowfall - Amount of snowfall received in cm

## Rented Bike count - Count of bikes rented (target variable)

### Tools and technologies used:
The programming language used in this project is Python. The following libraries were used for data analysis and data visualization and to build a classifier for prediction.

Pandas: For loading the dataset and performing data wrangling
Matplotlib: For data visualization.
Seaborn: For data visualization.
NumPy: For some math operations in predictions.
Statsmodels: For statistical computations

## Purpose of analysis, prediction and evaluation

### Steps involved
Data Preprocessing: Checked for outliers, incorrect values, missing values, duplicates and performed data type correction.

Exploratory Data Analysis: Performed Univariate, Bivariate, and Multivariate analysis with various graphs and plots to better understand the distribution of features and their relationships.

Implementation of Regression models.

## Findings from EDA
#### Observation:
<br> Temperature: In the Temperature column, we are able to understand that the demand is low in the winter season, i.e when the temperature is lowest, which may include snowfall.
<br><br> Weather conditions: 
<br> (i) Humidity: Demand for bike rentals is less when humidity is at its lowest and highest point. Demand for bike rentals is high during moderate humidity.
<br> (ii) Dust: Demand is highest when dust is lowest. As dust in the weather increases, demand for bikes decreases.
<br> (iii) Precipitation: Demand is high when precipitation is low. As precipitation increases, demand for bikes decreases.
<br><br> Wind speed: Demand for bike rentals is highest during low wind days. As wind speed increases, demand for bikes decreases.
<br><br> Days of the week: in the Days of the Week column, we can observe the pattern of weekdays and weekends. Demand decreases on weekends, whereas on weekdays, the demand increases due to working days.
<br><br> Month: In the month column, the demand is lowest in 

## List of Models
<br>
Linear Regression
<br> Ridge Regression
<br> Lesso Regression
<br> XGBRegressor
<br> Random Forest Regressor
<br> Decision Tree Regressor
<br> Support Vector Machine (SVM)

<br><br>
The best-performing model on the test set is XGBRegressor, followed by RandomForestRegressor, DecisionTreeRegressor, RidgeRegression, LassoRegression, LinearRegression, and SVM. These rankings are based on the RMSE, and lower RMSE values indicate better model performance.
