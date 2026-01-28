📌 Project Overview

Customer churn is a critical business problem where companies lose customers to competitors. This project focuses on predicting customer churn using traditional Machine Learning models, with special emphasis on cost-sensitive learning and threshold optimization to reflect real-world business trade-offs.

The goal is not just accuracy, but minimizing business loss caused by false negatives (missed churners).

🎯 Business Objective

Identify customers likely to churn

Reduce revenue loss by prioritizing recall of churners

Compare baseline and advanced ML models under cost constraints

🧠 Machine Learning Approach

Models implemented:

Logistic Regression (baseline)

Random Forest

XGBoost (tuned)

Key techniques used:

Feature encoding & scaling

Class imbalance handling

Cost-sensitive evaluation

Threshold tuning

ROC-AUC & Precision-Recall analysis

📊 Dataset

Source: Telecom Customer Churn Dataset

Size: ~7,000 records

Target variable: Churn (Yes / No)

Features include:

Demographics

Service usage

Contract & billing information

⚙️ Model Evaluation Metrics

Instead of accuracy alone, we focus on:

Precision

Recall

F1-Score

ROC-AUC

Confusion Matrix

Business-oriented threshold selection

🔍 Key Results

XGBoost outperformed Logistic Regression after hyperparameter tuning

Threshold optimization significantly improved churn detection

Demonstrated how business costs change optimal decision boundaries

📈 Visualizations

Confusion Matrix

ROC Curve

Feature Importance (XGBoost)

(Stored inside /images directory)

🚀 How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/your-username/customer-churn-prediction-cost-sensitive-ml.git
cd customer-churn-prediction-cost-sensitive-ml
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Run the notebook

Open:

notebooks/Customer_Churn_Analysis.ipynb
📌 Skills Demonstrated

Machine Learning modeling

Business-driven ML decisions

Cost-sensitive learning

Model evaluation & threshold tuning

XGBoost hyperparameter optimization

Data preprocessing & EDA

🔮 Future Improvements

SHAP explainability

Model monitoring

Cost-based loss function integration

Deployment (API / dashboard)

👤 Author

Anuj Negi
Aspiring Machine Learning Engineer
📫 LinkedIn | GitHub
