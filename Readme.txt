IEEE-CIS Fraud Detection using XGBoost & Explainable AI - Stevens Institute of Technology

Overview
This project focuses on detecting fraudulent transactions using advanced machine learning techniques. The solution leverages XGBoost with HyperOpt-based tuning to optimize fraud risk assessment. Additionally, Explainable AI (XAI) techniques, including SHAP and LIME, have been integrated to provide interpretability for financial risk teams.

Key features of this project include:
✅ Feature Engineering – PCA-transformed behavioral patterns, device fingerprinting, transaction velocity, and card-link analysis.
✅ Fraud Detection Model – XGBoost with hyperparameter tuning achieving ROC AUC of 0.902.
✅ Explainable AI (XAI) – SHAP and LIME integration for model transparency.
✅ AI-powered Fraud Explanation System – Gemini AI for generating natural language explanations of fraud predictions.
✅ Automated Pipeline – SQL-driven data preprocessing, model training, evaluation, and real-time fraud scoring.

Project Structure
📂 notebooks/ – Contains Jupyter notebooks with code for data preprocessing, feature engineering, model training, and explainability.
📂 data/ – Processed datasets used for training and validation.
📂 models/ – Serialized trained models for fraud prediction.
📂 api/ – Backend scripts for integrating real-time fraud prediction and explanations.
📂 visualizations/ – SHAP and LIME plots for fraud interpretation.
📄 README.md – Project documentation (this file).