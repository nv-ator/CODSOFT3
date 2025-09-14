#CODSOFT
# 📘 Movie Rating Prediction — README.md  
# Movie Rating Prediction 🎬

## Overview
This project predicts IMDb movie ratings based on features such as genre, director, and actors using regression models.  

## Dataset
- Source: [IMDb Movies India Dataset](https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies)  
- Features: Title, Genre, Director, Actors, Duration, Votes, etc.  
- Target: IMDb Rating  

## Workflow
1. Data preprocessing (handling missing values, encoding categorical features with OneHotEncoder)  
2. Splitting into train and test sets  
3. Training multiple models:
   - Linear Regression  
   - Decision Tree Regressor  
   - Random Forest Regressor  
   - Gradient Boosting Regressor  
   - SVR  
4. Model evaluation using MAE, MSE, and R² Score  
5. Best model selection and sample predictions  

## Results
- Linear Regression underperformed (underfitting).  
- **Gradient Boosting Regressor** and **Random Forest Regressor** performed best.  
- Still challenging to predict extreme ratings due to limited dataset features.  

## Sample Prediction
