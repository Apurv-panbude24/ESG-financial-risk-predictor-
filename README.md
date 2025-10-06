# ESG Financial Risk Predictor

## 📘 Overview
The **ESG Financial Risk Predictor** is a data-driven project that combines **Environmental, Social, and Governance (ESG)** metrics with **financial data** to predict the financial risk level of companies.  
This project demonstrates a complete data science workflow — from data cleaning and preprocessing to model building, evaluation, and interpretation.

---

## 🎯 Objective
To build a predictive model that classifies companies into **Low**, **Medium**, or **High Financial Risk** categories based on:
- ESG scores and components (Environmental, Social, Governance)
- Key financial metrics (Market Cap, Price/Earnings, Price/Book, Dividend Yield, etc.)

---

ESG-Financial-Risk-Predictor/
├─ data/
│ ├─ raw/ # Raw ESG and financial datasets
│ ├─ processed/ # Cleaned and merged datasets
├─ notebooks/
│ ├─ 01_data_cleaning.ipynb
│ ├─ 02_eda.ipynb
│ ├─ 03_feature_engineering.ipynb
│ ├─ 04_model_training.ipynb
│ ├─ 05_model_evaluation.ipynb
├─ models/ # Trained models and scalers
├─ src/
│ ├─ data_processing.py
│ ├─ feature_engineering.py
│ ├─ modeling.py
│ ├─ evaluation.py
│ ├─ predict.py
├─ requirements.txt
├─ README.md
└─ LICENSE


---

## ⚙️ Technologies Used
- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**
- **XGBoost / LightGBM**
- **SHAP** (Model Explainability)
- **Jupyter Notebook**

---

## 🔍 Methodology
1. **Data Gathering:**  
   ESG and financial datasets are collected and merged on a common identifier (e.g., company ticker or name).

2. **Data Cleaning & Preprocessing:**  
   - Handle missing values  
   - Normalize numerical columns  
   - Encode categorical variables  

3. **Exploratory Data Analysis (EDA):**  
   - Correlation analysis between ESG and financial metrics  
   - Outlier detection and feature distributions  

4. **Feature Engineering:**  
   - Creation of new features (ratios, averages, combined ESG indicators)  
   - Scaling and transformation  

5. **Model Building:**  
   - Train ML models (Logistic Regression, Random Forest, XGBoost, LightGBM)  
   - Classify companies into *Low*, *Medium*, *High* risk  

6. **Evaluation:**  
   - Accuracy, Precision, Recall, F1-score, ROC-AUC  
   - Confusion matrix and SHAP explainability  

7. **Prediction:**  
   - Predict financial risk level for new companies based on ESG and financial metrics  

---

## 🧠 Example Features
| ESG Metrics | Financial Metrics |
|--------------|-------------------|
| Total ESG Score | Market Cap |
| Environmental Score | Price/Earnings |
| Social Score | Price/Book |
| Governance Score | Dividend Yield |
|                | 52 Week Low/High |
|                | EBITDA |

---

## 🧾 Output
- **Risk Category:** Low / Medium / High  
- **Feature Importance Visualization**  
- **Model Evaluation Reports**

---
📊 Model Evaluation Metrics

Accuracy Score

Precision, Recall, F1-score

ROC-AUC

Confusion Matrix

SHAP Feature Importance

📈 Future Enhancements

Automate data gathering using APIs

Integrate SQL/NoSQL database for live data ingestion

Develop an interactive dashboard (Power BI / Streamlit)

Deploy the model as a web service using FastAPI / Flask

👨‍💻 Author

Apurv Panbude
📧 Email: apurvpanbude1@gmail.com

📍 Location: Essen, Germany
📚 MSc in Big Data and Business Analytics (expected April 2026)

