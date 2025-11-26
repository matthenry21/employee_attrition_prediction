# 📊 Employee Attrition Prediction

End-to-End HR Analytics & Machine Learning Project

By Mathews Henry — Aspiring Data Scientist

🚀 Project Overview

Employee attrition is a major challenge for organizations.
This project builds a machine learning pipeline to identify key drivers of attrition and predict which employees are at risk of leaving.

The workflow includes:

	•	Exploratory Data Analysis (EDA)
	•	Feature engineering
	•	Model training (Logistic Regression, Decision Tree, Random Forest)
	•	Hyperparameter tuning (refit: ROC-AUC)
	•	Insight generation & actionable HR recommendations

The Random Forest model emerged as the champion model with strong generalization on test data.

🎯 Business Objective

	•	Understand patterns behind employee turnover
	•	Identify the key factors that influence attrition
	•	Provide HR with data-driven insights
	•	Build an ML model that predicts employee attrition risk

  🧠 Key Insights from EDA
  
	•	Overwork strongly drives attrition — high monthly hours = high risk
	•	Employees handling 7 projects always left
	•	Tenure between 2–4 years shows the highest turnover risk
	•	Lack of promotion in the last 5 years significantly increases exits
	•	Salary is not a strong predictor of attrition in this dataset

  🛠️ Models Used

✔ Logistic Regression

- Baseline classifier to understand linear relationships.

✔ Decision Tree

- Interpretable model used to understand decision rules.

✔ Random Forest

- Tuned with GridSearchCV (refit = ROC-AUC)
- ✔ Best performance on validation & test sets
- ✔ Strong generalization
- ✔ Selected as the champion model


🔧 Feature Engineering

	•	Removed potential leakage features (e.g., satisfaction level)
	•	Created a new binary feature: overworked
	•	True if monthly hours > 175
	•	Encoded categorical variables
	•	Train–validate-test split
	•	Standard preprocessing pipeline

📦 Tech Stack

	•	Python
	•	Pandas, NumPy
	•	Scikit-learn
	•	Matplotlib, Seaborn

  📝 Results

The final Random Forest model can effectively identify high-risk employees and provide HR with insight-driven recommendations such as:

	•	Monitor early-tenure employees (2–4 years)
	•	Intervene for overworked staff
	•	Track promotion stagnation
	•	Balance project assignments

  📬 Contact

Mathews Henry
Aspiring Data Scientist & Machine Learning Enthusiast
📧 LinkedIn: http://linkedin.com/in/mathewshenry-data-scientist




  

  
