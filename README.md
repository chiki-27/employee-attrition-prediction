# Employee Attrition Prediction Using Machine Learning

This project analyzes HR employee data to predict whether an employee is likely to leave the company (attrition). The goal is to help HR teams make proactive decisions using data-driven insights.

## Dataset
- *Source:* IBM HR Analytics Employee Attrition Dataset
- *Type:* CSV file containing employee details like age, salary, job role, overtime, etc.

## Objectives
- Identify key factors influencing employee attrition.
- Train multiple ML models to predict attrition.
- Compare model performances and interpret results.

## Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- XGBoost
- Jupyter Notebook

## Steps Performed
1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Correlation Analysis
4. One-Hot Encoding of Categorical Variables
5. Model Building:
   - Logistic Regression
   - Random Forest Classifier
   - XGBoost Classifier
6. Model Evaluation (Accuracy, Confusion Matrix, Classification Report)
7. Feature Importance Analysis

## Top Features Impacting Attrition
- Total Working Years  
- Monthly Income  
- Job Level  
- Age  
- Years In Current Role  
- OverTime  

## Results
- *Best Accuracy:* ~85% using Random Forest
- *Insight:* Employees with lower job level, income, or high overtime are more likely to leave.

## How to Run
1. Clone this repository  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

   
 ##💡 To run this notebook:**
- Upload the dataset to Colab using the left sidebar → Files → Upload
- Or mount Google Drive and use a relative path

