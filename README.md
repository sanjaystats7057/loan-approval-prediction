# loan-approval-prediction
Predicting loan approval using XGBoost, SMOTE, and feature selection
#  Credit Risk Analysis using XGBoost & Random Forest

This project focuses on predicting whether a loan application will be approved or not based on historical financial data. With over 1 million data points, we perform end-to-end Credit Risk Analysis using supervised machine learning techniques.

---

##  Problem Statement

To predict the risk of loan default based on customer financial behavior and demographic features. The goal is to help financial institutions assess creditworthiness effectively using machine learning models.

---

##  Dataset Overview

-  Total Rows: 1,000,001  
- Target Variable: `LoanApproved`  
-  Imbalance Issue: Addressed using SMOTE  
-  [Download Full Dataset (Google Drive)](https://drive.google.com/file/d/1l_0v6cxfHBM82a3dXFE8qb55pBhRZlz1/view?usp=drive_link)

---

##  EDA (Exploratory Data Analysis)

- Checked for missing values  
- Visualized class imbalance  
- Plotted distributions of income, credit score, expenses, etc.  
- Correlation heatmap to identify important features

---

##  Machine Learning Models

| Model             | Accuracy | AUC Score | After SMOTE |
|------------------|----------|-----------|--------------|
| Random Forest     | 75%      | 0.80      | ✅            |
| XGBoost (Tuned)   | 75%      | 0.80      | ✅            |

---

##  Feature Engineering

- Top 30 features selected using XGBoost importance  
- Handled class imbalance using SMOTE  
- Hyperparameter tuning via `RandomizedSearchCV`

---

##  Visualizations

- ROC Curve & Precision-Recall Curve  
- Class Imbalance Before & After SMOTE  
- Feature Importance Bar Charts  
- Confusion Matrix Heatmaps

---

##  Technologies Used

- Python  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn, XGBoost, imbalanced-learn  
- Google Colab

---

##  Project Highlights

- Handled 1 million+ rows efficiently  
- Applied SMOTE to handle class imbalance  
- Tuned XGBoost model for optimal performance  
- Compared Random Forest and XGBoost models

---

##  Project Structure
loan-approval-prediction/
│
├── credit_risk_analysis.ipynb # Main notebook
├── README.md # This file
├── .gitignore # File exclusions


---

##  How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/sanjaystats7057/loan-approval-prediction.git
2. Open the notebook in Google Colab or Jupyter

3. Run all cells step by step

Contact

Made with ❤️ by Sanjay Chaudhary
📧 sanjay.chaudhary.stats@gmail.com
🔗 https://www.linkedin.com/in/sanjay-chaudhary-0599b0248

