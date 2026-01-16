🛒 Online Shopper Revenue Prediction System

📌 Overview

The Online Shopper Revenue Prediction System is a machine learning–based web application designed to predict whether an online visitor is likely to generate revenue during a browsing session.
Built with Python, Scikit-learn, and Streamlit, this project converts raw e-commerce behavior data into meaningful business insights.

Using a trained Random Forest model, the system analyzes session-level features such as page visits, bounce rates, visitor type, and special days to deliver real-time revenue predictions through an interactive web interface.

🚀 Key Features

Predicts whether a visitor will generate revenue

Uses real-world e-commerce behavioral data

Trained with a Random Forest Classifier

Fast and interactive Streamlit web application

Proper feature scaling and categorical encoding

Pre-trained model and encoders for easy deployment

🧠 Machine Learning Workflow

Data cleaning and preprocessing

Feature scaling using StandardScaler

Encoding categorical variables (Month, VisitorType, Revenue)

Model training with Random Forest Classifier

Model evaluation and saving using Pickle

Real-time prediction via Streamlit UI

🛠️ Tech Stack

Language: Python

Web Framework: Streamlit

Machine Learning: Scikit-learn

Data Processing: Pandas, NumPy

Model Storage: Pickle

📂 Project Structure
├── app.py                # Streamlit application
├── model.ipynb           # Model training & evaluation
├── dataset.csv           # Dataset
├── rf_model.pkl          # Trained Random Forest model
├── scaler.pkl            # Feature scaler
├── le_month.pkl          # Label encoder (Month)
├── le_visitor.pkl        # Label encoder (Visitor Type)
├── le_revenue.pkl        # Label encoder (Revenue)
├── requirements.txt      # Project dependencies
└── README.md             # Documentation


📈 Output

✅ Will generate revenue

❌ Will NOT generate revenue

Predictions are displayed instantly based on user input.

🎯 Use Cases

E-commerce business analytics

Customer behavior prediction

Conversion rate optimization

Data science and ML portfolio project

🏆 Conclusion

This project showcases a complete end-to-end machine learning pipeline—from data preprocessing and model training to deployment using Streamlit.
It highlights practical skills in feature engineering, model building, and real-world ML deployment, making it a strong and professional addition to any data science portfolio.
