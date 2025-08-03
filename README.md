# 🎥 Movie Rating Prediction using Python

A **Data Science project** that predicts movie ratings based on various features like genre, runtime, budget, cast popularity, and more. This project walks through the entire data science lifecycle — from data preprocessing and exploration to model building and evaluation.

## 🧠 Project Overview

The aim of this project is to **predict the IMDb rating of a movie** using supervised learning techniques. By analyzing key factors influencing movie success, such as production details, crew, and genre, the model provides reliable predictions for unseen data.

This project showcases skills in:
- Data cleaning and wrangling
- Feature engineering
- Exploratory Data Analysis (EDA)
- Model training, tuning, and evaluation
- Regression metrics interpretation

## 📂 Dataset

The dataset used contains movie metadata including:
- Title, Genre, Runtime, Release Year
- Budget, Revenue
- Director and Cast popularity
- IMDb Rating (Target Variable)

Data Source:[  https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies](url)


## ⚙️ Technologies & Tools

- **Language**: Python
- **Libraries**: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
- **Environment**: Jupyter Notebook / Google Colab

## 📌 Key Features

- Handled missing and inconsistent data
- Engineered new features like cast popularity index and director impact score
- Performed detailed visualizations (correlation heatmap, distribution plots, etc.)
- Trained multiple models: Linear Regression, Random Forest, Gradient Boosting
- Evaluated models using R², RMSE, MAE

## 🔍 EDA Highlights

- Top genres by rating
- Correlation between budget and rating
- Impact of runtime on audience reception
- Visualization of rating distribution


predicted_rating = model.predict(sample)
print(f"Predicted Rating: {predicted_rating:.2f}")
