# 🏠 House Price Category Prediction using Logistic Regression

This project demonstrates a simple **machine learning pipeline** to predict house price categories based on area, number of bedrooms, and bathrooms using **Logistic Regression**.

## 📁 Dataset

The dataset used is `synthetic_house_data.csv`, which includes the following columns:
- `area`: Size of the house (in square feet)
- `bedrooms`: Number of bedrooms
- `bathrooms`: Number of bathrooms
- `price`: Selling price of the house

We categorize the `price` into 3 classes:
- `0`: Price < 300,000
- `1`: 300,000 ≤ Price < 450,000
- `2`: Price ≥ 450,000

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- scikit-learn
- Matplotlib

## 📊 Model

- **Model Used**: Logistic Regression
- **Evaluation Metrics**:
  - Accuracy
  - Classification Report (Precision, Recall, F1-Score)
  - Confusion Matrix
  - Scatter Plot: Actual vs Predicted Price Categories
