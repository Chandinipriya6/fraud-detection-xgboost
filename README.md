# 🛡️ Online Fraud Detection using XGBoost

This project uses the XGBoost classifier to detect fraudulent financial transactions based on historical transaction data.

## 📂 Dataset
- Source: `onlinefraud.csv`
- Features: step, type, amount, origin/destination balances, isFraud, etc.

## ⚙️ Tools & Technologies
- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- Jupyter Notebook

## 📊 Model
- Model used: `XGBClassifier`
- Evaluation metric: `Log Loss`

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook fraud_detection.ipynb
