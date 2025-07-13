# Salary Prediction

## Introduction
This project aims to predict salaries based on various factors, such as age, gender, education level, job title, and years of experience. We have used a dataset to develop and evaluate our salary prediction model.

## Dataset
Filename- Salary Data.csv

Sample columns:- 

    *Age
    
    *Gender
    
    *Educational Level
    
    *Job Title
    
    *Years of Experience
    
    *Salary
    
## Data Preprocessing

### Handling Missing Values
We checked for missing values in the dataset and removed rows with missing data, ensuring a clean dataset for modeling.

### encoding categorical columns

### train test split

## Model Building and Evaluation

### Model Selection
We have used Random Forests Regressor to build our salary prediction model, which gives good predictions.

### Model Evaluation

Model's performance was evaluated using several regression metrics, including Root Mean Squared Error (RMSE), and R-squared (R2) score. These metrics help assess the accuracy and reliability of the predictions.

## Results

The Random Forest model achieved the highest R-squared score and the lowest error metrics (RMSE), indicating superior predictive performance compared to the other models.

## Conclusion

In conclusion, the Random Forest model demonstrated the best predictive capability for salary estimation in this dataset. 

The model evaluation and feature importance analysis provided valuable insights for understanding salary determinants and highlighted the importance of choosing the appropriate machine learning model for regression tasks.

This salary prediction model can be used to make informed salary estimates based on individual characteristics, making it a valuable tool for HR analytics and compensation planning.In conclusion, our salary prediction model, trained on a well-preprocessed dataset, successfully predicts salaries based on various factors. This project demonstrates the importance of data preprocessing, feature engineering, and model selection in creating an accurate predictive model.
