# 🌍 Global Food Prices Prediction

This project aims to analyze and predict food prices across different countries using machine learning techniques. The dataset is sourced from [data.world - Global Food Prices](https://data.world/), and several models were trained including Linear Regression, Random Forest, and XGBoost.

---

## 📊 Dataset

- Source: `Global Food Prices` from data.world
- Features include:
  - Country, Market, Commodity, Date
  - Price and Units
  - Currency, Source, and Commodity Category

---

## 📌 Project Workflow

1. **Data Cleaning**  
   - Removed nulls, duplicates, and unnecessary columns.
   - Converted date column to datetime and extracted year and month.

2. **Feature Engineering**  
   - Encoded categorical features using Label Encoding.
   - Standardized numerical features using `StandardScaler`.

3. **Outlier Removal**  
   - Used Z-score method to remove outliers in price.

4. **Feature Selection**  
   - Used `SelectKBest` with `f_regression` to choose top 20 features.

5. **Model Training**
   - Trained and evaluated:
     - ✅ Linear Regression  
     - ✅ Random Forest Regressor  
     - ✅ XGBoost Regressor  

6. **Evaluation Metrics**
   - Mean Squared Error (MSE)
   - R-squared (R²)
   - Actual vs Predicted Visualization

---

## 🤖 Models and Results

| Model                 | R² Score | MSE       |
|----------------------|----------|-----------|
| Linear Regression     | ~0.XX    | ~XXX.XX   |
| Random Forest         | ~0.XX    | ~XXX.XX   |
| XGBoost Regressor     | ~0.XX    | ~XXX.XX   |

_Actual scores can be found in the notebook result outputs._

---

## 📈 Visualizations

- Feature Importances
- Actual vs Predicted Price Scatter Plot

---

## Main libraries used:
  pandas
  numpy
  matplotlib
  scikit-learn
  xgboost
