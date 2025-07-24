# 💳 Credit Card Fraud Detection System

This project is a machine learning-based solution to detect fraudulent credit card transactions using real-world, imbalanced datasets. It applies preprocessing techniques, model training, evaluation, and visualization to identify suspicious activity with high accuracy and recall.

---

## 📊 Features

- Data preprocessing and feature engineering
- Handling class imbalance using SMOTE
- Model training: Logistic Regression, Random Forest, XGBoost
- Evaluation metrics: F1-score, ROC-AUC, MCC, Confusion Matrix
- Fraud detection optimization using threshold tuning
- Performance visualizations for better insights

---

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**: pandas, numpy, scikit-learn, imbalanced-learn, matplotlib, seaborn, xgboost  
- **Jupyter Notebook** for EDA and model building

---

## 🚀 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook
Open FraudDetection.ipynb in Jupyter Notebook or VS Code and execute all cells step by step.

📈 Results
Best Model: XGBoost

F1 Score: 0.93

Recall: 0.91

MCC: 0.89

📌 Dataset
The dataset used is the Kaggle Credit Card Fraud Detection Dataset.

🧠 Future Work
Deploy model as a REST API using Flask or FastAPI

Integrate with real-time transaction stream

Implement dashboard for live fraud alerts

📝 License
This project is licensed under the MIT License.
