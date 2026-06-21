📞 Telco Customer Churn Prediction Dashboard

A Machine Learning-powered web application built using Streamlit that predicts customer churn for a telecommunications company and provides interactive data visualizations for business insights.

🚀 Features
🔮 Customer Churn Prediction
Predict whether a customer is likely to churn.
Interactive form-based input system.
Real-time prediction using a trained Machine Learning model.
📊 Dataset Explorer
Upload Telco Customer Churn dataset.
View dataset records.
Display statistical summaries.
Explore data structure interactively.
📈 Insights Dashboard
Monthly Charges Distribution.
Gender Breakdown Analysis.
Churn Analysis by Contract Type.
Interactive visualizations using Plotly.
🛠️ Technologies Used
Python
Streamlit
Scikit-Learn
Pandas
NumPy
Plotly
Pickle
📂 Project Structure
ML_Project/
│
├── app.py
├── model.pkl
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── Telco_Customer_Churn_ml.ipynb
├── package.json
├── package-lock.json
└── README.md
📋 Dataset

Dataset: Telco Customer Churn Dataset

The dataset contains customer information such as:

Gender
Partner Status
Dependents
Phone Service
Internet Service
Contract Type
Payment Method
Monthly Charges
Total Charges
Churn Status
⚙️ Installation
Clone Repository
git clone <repository-url>
cd ML_Project
Install Dependencies
pip install streamlit pandas numpy scikit-learn plotly
▶️ Run the Application
streamlit run app.py

After running, open:

http://localhost:8501
🧠 Machine Learning Model

The churn prediction model was trained using the Telco Customer Churn dataset.

Workflow:

Data Preprocessing
Feature Encoding
Model Training
Model Serialization using Pickle
Deployment with Streamlit

The trained model is stored as:

model.pkl
📸 Dashboard Modules
🔮 Predict Churn

Enter customer details and predict churn probability instantly.

📊 Dataset Explorer

Upload and inspect customer datasets.

📈 Insights Dashboard

Generate visual reports and customer behavior analytics.

🎯 Project Objectives
Predict customer churn accurately.
Help telecom companies identify at-risk customers.
Support customer retention strategies.
Provide business-friendly data visualization tools.
