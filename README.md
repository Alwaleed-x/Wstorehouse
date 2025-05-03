# 📦 WstoreHouse

A machine learning project that compares multiple classification models using GPU-accelerated libraries to enhance performance on large datasets.

---

## 🧠 Project Objective
This project aims to:
- Train and evaluate multiple machine learning models (Naive Bayes, Logistic Regression, Random Forest, and XGBoost).
- Compare accuracy, training time, and memory usage.
- Leverage **GPU acceleration** using `cuML` for faster processing.

---

## 🛠️ Technologies & Tools
- Python (Jupyter Notebook)
- cuML (RAPIDS)
- Scikit-learn
- XGBoost
- Pandas, NumPy
- CSV data handling

---

## 📁 Files
- `Alwaleed (1).ipynb`: Main training notebook
- `X_test.csv`, `scalar.csv`: Transformed datasets
- `prediction.csv`: Model predictions
- `model.joblib.csv`: Saved model

---

## 🧪 Models Used
1. **Naive Bayes (MultinomialNB)**  
2. **Logistic Regression**  
3. **Random Forest Classifier**  
4. **XGBoost Classifier**

Each model is evaluated based on:
- **Training time**
- **Accuracy**
- **GPU memory usage**

---

## 📊 Results Snapshot
- XGBoost and Random Forest achieved the best accuracy.
- cuML significantly reduced training time compared to CPU-based models.

---

## 📌 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/Alwaleed-x/Wstorehouse.git
