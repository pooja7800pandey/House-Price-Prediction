**House Price Prediction using Machine Learning**

This project focuses on predicting house prices based on key features such as area, number of bedrooms, and bathrooms using a Machine Learning approach.

## Project Overview

The goal of this project is to build a simple and interpretable model that can estimate house prices.  
We performed data preprocessing, exploratory data analysis (EDA), and trained a Linear Regression model to make predictions.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- 
## 📊 Dataset

The dataset Taken From Kaggle website :
- Area
- Number of Bedrooms
- Number of Bathrooms
- Price (Target Variable)

## Exploratory Data Analysis (EDA)

- Checked dataset shape and preview
- Handled missing values using `dropna()`
- Visualizations used:
  - Histogram (Price distribution)
  - Scatter Plot (Area vs Price)
  - Box Plot (Bedrooms vs Price)
  - Heatmap (Correlation between features)

### Key Insights:
- Price distribution is fairly uniform
- Area does not strongly correlate with price
- Bedrooms do not significantly impact price
- Overall correlation between features is weak
- 
## Model Building

- Algorithm Used: **Linear Regression**
- Train-Test Split: 80% training, 20% testing

### Features Used:
- Area
- Bedrooms
- Bathrooms

## 📈 Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### Observation:
The model does not perform very well as predictions tend to stay around an average value, indicating weak relationships between features and target.

## 📉 Results Visualization

- Actual vs Predicted Prices plotted
- Predictions do not closely follow actual values
- Indicates underfitting / lack of strong features

---

## Prediction Example

```python
new_house = {
    "Area":[2600],
    "Bedrooms":[4],
    "Bathrooms":[2]
}
