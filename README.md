# Credit Risk Modeling

This project was completed as part of the **J.P. Morgan Quantitative Research Virtual Experience** on Forage.

It focuses on developing a predictive model to estimate the **probability of default (PD)** for loan borrowers using customer financial data. The pipeline integrates exploratory data analysis (EDA), outlier handling, feature scaling, and machine learning techniques with hyperparameter tuning.

---

## 📊 Project Workflow

### ✅ Step 1: Data Understanding & Summary Statistics
- Reviewed key metrics like `income`, `loan_amt_outstanding`, `fico_score`, etc.
- Identified potential outliers and skewed distributions.

### ✅ Step 2: Visualize & Handle Outliers
- Used boxplots to detect outliers.
- Applied **percentile capping** to limit extreme values.

### ✅ Step 3: Feature Scaling
- Standardized numerical features using `StandardScaler` to improve model stability.

### ✅ Step 4: Model Training & Evaluation
- Split dataset into training, validation, and test sets.
- Used **GridSearchCV** to optimize hyperparameters for:
  - Logistic Regression
  - Naive Bayes
  - Random Forest

### ✅ Step 5: Final Model Selection
- Selected the model with the best **ROC-AUC score** on validation set.
- Evaluated final model on test set using:
  - Confusion Matrix
  - ROC Curve
  - Classification Metrics

---

## 🧠 Algorithms Used
- Logistic Regression
- Gaussian Naive Bayes
- Random Forest Classifier

---

## 🧪 Metrics Tracked
- Accuracy
- Precision, Recall, F1-Score
- ROC-AUC
- Confusion Matrix

---

## 🧰 Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📂 Repository Contents

| File                  | Description                             |
|-----------------------|-----------------------------------------|
| `Loan_Data.csv`       | Customer loan dataset                   |
| `Untitled.ipynb`      | Complete notebook with all analysis     |
| `README.md`           | This documentation                      |

---

## 📌 Outcome
Achieved a **ROC-AUC score of ~0.999** with the Random Forest model, demonstrating highly accurate credit risk prediction for future loan decisions.

---

## 🔗 Credits
Built as part of the **J.P. Morgan Virtual Internship Program** hosted by **Forage**.

---

