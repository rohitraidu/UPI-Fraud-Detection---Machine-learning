# 💳 UPI Fraud Detection using Machine Learning

This project focuses on detecting fraudulent transactions in UPI (Unified Payments Interface) systems using machine learning models. The goal is to classify transactions as either genuine or fraudulent, even in the presence of significant class imbalance.

---

## 📁 Project Structure


---

## 🔍 Problem Statement

Detect fraudulent UPI transactions using supervised machine learning techniques. The main challenges involve:
- Imbalanced classes (very few fraudulent cases)
- Identifying relevant features
- Ensuring high recall to catch frauds without too many false alarms

---

## 🧠 Models Used

- ✅ Logistic Regression  
- ✅ Random Forest Classifier  
- 🔜 XGBoost / LightGBM (Next phase)

---

## 📊 Evaluation Metrics

- Precision  
- Recall (Focus due to class imbalance)  
- F1-Score  
- Confusion Matrix  

### 📌 Current Results:

| Model              | Accuracy | Recall (Fraud) | F1-Score (Fraud) |
|-------------------|----------|----------------|------------------|
| Logistic Regression | 0.95     | 0.77           | 0.87             |
| Random Forest       | 0.93     | 0.90           | 0.86             |

---

## 📈 Insights

- **Best Model:** Random Forest (better recall & F1-score)
- **Feature Importance:** Certain features like transaction type and amount had high influence.
- **Class Imbalance:** Strong focus on detecting rare fraud cases.

---

## 🧪 Next Steps

- ✅ Handle imbalance using **SMOTE** or **class weighting**
- 🚀 Train advanced models like **XGBoost** or **LightGBM**
- 🌐 Deploy model via **Flask API** for real-time fraud alerts
- 🔁 Monitor model performance and update with new data

---

## 💻 Tech Stack

- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Flask / FastAPI (for deployment)
- Git & GitHub

---

## 📬 Contact

**Rohit Sumalraidu**  
📧 rohitraidu00@gmail.com  
📍 Ambernath, Maharashtra  

---

## ⭐️ Star This Repo

If you find this helpful, please ⭐️ the repo and share with fellow learners!

