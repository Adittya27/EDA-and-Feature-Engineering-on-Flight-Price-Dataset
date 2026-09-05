# ✈️ Flight Price Prediction — EDA & Feature Engineering

This project focuses on **Exploratory Data Analysis (EDA) and Feature Engineering** on a flight price dataset to prepare the data for a machine learning-based flight price prediction problem.

### 🔍 Project Overview

The dataset contains information about airlines, source and destination cities, flight routes, departure and arrival times, duration, number of stops, additional information, and ticket prices.

The notebook performs data exploration and transforms raw flight information into meaningful numerical features suitable for machine learning models.

### 🛠️ Key Steps

* Loaded and explored the Flight Price dataset using **Pandas**
* Examined dataset structure, data types, descriptive statistics, and unique values
* Identified and handled missing values
* Extracted **Day, Month, and Year** from the journey date
* Extracted **Arrival Hour/Minute** from arrival time
* Extracted **Departure Hour/Minute** from departure time
* Converted flight duration into separate **Hours and Minutes** features
* Converted the number of stops into numerical values
* Explored categorical features such as:

  * Airline
  * Source
  * Destination
  * Total Stops
  * Additional Information
* Applied **One-Hot Encoding** to categorical variables
* Prepared the dataset for subsequent machine learning modeling

### 📊 Dataset

The dataset contains **10,683 flight records** with ticket price as the target variable.

**Target Variable:** `Price`

**Important Features:** `Airline`, `Source`, `Destination`, `Route`, `Total_Stops`, `Date`, `Month`, `Year`, `Arrival_hour`, `Arrival_min`, `Departure_hour`, `Departure_min`, `Duration_Hours`, and `Duration_Min`.

### 💻 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

### 🎯 Objective

The main objective is to understand the flight pricing data, perform appropriate feature engineering, encode categorical variables, and create a machine-learning-ready dataset that can be used for **Flight Price Prediction**.

### 📚 Dataset Source

Flight Price Prediction dataset from Kaggle.
