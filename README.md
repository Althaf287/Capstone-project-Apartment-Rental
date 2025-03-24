# Apartment Rental Prediction - Capstone Project

**Name:** Althaf N

**Organization:** Entri Elevate

### Project Overview

This project aims to predict apartment rental prices based on various features such as location, square feet, number of bedrooms, and other relevant attributes. Using machine learning techniques, we develop a predictive model that assists renters and property managers in estimating fair rental prices.

### Features & Objectives
- **Develop an accurate machine learning model to predict rental prices.**
- **Perform exploratory data analysis (EDA) to uncover patterns and insights.**
- **Apply feature engineering techniques to enhance model performance.**
- **Evaluate multiple regression algorithms to find the best-performing model.**
- **Deploy the trained model for real-world use.**

### Project Structure
├── data/                     # Dataset files
├── notebooks/                # Jupyter notebooks for analysis and modeling
├── src/                      # Source code for data processing and model training
├── models/                   # Saved models
├── results/                  # Predicted results and evaluation reports
├── README.md                 # Project documentation (this file)
└── requirements.txt          # Required Python packages

 # Data Description

The dataset contains various features relevant to apartment rentals, including:

- **Location (City, Neighborhood)**
- **Square Footage**
- **Number of Bedrooms & Bathrooms**
- **Amenities & Features**
- **Rental Price (Target Variable)**

### Data Source
The dataset used in this project is sourced from the UCI Machine Learning
Repository:https://archive.ics.uci.edu/dataset/555/apartment+for+rent+classified
Apartment for Rent Classified Dataset

### Exploratory Data Analysis (EDA)
Key insights from EDA include:
- **Distribution of rental prices across different locations.**
- **Correlation between apartment size and rental cost.**
- **Influence of additional features (e.g., parking, pet-friendliness) on pricing.**
  
### Machine Learning Models Implemented
The following regression models were tested:
- **Linear Regression**
- **Decision Tree Regressor**
- **Support Vector Regression (SVR)**
- **Random Forest Regressor (Best performing model )**
- **Gradient Boosting Regressor**
- **MLP Regressor (Neural Network)**
- **AdaBoost Regressor**
  
 ### Model Evaluation
The models were evaluated using the following metrics:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**
  
### Best Performing Model: Random Forest Regressor

- **RMSE: 192.16 (Lowest, indicating best accuracy)**
- **R² Score: 0.84 (Explains 84% variance in data)**
- **MAE: 124.71 (Least average error)**
  
### Project Phases
- **Phase 1: Data Collection (Source code)**
- **Phase 2: Exploratory Data Analysis (jupyter note)**
- **Phase 3: Model Development (jupyter note)**
- **Phase 4: Final Report & Predictions (jupyter note_Results)**

### Future Work
- **Implement deep learning models for better accuracy.**
- **Enhance dataset with additional real estate factors.**
- **Deploy the model using Flask/Django API.**

  # **THANKYOU**
