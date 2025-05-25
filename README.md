# 💳 Credit Risk Modeling – JPMorgan Chase Virtual Experience

This project was completed as part of the **JPMorgan Chase Quantitative Research Virtual Experience** on Forage. It simulates real-world tasks faced by quantitative analysts in credit risk modeling, including data preprocessing, outlier handling, predictive modeling, and credit score bucketing.

---

##  Task Overview

### ✅ Task 1: Data Exploration and Forecasting
- Analyzed historical monthly natural gas prices (Oct 2020 – Sep 2024).
- Built a forecast model using monthly seasonal averages to extrapolate prices for the next 12 months.
- Designed a function to estimate price given any future date.
- Visualized seasonality trends and future price forecasts.

### ✅ Task 2: Valuing a Natural Gas Storage Contract
- Created a pricing function to estimate the economic value of a storage contract using injected and withdrawn natural gas volumes.
- Included factors like monthly storage cost, capacity constraints, and market prices.
- Applied test cases to simulate contract value and validate strategy logic.

### ✅ Task 3: Credit Risk Prediction
- Explored and cleaned a loan dataset with borrower features and default indicators.
- Applied outlier handling (capping) and standardized numeric features.
- Built and compared three models:
  - Logistic Regression
  - Gaussian Naive Bayes
  - Random Forest Classifier
- Used `GridSearchCV` and cross-validation to optimize performance.
- Evaluated models using ROC-AUC, confusion matrices, and test accuracy.

### ✅ Task 4: FICO Score Bucketing & Default Risk Profiling
- Transformed continuous `fico_score` into discrete credit bands using `KBinsDiscretizer` (quantile-based).
- Validated that each bucket had balanced records.
- Analyzed default rates across buckets and observed a clear inverse relationship between score and default likelihood.
- Visualized the distribution and risk profile of each segment.



---

## 📈 Tools & Libraries Used
- Python (Pandas, NumPy)
- Scikit-learn (GridSearchCV, KBinsDiscretizer)
- Seaborn & Matplotlib
- Jupyter Notebook
- Git & GitHub

---

## 📌 Outcome
This project demonstrates my ability to:
- Clean and preprocess large datasets
- Engineer features and handle outliers
- Build and tune classification models
- Translate numerical risk into business-intelligible categories
- Communicate results through plots and markdown narrative

---

##  Author

**Mark-Daniels Tamakloe**  
MSc Computer Science – Washington University in St. Louis  
[LinkedIn](https://www.linkedin.com/in/mark-daniels-tamakloe-934785a9) 

---

## 🔗 Acknowledgement

This project was built as part of the [JPMorgan Chase Quantitative Research Virtual Experience](https://www.theforage.com/virtual-internships/prototype/jpmorgan-chase/quantitative-research) on Forage.



