#  Taxi_Fare_Prediction-Using  Random Forest Algorithm

# Description:

"Taxi Fare Prediction using Random Forest Algorithm: A machine learning project to predict taxi fares based on features like trip distance, passenger count, and pickup/dropoff locations.
The Random Forest algorithm is utilized for accurate regression, handling data preprocessing, feature engineering, and model evaluation.
Ideal for exploring ML regression techniques and real-world dataset applications."

# Abstract: 
In the last few years, the number of for-hire vehicles operating in NY has grown from 63,000 to more than 100,000. However, while the number of trips in app-based vehicles has increased from 6 million to 17 million a year, taxi trips have fallen from 11 million to 8.5 million. Hence, the NY Yellow Cab organization decided to become more datacentric. Then we have apps like Uber, OLA, Lyft, Gett, etc. how do these apps work? After all, that set price is not a random guess. 
 
# Problem Statement: 
Given pickup and dropoff locations, the pickup timestamp, and the passenger count, the objective is to predict the fare of the taxi ride using Random Forest. 

# Dataset Information: 
 
### Column 	Description:

* unique_id - A unique identifier or key for each record in the dataset 

* date_time_of_pickup -	The time when the ride started 

* longitude_of_pickup -	Longitude of the taxi ride pickup point 

* latitude_of_pickup -	Latitude of the taxi ride pickup point 

* longitude__of_dropoff -	Longitude of the taxi ride dropoff point 

* latitude_of_dropoff -	Latitude of the taxi ride dropoff point 

* no_of_passenger -	count of the passengers during the ride 

* amount -	(target variable)dollar amount of the cost of the taxi ride

# Scope: 

●	Prepare and analyse data  

●	Perform feature engineering wherever applicable 

●	Check the distribution of key numerical variables 

●	Training a Random Forest model with data and check it’s performance 

● Perform hyperparameter tuning 

# Table of Contents

1. **[Import Libraries](#import_lib)**
2. **[Set Options](#set_options)**
3. **[Read Data](#Read_Data)**
4. **[Prepare and Analyze the Data](#data_preparation)**
    - 4.1 - [Understand the Data](#Data_Understanding)
        - 4.1.1 - [Data Type](#Data_Types)
        - 4.1.2 - [Feature Engineering](#Feature_Eng)
        - 4.1.3 - [Summary Statistics](#Summary_Statistics)
        - 4.1.4 - [Discover Outliers](#outlier)
        - 4.1.5 - [Missing Values](#Missing_Values)
        - 4.1.6 - [Correlation](#correlation)
    - 4.2 - [Exploratory Data Analysis](#EDA)
        - 4.2.1 - [Peak hours](#Peak)
        - 4.2.2 - [Mean fare for each hour during weekdays and weekends](#Mean_Fare)
        - 4.2.3 - [Distribution of key numerical variables](#Distribution)
5. **[Random Forest](#Random_Forest)**
    - 5.1 - [Random Forest Model](#RF_Model)
    - 5.2 - [Random Forest with GridSearchCV ](#RF_CV)
6. **[Conclusion and Interpretation](#conclusion)**

# Contact:

For any inquiries or suggestions, feel free to reach out:

- *Email:* [shivanandnashi97@gmail.com](mailto:shivanandnashi97@gmail.com)
- *LinkedIn:* [Shivanand Nashi](https://www.linkedin.com/in/shivanand-s-nashi-79579821a)
