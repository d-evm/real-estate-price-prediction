
# Bengaluru House Price Prediction

This repository contains a machine learning project aimed at predicting house prices in Bengaluru based on various features such as location, square footage, number of bedrooms, and bathrooms. The project involves data preprocessing, feature engineering, and model training to achieve accurate predictions.

## Dataset
The dataset used is **Bengaluru_House_Data.csv**, which contains information about real estate properties in Bengaluru. [Dataset from Kaggle](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)

## Features
- **Data Cleaning**: Removal of unnecessary columns and handling missing values.
- **Feature Engineering**: Conversion of categorical data to numerical, outlier removal, and dimensionality reduction.
- **Model Training**: Multiple machine learning algorithms including:
  - Linear Regression
  - Decision Tree Regression
  - Hyperparameter tuning using GridSearchCV

## Libraries Used
- **pandas**
- **numpy**
- **matplotlib**
- **scikit-learn**

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/d-evm/real-estate-price-prediction.git
   ```
2. Ensure all dependencies are installed:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook (`main.ipynb`) to see the step-by-step implementation.

## Results
The model predicts house prices based on user input features like location, size, and amenities.

---

Feel free to contribute to the project or raise issues for improvements.
