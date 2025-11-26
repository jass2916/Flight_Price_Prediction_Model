# ✈️ Flight Price Prediction Model

This repository contains a **machine learning model** built to predict
flight ticket prices based on various travel-related features. The model
is trained using historical flight data and includes detailed
preprocessing, feature engineering, exploratory data analysis (EDA), and
model evaluation --- all implemented in the accompanying Jupyter
Notebook: **`Flight_Price_Prediction_Model.ipynb`**.

## 📘 Project Overview

Airline ticket prices fluctuate frequently due to several factors such
as travel routes, airline companies, flight duration, stops, and
departure times.\
This project uses machine learning techniques to predict the
**approximate price** of a flight using these features.

## 🗂️ Contents

-   `Flight_Price_Prediction_Model.ipynb`
    -   Data loading\
    -   Cleaning and preprocessing\
    -   Feature engineering\
    -   Exploratory Data Analysis (EDA)\
    -   Model training\
    -   Model evaluation\
    -   Final price prediction demo

## 🔧 Features Used

-   Airline\
-   Date of Journey\
-   Route\
-   Source & Destination\
-   Total Stops\
-   Duration\
-   Departure & Arrival Times\
-   Additional Information

## 🧹 Data Preprocessing Steps

-   Handling missing values\
-   Converting date-related columns to datetime\
-   Extracting useful features\
-   Encoding categorical variables\
-   Removing duplicates\
-   Splitting into training/testing datasets

## 📊 Models Used

-   Random Forest Regressor\
-   XGBoost Regressor\
-   Decision Tree Regressor\
-   Linear Regression

## 🚀 How to Run

1.  Install dependencies:

    ``` bash
    pip install pandas numpy scikit-learn matplotlib seaborn xgboost
    ```

2.  Open the notebook:

    ``` bash
    jupyter notebook Flight_Price_Prediction_Model.ipynb
    ```

3.  Run all cells to execute the full workflow.

## 📈 Results

The model predicts flight fares based on user-given input, with
performance metrics and visualizations available in the notebook.

## 📌 Future Improvements

-   Deployment using Flask / FastAPI\
-   Web UI\
-   Hyperparameter tuning\
-   Deep learning comparison models

## 👤 Author

This README corresponds to the project in
`Flight_Price_Prediction_Model.ipynb`.
Jaskaran Singh
