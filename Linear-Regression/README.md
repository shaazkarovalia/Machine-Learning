# 📊 Insurance Price Prediction using Linear Regression

This project predicts medical insurance charges for individuals based on their features such as age, BMI, gender, number of children, and more. The primary goal is to understand the relationship between these features and insurance prices using a **Linear Regression** model.

## 🚀 Overview

Given a dataset containing demographic and health-related attributes, this project aims to:
- Explore and visualize the data (EDA)
- Preprocess it using techniques like one-hot encoding and feature scaling
- Train a linear regression model
- Evaluate model performance using loss functions

## 📁 Dataset Features

- `age` — Age of the individual
- `sex` — Gender (`male`, `female`)
- `bmi` — Body Mass Index
- `children` — Number of children covered by insurance
- `smoker` — Whether the individual is a smoker
- `region` — Geographic region in the US
- `charges` — Medical insurance cost (target variable)

## 🔍 Exploratory Data Analysis (EDA)

- Visualized feature distributions (e.g., age, BMI)
- Analyzed relationships between features and insurance charges
- Identified potential outliers and patterns
- Checked correlations between numeric features

## ⚙️ Preprocessing Steps

- Applied **One-Hot Encoding** to categorical variables (`sex`, `smoker`, `region`)
- Performed **Feature Scaling** on continuous variables to normalize the data
- Split the dataset into training and testing sets

## 🧠 Model Used

- **Linear Regression** — A fundamental regression algorithm that finds the best-fitting line by minimizing the loss.

## 📉 Loss Function

- Used **Mean Squared Error (MSE)** to evaluate model performance
- Compared training vs testing loss to identify overfitting/underfitting

## ✅ Results

- Achieved reasonable accuracy with a simple model
- Demonstrated how even basic algorithms like linear regression can provide useful insights when applied with proper preprocessing

## 📌 Key Learnings

- Importance of EDA before modeling
- Handling categorical data for regression models
- The role of feature scaling
- Interpreting model loss and performance

## 📚 Future Improvements

- Try advanced regression models (e.g., Ridge, Lasso, Polynomial Regression)
- Perform hyperparameter tuning
- Deploy the model with a UI for real-time predictions

---

Feel free to check out the notebook and explore the results yourself!
