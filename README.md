# ❤️ Heart Disease Prediction using Machine Learning

A Machine Learning application that predicts the likelihood of heart disease based on patient clinical parameters. The project leverages data preprocessing, feature engineering, and a K-Nearest Neighbors (KNN) classifier to provide real-time predictions through an interactive Streamlit web application.

---

## 🚀 Features

- Predicts heart disease risk from patient health parameters.
- Data preprocessing and feature engineering.
- One-hot encoding for categorical features.
- Feature scaling using StandardScaler.
- K-Nearest Neighbors (KNN) classification model.
- Interactive Streamlit web interface.
- Real-time prediction with an intuitive user experience.

---

## 🧠 Machine Learning Pipeline

1. Data Collection
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. One-Hot Encoding
6. Feature Scaling (StandardScaler)
7. Model Training using K-Nearest Neighbors (KNN)
8. Model Evaluation
9. Model Serialization using Joblib
10. Streamlit Deployment

---

## 📊 Dataset Features

The model uses the following patient attributes:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak (ST Depression)
- ST Slope

---

## 🛠 Tech Stack

### Programming Language
- Python

### Machine Learning
- Scikit-learn
- K-Nearest Neighbors (KNN)

### Data Processing
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn

### Model Persistence
- Joblib

---

## 📂 Project Structure

```
Heart-Disease-Prediction/
│
├── app.py                  # Streamlit application
├── KNN_heart.pkl           # Trained KNN model
├── scaler.pkl              # StandardScaler
├── columns.pkl             # Feature columns
├── Untitled.ipynb          # Model training notebook
├── heart.csv               # Dataset
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/mishraakshat135/Heart-Disease-predictor
```

---

## 📈 Model Workflow

```
Patient Information
        │
        ▼
Data Preprocessing
        │
        ▼
One-Hot Encoding
        │
        ▼
Feature Scaling
        │
        ▼
KNN Classifier
        │
        ▼
Heart Disease Prediction
```

---

## 🎯 Future Improvements

- Compare multiple Machine Learning models (Random Forest, XGBoost, SVM, Logistic Regression).
- Hyperparameter tuning using GridSearchCV.
- Model confidence visualization.
- REST API using FastAPI.
- React frontend for production deployment.

---

## 👨‍💻 Author

**Akshat Mishra**

B.Tech in Data Science & Artificial Intelligence  
Thapar Institute of Engineering & Technology

---

⭐ If you found this project useful, consider giving it a star!