# PORTER – Food Delivery Time Prediction

## Overview
PORTER is an India-based logistics company operating across multiple sectors, including food delivery services. With partnerships established with a wide range of food establishments and a customer base exceeding 5 million users, accurate delivery time estimation is critical for operational efficiency and customer satisfaction.

This project focuses on developing a predictive model to estimate **food delivery time**, measured from the moment an order is placed until it reaches the customer. The model leverages variables that exhibit strong correlations with delivery duration to produce reliable predictions.

## Objectives
- Identify key factors influencing food delivery time
- Build and evaluate regression models for delivery time prediction
- Optimize model performance through hyperparameter tuning
- Deploy the best-performing model for practical usage

## Dataset
- Source: Internal operational dataset
- Scope: Food delivery orders across multiple regions
- Key features include:
  - Order details
  - Distance and location-related variables
  - Time-related attributes
  - Operational and logistical indicators

## Tools & Technologies
- Python
- pandas, numpy
- scikit-learn
- XGBoost
- Streamlit
- Data visualization libraries

## Methodology
1. **Exploratory Data Analysis (EDA)**  
   Conducted to understand data distribution, detect anomalies, and identify relationships between variables.

2. **Data Cleaning & Preprocessing**  
   - Removal of outliers  
   - Elimination of irrelevant columns  
   - Feature categorization based on relevance to delivery time prediction

3. **Model Development**  
   - Initial model built using **Linear Regression**
   - Model performance evaluated using appropriate regression metrics
   - Hyperparameter tuning applied to improve predictive accuracy

4. **Model Optimization**  
   - **XGBoost Regression** tested and compared against baseline models
   - XGBoost identified as the best-performing model due to superior accuracy

5. **Deployment**  
   - Final model deployed using **Streamlit**
   - Enables interactive and user-friendly prediction access

## Results
- XGBoost Regression outperformed baseline regression models
- Improved prediction accuracy for food delivery time estimation
- Deployment via Streamlit allows real-time usage and accessibility

## Repository Structure
- `README.md` – Project overview and documentation
- Python scripts – Data processing, modeling, and evaluation
- Datasets – Cleaned and processed data files
- Reports – Analysis summaries and project documentation
- `resources/` – Supporting files and references

## Conclusion
This project demonstrates the end-to-end machine learning workflow, from data exploration and preprocessing to model optimization and deployment. The resulting model provides a practical solution for estimating food delivery times and highlights the effectiveness of gradient boosting techniques in regression-based prediction tasks.

## Future Improvements
- Incorporate real-time traffic and weather data
- Experiment with additional ensemble models
- Improve deployment scalability

