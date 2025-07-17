# 📱 Phone Purchase Prediction ML Project

A professional machine learning classification project that predicts whether a person is likely to purchase a new phone based on their demographic and financial attributes.

---

## 🔍 Project Overview

This project uses a synthetic dataset to train and evaluate various classification models to predict phone purchasing behavior (Yes/No). The best-performing model is selected based on accuracy and other performance metrics.

---

## 📂 Dataset Details

| Feature            | Description                                             |
|------------------- |---------------------------------------------------------|
| Age                |  Age of the person                                      |
| Salary             |  Monthly salary in INR (₹)                              |
| time_on_website    |  Time spent browsing smartphone-related content (min)   |
| previous_purchases | 	No. of past purchases (phones)                         |
| marketing_engaged  | 	Whether the user engaged with ads (1 = yes, 0 = no)    |
| search_frequency   |  How often the user searched phone terms                |
| device_age         |  Age of current device (years)                          |
| will_purchase      | 	Target variable (1 = yes, 0 = no)                      | 

---

## ⚙️ Tech Stack

- 🐍 Python (Pandas, NumPy, Scikit-learn)
- 📊 Matplotlib & Seaborn (for data visualization)
- 🧠 Machine Learning (Classification models)
- 📘 Jupyter Notebook / Google Colab
- 📝 PDF Report for Documentation

---

## 📈 ML Workflow

1. 🔍 Data Exploration
2. 🧼 Data Preprocessing (encoding, scaling)
3. 🧠 Model Training (Logistic, KNN, RandomForest, etc.)
4. ✅ Evaluation (Accuracy, Confusion Matrix)
5. 📊 Results Visualization
6. 💾 Model Saving (optional)

---

## 📊 Results

| Model               | Accuracy Score |
|--------------------|----------------|
| Logistic Regression | ✅ 80.00%       |
| Random Forest       | 77.50%         |
| Support Vector Machine (SVM) | 77.50%  |

📌 Final selected model: **Logistic Regression** (Best Score: 78.50%)


---

## 📎 Files in This Repo

- `Phone Purchase Prediction.pdf` – Full project explanation
- `smartphone_purchase_data.csv` – Cleaned dataset used for training
- `Notebook.ipynb` – Google Colab-compatible notebook
- `README.md` – This file

---

🙋‍♂️ Author
Mandar Kajbaje
