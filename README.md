# Car-Price-Prediction-System
## Description
This project predicts the price of a car based on various features such as its brand, model, age, mileage, fuel type, and transmission. The system is built using Python and employs data preprocessing, exploratory data analysis, feature engineering, and machine learning models to achieve accurate predictions.

This project demonstrates how machine learning can be applied to solve real-world problems in the automotive industry.

---

## Features
1. **Data Preprocessing**:
   - Handles missing values, outliers, and inconsistent data.
   - Encodes categorical features using techniques like one-hot or label encoding.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizes relationships between features and target variables.
   - Identifies key factors influencing car prices.

3. **Machine Learning Models**:
   - Trains multiple regression models such as:
     - Linear Regression
     - Random Forest
     - Decision Tree
     - Gradient Boosting (e.g., XGBoost, LightGBM)
   - Compares models using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.

4. **Hyperparameter Tuning**:
   - Optimizes model performance using techniques like Grid Search or Randomized Search.

5. **Prediction System**:
   - Provides predictions for car prices based on user input features.

---

## Dataset
The dataset includes the following features:
- **Car Details**: Brand, model, year of manufacture, etc.
- **Specifications**: Fuel type, transmission type, mileage, and engine capacity.
- **Target Variable**: Car price.

---

## Dependencies
Install the required Python libraries:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
