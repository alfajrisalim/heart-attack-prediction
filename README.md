# ❤️ Heart Attack Prediction using Machine Learning (SVM)

This project aims to build a machine learning model to **predict the risk of heart attack** based on medical features such as cholesterol level, maximum heart rate, age, chest pain type, and more.

Dataset used in this project: **Heart Disease UCI**  
(Source: Kaggle / UCI Machine Learning Repository)

---

## 📌 Project Goals
- Menganalisis fitur–fitur kesehatan yang berpengaruh pada risiko serangan jantung.
- Membangun model Machine Learning menggunakan **Support Vector Machine (SVM)**.
- Melakukan tuning hyperparameter menggunakan **GridSearchCV**.
- Mengevaluasi performa model menggunakan **Accuracy, Confusion Matrix, dan ROC–AUC Curve**.

---

## 🧠 Machine Learning Workflow

| Step | Description |
|------|-------------|
| 1. Load dataset | Import dataset dan melihat struktur data |
| 2. Exploratory Data Analysis | Heatmap correlation dan distribusi fitur |
| 3. Data preprocessing | Scaling, train-test split |
| 4. Model training | SVM classifier |
| 5. Hyperparameter tuning | Grid Search (C, gamma, kernel) |
| 6. Evaluation | Accuracy, confusion matrix, ROC–AUC |

---

## 📊 Key Findings

- Dataset sedikit **imbalanced** → Target label:
  - 1 (Heart Attack): 165 data
  - 0 (Healthy): 138 data

➡️ Masih dianggap **seimbang**, sehingga **SMOTE tidak wajib**.

- Parameter terbaik hasil tuning:
Best Parameters: {'C': 1, 'gamma': 'scale', 'kernel': 'rbf'}
Best Score (cross-validation): 0.8224

## 🛠️ Tech Stack

| Component | Tools |
|----------|-------|
| Language | Python 3.9+ |
| Machine Learning | scikit-learn |
| Visualization | Matplotlib, Seaborn |
| Notebook | Jupyter Notebook |

---

## 📦 Installation & Running

### Clone repository
```bash
git clone https://github.com/alfajrisalim/heart-attack-prediction.git
cd heart-attack-prediction
