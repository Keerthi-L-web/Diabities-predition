# 🩺 Diabetes Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

A Machine Learning project that predicts whether a person is diabetic based on several medical parameters. The project demonstrates a complete ML workflow including data preprocessing, exploratory analysis, model training, evaluation, and prediction.

---

## 📌 Project Overview

Diabetes is one of the most common chronic diseases worldwide. Early prediction can help in timely diagnosis and treatment.

This project uses supervised machine learning techniques to classify whether a patient is diabetic based on medical features such as glucose level, BMI, insulin, age, and more.

---

## 🚀 Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature selection
- Train/Test data splitting
- Machine Learning model training
- Model evaluation
- Predict diabetes for new patient data

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Structure

```
Diabetes-Prediction/
│
├── Diabetes_prediction.ipynb
├── diabetes.csv
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

This project uses the **Pima Indians Diabetes Database**, one of the most widely used datasets for diabetes prediction.

### Dataset Link

https://www.kaggle.com/datasets/mathchi/diabetes-data-set

The dataset contains **768 patient records** with the following attributes:

| Feature | Description |
|----------|-------------|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Triceps skin fold thickness |
| Insulin | 2-Hour serum insulin |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Age in years |
| Outcome | 0 = Non-Diabetic, 1 = Diabetic |

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/Keerthi-L-web/Diabetes-Prediction.git
```

Move to project directory

```bash
cd Diabetes-Prediction
```

Install required libraries

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Diabetes_prediction.ipynb
```

Run all cells.

---

## 🔄 Machine Learning Workflow

1. Import Dataset
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Selection
5. Split Dataset
6. Train Machine Learning Model
7. Evaluate Performance
8. Predict Diabetes

---

## 📈 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 📋 Sample Prediction

### Input

```
Pregnancies: 5
Glucose: 166
BloodPressure: 72
SkinThickness: 19
Insulin: 175
BMI: 25.8
DiabetesPedigreeFunction: 0.587
Age: 51
```

### Output

```
Diabetic
```

---

## 💡 Future Improvements

- Hyperparameter tuning
- Feature engineering
- Cross-validation
- Deploy using Streamlit
- Build REST API using Flask/FastAPI
- Dockerize the application
- Deploy on Render or Hugging Face Spaces



---
