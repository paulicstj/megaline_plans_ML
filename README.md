# 🤖 Megaline Plans – Predictive Plan Recommendation with Machine Learning
## 🔍 Project Functionality
This project aims to support the telecom company Megaline in recommending optimal mobile plans to its users. Many customers are still on outdated plans, and the company wants to predict whether a user should switch to the "Smart" or "Ultra" plan, based on their behavior. A machine learning classification model was developed using customer usage data to automate and optimize this decision.

## 🛠️ Technologies and Methods
Python with Scikit-learn, NumPy, Pandas

**Classification models:**

Decision Tree (optimized via max depth loop)

Logistic Regression

Random Forest (tuned with nested hyperparameter loop)

**Model evaluation:**

Accuracy score on training, validation, and test sets

Sanity check on overfitting

Accuracy target threshold: ≥ 0.75

Target variable: is_ultra (1 = Ultra, 0 = Smart)

Features used: calls, minutes, messages, mb_used

## 📈 Key Findings and Conclusion
Three models were trained and evaluated: Decision Tree, Logistic Regression, and Random Forest.

The best-performing model was a Random Forest with:

n_estimators = 50

max_depth = 10

Validation accuracy ≈ 88% and Test accuracy ≈ 78%

The model exceeded the required performance threshold and passed sanity checks.

**Recommendation:** Megaline should implement the Random Forest model to support customer transition to new plans. This model provides a robust and data-driven way to suggest the most suitable option based on user behavior.
