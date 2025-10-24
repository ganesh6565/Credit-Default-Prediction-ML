🏦 Credit Default Prediction using Machine Learning

This project focuses on predicting whether an individual will default on their credit payments within the next two years. It uses machine learning classification models, WOE (Weight of Evidence) encoding, and class imbalance handling to improve prediction performance.

📌 Project Overview

Goal: Predict the risk of credit default

Dataset: Give Me Some Credit (Kaggle)

Target Variable: SeriousDlqin2yrs (1 = default, 0 = no default)

Challenge: Class imbalance — very few default cases

✅ Key Steps & Techniques Used
Step	Description
🔹 EDA	Missing values, outliers, correlation
🔹 Data Cleaning	Imputation, feature scaling
🔹 Class Imbalance Handling	SMOTE & Class weights
🔹 Feature Engineering	Weight of Evidence (WOE)
🔹 Models	Logistic Regression, Random Forest, XGBoost
🔹 Evaluation Metrics	Recall, Precision, F1-score, ROC-AUC
🧠 Machine Learning Models Used

Logistic Regression

Random Forest Classifier

XGBoost Classifier

Best Performing Model ✅
👉 XGBoost + WOE + Class Weights

📊 Model Performance
Metric	Score
Accuracy	~ 93%
Precision	Improved using class weights
Recall	Increased after SMOTE
ROC-AUC	0.85+ (Good discrimination ability)

Note: Accuracy alone is misleading due to class imbalance.
We focus on improving recall & ROC-AUC for default prediction.

📈 ROC Curve Example

(Insert image later if needed — I can provide the plot file as well)

📂 Project Structure
Credit-Default-Prediction-ML/
│── data/
│   └── GiveMeSomeCredit.csv
│── notebooks/
│   └── pro2.ipynb
│── models/
│   └── best_model.pkl  (optional)
│── README.md
│── requirements.txt
│── .gitignore

🛠️ Technologies Used
Tool	Purpose
Python	Programming
Pandas, NumPy	Data Processing
Scikit-Learn	ML models & evaluation
Imbalanced-Learn	SMOTE
Matplotlib, Seaborn	Visualizations
💡 Future Enhancements

Deploy model using Flask/Django

SHAP-based feature interpretability

Live dashboard for real-time default risk

Hyperparameter optimization (Bayesian Tuning)

📌 Conclusion

✔ Improved prediction of high-risk users
✔ Business value: Helps financial institutions reduce losses
✔ Demonstrates ML for real-world financial risk problem-solving

📬 Contact

Developer: Your Name
📧 Email:ganeshprasadnayak03@gmail.com
🔗 LinkedIn: http://linkedin.com/in/ganesh-prasad-nayak-151564229 # Credit-Default-Prediction-ML
Prediction of default risk using machine learning and WOE feature engineering
