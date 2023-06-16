# BANGALURU HOUSE PRICE PREDICTION 

This project mains on predicting house prices in Bangalore, India using machine learning. The aim is to build a model that can estimate the prices of houses based on various factors such as tatol_sqft, bath, BHK, price and locations.
Predicting Banglore property prices accurately may give useful information to purchasers, sellers, and real estate agents, to make informed decisions.

## Dataset 

The dataset contains a collection of house listings in Bangalore. It includes information on the Area Type, Availability, Locations, bathrooms, balconies, Size, Society, Total SQFT and along with their corresponding prices.

Link for Dataset: 
https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data

## Data Preprocessing

1) Data Cleaning:  I have fixed and removed incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset. 

2) Feature Engineering: I have created an additional feature called price_per_sqft to perform dimensional data reduction.

3) Outlier Removal: I have removed Outliers like, there was a variation in total_sqft and the number of bedrooms for example 600.0 total_sqft and 8 bedrooms, So it was an extreme variation in the dataset and to remove outliers from price_per_sqft like some location had a maximum price and some had minimum so I have created a function which uses the methods like mean and standard deviation and then filtered the data points which are beyond the one standard deviation.


## Model Scores 
![Screenshot 2023-06-17 000314](https://github.com/JV456/Bangaluru-House-Price-Prediction/assets/99525324/044d3764-d986-4685-8d15-2e21ffbf1c73)

![Screenshot 2023-06-17 000411](https://github.com/JV456/Bangaluru-House-Price-Prediction/assets/99525324/c4307d42-49c7-4284-b200-e8019cf77de7)

![Screenshot 2023-06-17 000515](https://github.com/JV456/Bangaluru-House-Price-Prediction/assets/99525324/4ee97781-2969-43a2-868c-4aaec68da93b)




