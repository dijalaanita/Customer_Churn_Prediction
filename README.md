# Customer Churn Prediction
 Predict which customers are likely to leave (churn) based on their activity &amp; demographics using machine learning models.


## Overview
 This project analyzes telcom customer dataset to predict churn. It applies &amp; **data preprocessing, exploratiory data analysis (EDA), feature engineering, and machine learning** techniques to train and evaluate predictive models.

 ## Goals
 - Identify key triggers of customer churns.
 - Train models to predict churn probability.
 - Provide actionable insights that can help businesses reduce churn.

## Dataset
- Source: Kaggle Telco Churn Dataset (https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data)
- Rows: 7,043
- Features: 21

## Technologies Used
- Python: Data processing & modelling
- Libraries: Pandas, NumPy, Matplotlib, Scikit-learn
- Environment: Jupyter Notebook, Visual Studio Code

## Approach
1. Data Cleaning & Preprocessing
   - Handle missing values
   - Convert categorical variables
   - Convert numeric features
  
2. Exploratory Data Analysis (EDA)
   - Visualized churn rates by tenure, senior citizen status, contract type
   - Identified correlations

3. Modeling
   - Models tested: Logistic Regression, Random Forest, XGBoost

4. Evaluation
   - Metrics: Accuracy, Confusion Matrix, F-1 Score, Precision, Recall, Classification Report
  

## Results
- Best Model: XGBoost
- Accuracy: 78.89%
- Key Insights:
 - Tenure contracts and senior citizens are at higher risk of churn

## Visualizations
- XGBoost Feature Importance Plot
<img width="658" height="455" alt="xgb_importance" src="https://github.com/user-attachments/assets/b0dd7388-285c-44f8-86d4-2a62def1cae4" />

- XGBoost Confusion Matrix Plot
<img width="507" height="432" alt="xgb_confusionmatrix" src="https://github.com/user-attachments/assets/568ad1ed-f0f4-4e13-9605-36a8a0f88f71" />

- Tenure Vs. Churn Plot
<img width="580" height="455" alt="tenurevchurn" src="https://github.com/user-attachments/assets/1eb311c1-85bd-4d57-b362-2182cef3ed41" />

- Senior Citizen Vs. Churn Plot
<img width="580" height="455" alt="seniorvchurn" src="https://github.com/user-attachments/assets/0c8750ef-6e98-48b7-98ad-7945a8090f12" />

- Monthly Charges Vs. Churn Plot
<img width="580" height="455" alt="monthlyvchurn" src="https://github.com/user-attachments/assets/40aea7ac-7bc1-4b42-b7a6-f5d4f96ebcbe" />

- Logistic Regression Feature Importance Plot
<img width="630" height="470" alt="reg-importance" src="https://github.com/user-attachments/assets/d945336e-dab7-4ac2-8f44-198fffcd9c83" />

- Random Forest Feature Importance Plot
<img width="630" height="470" alt="randfor_importance" src="https://github.com/user-attachments/assets/fee46cc0-632a-4bc4-a4f5-bedc026310e0" />


## How to Run
1. **Clone the repo:** 
- git clone https://github.com/your-username/churn-prediction.git
- cd churn-prediction

2. **Install dependencies:**
- pip install -r requirements.txt

3. **Open Jupyter Notebook:**
- jupyter notebook

4. **Run the notebooks in order.**

## Future Work
- Deploy as a web app (Streamlit/Flask)
- Integrate with a live API
- Add SHAP explainability

# Author
Anita Dijala

