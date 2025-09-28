# Machine Learning Projects

This repository showcases **three fully functional machine learning web applications** developed during my internship. These projects focus on practical applications of regression and classification models, data preprocessing, feature engineering, and web deployment using Flask.



## Projects Overview

### 1. Vehicle Price Prediction (Regression)
- **Purpose:** Predict vehicle prices based on specifications such as make, model, year, mileage, engine type, transmission, and drivetrain.
- **Dataset:** 13,000+ records with 21 features; raw data cleaned and structured.
- **Methodology:** 
  - Linear, Ridge, and Lasso Regression models using scikit-learn pipelines.
  - Categorical features one-hot encoded; numerical features scaled.
  - Target variable (price) log-transformed for model stability.
- **Performance:** 
  - Linear Regression R² = 0.8914  
  - Ridge Regression R² = 0.8896  
  - Lasso Regression underperformed due to over-penalization.  
  - RMSE values confirmed model accuracy.
- **Deployment:** Flask-based web interface for interactive predictions.
- **Project Link:** [Vehicle Price Prediction Repository](<https://github.com/hushisuga/Car-price-predictor>)



### 2. Mobile Price Range Prediction (Classification)
- **Purpose:** Predict the price range (0–3) of mobile phones based on RAM, battery, screen size, processor, and additional engineered features (build_score, screen_area).
- **Dataset:** 2,000 records with numerical and categorical features; no missing values.
- **Methodology:** 
  - Logistic Regression with scikit-learn pipeline.
  - Applied preprocessing steps, feature engineering, and stratified train-test split.
- **Performance:** 
  - Accuracy = 93.75%  
  - High precision, recall, and F1-score across all classes.  
  - Confusion matrix confirmed minimal misclassifications.
- **Deployment:** Flask interface with HTML forms for interactive predictions.
- **Project Link:** [Mobile Price Range Prediction Repository](<https://github.com/hushisuga/Phone-price-predictor>)


### 3. House Price Prediction (Regression)
- **Purpose:** Predict residential house prices based on location, area, number of bedrooms/bathrooms, furnishing type, and BHK/1RK indicator.
- **Dataset:** Compiled from real-world listings, cleaned and preprocessed.
- **Methodology:** 
  - Ridge Regression model evaluated with R² metric.
  - Preprocessing included scaling, encoding, and handling categorical variables.
  - Full pipeline documented in Jupyter notebooks.
- **Deployment:** Flask web app for inputting property details and receiving predicted prices.
- **Project Link:** [House Price Prediction Repository](<https://github.com/hushisuga/House-Price-Predictor>)



## Skills & Outcomes
- Applied advanced **data preprocessing** and **feature engineering** techniques on real-world datasets.
- Gained hands-on experience in **regression and classification models**, pipeline building, and evaluation metrics (R², RMSE, Accuracy, Precision, Recall, F1-score).
- Learned **web deployment of ML models using Flask**, integrating backend with frontend forms.
- Developed problem-solving, coding, and project documentation skills.
- Managed **end-to-end project workflow** from data cleaning to model deployment.



## Summary
This repository provides a **comprehensive overview of my machine learning skills** through three key projects that combine data processing, model building, and web deployment. Explore the individual repositories to see detailed implementation, code, and interactive web applications.
