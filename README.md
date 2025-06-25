# 🏡 House Price Prediction - King County, USA

This project is part of the **IBM Data Analysis with Python** final assignment. It focuses on **analyzing and predicting housing prices** in King County, which includes Seattle, using machine learning models built in Python.

## 📌 Project Objective

To predict housing prices based on various property features such as square footage, number of bedrooms, bathrooms, waterfront view, grade, and location. The analysis is conducted using:
- Data exploration & visualization
- Correlation analysis
- Linear regression
- Polynomial regression
- Ridge regression
- Scikit-Learn pipelines
- Model evaluation with R² score

---

## 📊 Dataset Information

- 📍 **Location:** King County, USA (Seattle area)
- 📆 **Timeframe:** May 2014 – May 2015
- 🏠 **Features include:**
  - `price` (target variable)
  - `bedrooms`, `bathrooms`, `sqft_living`, `floors`, `view`, `waterfront`
  - `condition`, `grade`, `lat`, `long`, `yr_built`, `yr_renovated`
  - `sqft_above`, `sqft_basement`, `zipcode`, etc.

---

## ⚙️ Technologies Used

- Python 3.x  
- Jupyter Notebook  
- Pandas, NumPy  
- Seaborn & Matplotlib  
- Scikit-Learn (`LinearRegression`, `PolynomialFeatures`, `Ridge`, `Pipeline`)  

---

## 📈 Steps Performed

1. **Data Cleaning:**
   - Dropped unnecessary columns (`id`, `Unnamed: 0`)
   - Handled missing values

2. **Exploratory Data Analysis (EDA):**
   - Used `.value_counts()` and `.boxplot()` for categorical features
   - Identified outliers and strong correlations using `corr()`

3. **Modeling:**
   - Simple linear regression (e.g., `sqft_living` vs `price`)
   - Multiple linear regression with multiple features
   - Polynomial regression with pipeline
   - Ridge regression with different alpha values

4. **Evaluation:**
   - R² scores calculated for all models
   - Used training/testing split
   - Grid Search CV for hyperparameter tuning

---

## 🔍 Example Results

| Model Type         | R² Score (Example) |
|--------------------|-------------------|
| Linear Regression  | ~0.50             |
| Polynomial (deg=2) | ~0.75             |
| Ridge Regression   | ~0.78             |

*(Note: Actual values may vary based on train/test split and feature selection)*

---

## 📎 Screenshots

Included in this repository:
- 📸 Screenshots for each question in the assignment
- 📓 Jupyter notebook: `House_Sales_in_King_Count_USA.ipynb`

---

## 🧾 Credits

- **Course:** [IBM Data Analysis with Python - Coursera](https://www.coursera.org/learn/data-analysis-with-python)
- **Dataset Source:** [Kaggle - King County House Sales](https://www.kaggle.com/harlfoxem/housesalesprediction)

---

## ✅ Badge Earned

![IBM Badge](https://images.credly.com/size/340x340/images/1e6eac2f-94f4-49ae-bc50-eaa1d67e0463/Data_Analysis_with_Python.png)

This project contributed to earning the [IBM Data Analysis with Python](https://www.credly.com/org/ibm/badge/data-analysis-with-python) digital badge.

---

## 🔗 Author

**غيداء الديراوي**  
> Project Repository: [GitHub](https://github.com/GhydaaAldirawy/Project-Data-Analytics-for-House-Pricing-Data-Set)
