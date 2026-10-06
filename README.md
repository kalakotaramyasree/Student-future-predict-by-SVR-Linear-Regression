# 🎓 Student Future Prediction using SVR & Linear Regression

## 📌 Project Overview

**Student Future Prediction using SVR & Linear Regression** is a Machine Learning project designed to predict a student's future academic performance based on relevant historical and academic factors.

The project implements and compares two supervised learning algorithms:

* **Linear Regression**
* **Support Vector Regression (SVR)**

The goal is to understand how different regression techniques perform when predicting continuous student-related outcomes.

---

## 🎯 Objectives

* Analyze student academic data and identify important factors.
* Preprocess and prepare the dataset for Machine Learning.
* Build a **Linear Regression** model.
* Build a **Support Vector Regression (SVR)** model.
* Compare the performance of both models.
* Predict future student performance based on input features.
* Evaluate the models using suitable regression metrics.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Scikit-learn**
* **Jupyter Notebook**

---

## 🤖 Machine Learning Algorithms

### 1. Linear Regression

Linear Regression is used to model the relationship between the input features and the target variable.

It provides a simple and interpretable baseline for predicting student outcomes.

### 2. Support Vector Regression (SVR)

SVR is a Support Vector Machine algorithm adapted for regression problems. It can capture more complex relationships between input features and the target variable.

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Collection
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Selection
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
 ┌─────────────────────┐
 │                     │
Linear Regression     SVR
 │                     │
 └──────────┬──────────┘
            ↓
     Model Evaluation
            ↓
    Performance Comparison
            ↓
    Future Prediction
```

---

## 📊 Model Evaluation

The models can be evaluated using regression metrics such as:

* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score**

These metrics help determine how accurately each model predicts the student's future performance.

---

## 📁 Project Structure

```text
Student-Future-Prediction/
│
├── dataset/
│   └── student_data.csv
│
├── Student_Future_Prediction.ipynb
│
├── README.md
│
└── requirements.txt
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Student-Future-Prediction.git
```

### 2. Navigate to the Project Folder

```bash
cd Student-Future-Prediction
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Student_Future_Prediction.ipynb
```

and run the cells sequentially.

---

## 📈 Results

The performance of **Linear Regression** and **SVR** is compared using regression evaluation metrics.

The model with better evaluation performance can be selected for predicting future student outcomes.

> **Note:** Actual results depend on the dataset, selected features, preprocessing techniques, and model parameters.

---

## 🔮 Future Enhancements

* Add more student-related features.
* Perform hyperparameter tuning for SVR.
* Co
