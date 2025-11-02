# EasyVisa

📌 Project Overview
EasyVisa is a data-driven solution designed to assist the Office of Foreign Labor Certification (OFLC) in streamlining U.S. visa approvals. With rising application volumes, manual review has become increasingly tedious. This project leverages classification models to predict visa outcomes and recommend suitable applicant profiles based on key influencing factors.

🎯 Objective
Predict whether a visa application will be Certified or Denied

Identify the most influential features affecting visa decisions

Support OFLC in prioritizing high-potential applications

📊 Dataset Description
The dataset contains 25,480 records with 12 features, including:

Applicant details: continent, education, job experience, training needs

Employer details: number of employees, year of establishment

Job specifics: region of employment, prevailing wage, wage unit, full-time status

Target variable: case_status (Certified/Denied)

🔍 Key Insights from EDA
Applicants with higher education, job experience, and full-time positions have higher approval rates

Midwest region shows the highest visa approval rate

Higher prevailing wages correlate with increased chances of certification

Larger companies tend to have more successful applications

🧠 Modeling Approach
Data preprocessing: handled outliers, encoded categorical variables, and balanced classes using SMOTE and undersampling

Models evaluated: Random Forest, Gradient Boosting, XGBoost, AdaBoost, Bagging, Decision Tree

Evaluation metric: F1 Score to balance precision and recall

🏆 Best Performing Models
Gradient Boosting and AdaBoost (after hyperparameter tuning) showed generalized performance on validation data

XGBoost also performed well with balanced precision and recall
