# Car Price Prediction with Machine Learning

## 📌 Project Overview
This project predicts the selling price of used cars using Machine Learning techniques.  
The model is trained using various car-related features such as present price, fuel type, transmission type, kilometers driven, ownership history, and car age.

The main goal is to build a regression model that can estimate a fair resale price for a car based on available data.

---

## 🎯 Objectives

- Analyze car dataset and understand important features.
- Perform data cleaning and preprocessing.
- Apply feature engineering techniques.
- Train a regression model for price prediction.
- Evaluate model performance using metrics.
- Predict price for a sample car.
- Understand real-world applications of machine learning.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset Features

- Car_Name
- Year
- Selling_Price
- Present_Price
- Driven_kms
- Fuel_Type
- Selling_type
- Transmission
- Owner

---

## ⚙️ Data Preprocessing

- Removed unnecessary spaces in column names
- Created new feature: **Car_Age**
- Dropped Year column after transformation
- Converted categorical columns using One-Hot Encoding
- Split dataset into training and testing sets

---

## 🤖 Model Used

### Linear Regression

Used to predict selling prices based on multiple input features.

---

## 📊 Model Evaluation

Performance measured using:

- **MAE (Mean Absolute Error)**
- **MSE (Mean Squared Error)**
- **R² Score**

Example Results:

- MAE: 2.04
- MSE: 9.22
- R² Score: 0.60

---

## 📈 Visualizations

### 1. Actual vs Predicted Prices
Compares real car prices with model predicted prices.

### 2. Feature Importance / Coefficient Analysis
Shows which factors influence selling price the most.

### 3. Correlation Heatmap
Displays relationships between numerical features.

---

## 🚗 Sample Prediction

Predicted price for a sample car:

**7.47 Lakhs**

---

## 🌍 Real World Applications

- Helps buyers know fair resale value.
- Assists sellers in pricing vehicles.
- Useful for online car resale platforms.
- Supports dealerships with pricing decisions.

---

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
