# CodeAlpha_CarPricePrediction
Machine Learning model to predict car selling prices using Random Forest Regressor with feature engineering and data visualization.


# Car Price Prediction with Machine Learning 🚗

## Project Overview
Machine Learning model to predict used car selling prices using
Random Forest Regression with feature engineering, exploratory
data analysis, visualization, and model comparison.

## Dataset Information
- Total Records: 303
- Source: Kaggle — Car Price Dataset

## Features in Dataset
- Car_Name
- Year
- Selling_Price (Target Variable)
- Present_Price
- Driven_kms
- Fuel_Type
- Selling_type
- Transmission
- Owner

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Project Workflow
1. Data Loading
2. Data Exploration
3. Data Visualization
4. Feature Engineering
5. Data Preprocessing
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Feature Importance Analysis
10. New Car Price Prediction

## Visualizations Created
- Selling Price Distribution
- Cars by Fuel Type
- Selling Price by Fuel Type
- Correlation Heatmap
- Year vs Selling Price Scatter Plot
- Actual vs Predicted Price Plot
- Feature Importance Bar Chart

## Feature Engineering
A new feature was created:

- Car_Age = Current Year - Manufacturing Year

This feature improved the model's ability to understand
vehicle depreciation over time.

## Machine Learning Models Used

### Linear Regression
Used as a baseline regression model.

### Random Forest Regressor
Selected as the final model due to superior predictive performance.

**Parameters:**
- n_estimators = 100
- random_state = 42

## Model Comparison

| Metric | Linear Regression | Random Forest |
|----------|----------|----------|
| R² Score | 84.67% | 95.99% |
| RMSE | 1.88 Lakhs | 0.96 Lakhs |
| MAE | 1.22 Lakhs | 0.64 Lakhs |

Random Forest significantly outperformed Linear Regression
and was selected as the final model.

## Results

| Metric | Result |
|----------|----------|
| Final Model | Random Forest Regressor |
| R² Score | 95.99% |
| RMSE | 0.96 Lakhs |
| MAE | 0.64 Lakhs |

## Key Insights
- Present Price is the most influential feature in predicting car value.
- Diesel vehicles generally have higher resale values than Petrol vehicles.
- Car age significantly affects resale price.
- Vehicles with lower mileage tend to have higher market value.
- First-owner vehicles generally command better resale prices.
- Random Forest delivered highly accurate predictions with strong generalization performance.

## Skills Demonstrated
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Regression Modeling
- Model Evaluation
- Feature Importance Analysis
- Predictive Analytics
- Machine Learning with Scikit-Learn

## Future Improvements
- Hyperparameter Tuning
- Cross Validation
- Deployment using Streamlit or Flask
- Integration with Real-Time Car Market Data

## How to Run

1. Clone this repository

```bash
git clone <repository-url>
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the notebook

```bash
jupyter notebook car_price_prediction.ipynb
```

4. Run all cells sequentially

## Author

Shreyansh Gupta B.Tech (CSDS) 
Galgotias College of Engineering & Technology
