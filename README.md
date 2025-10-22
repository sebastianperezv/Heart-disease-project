# 🩺 Heart Disease Prediction Project

## Binary Classification Problem with Machine Learning

This project aims to develop and evaluate a **Machine Learning Binary Classification** model capable of predicting whether or not a patient has heart disease, based on a set of key clinical parameters.

The development followed a structured 6-step approach: Problem Definition, Data, Evaluation, Feature Analysis, Modeling, and Experimentation.

---

## 🎯 Goal and Evaluation (Objetivo y Evaluación)

### Problem Statement
Given clinical parameters about a patient, can we predict whether or not they have heart disease?

### Success Metric (Initial Goal)
The Proof of Concept's initial objective was to achieve an **Accuracy** of **95%**.

---

## 📊 Dataset (Conjunto de Datos)

The project utilizes a medical dataset that contains 14 clinical attributes and a binary target value.

* **Original Source (Cleveland Data):** UCI Machine Learning Repository.
    * [https://archive.ics.uci.edu/ml/datasets/heart+Disease](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
* **Version Used (Kaggle):** A balanced dataset for classification.
    * [https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset)

The dataset contains 303 rows and 15 columns, and is relatively balanced between the `yes` (with disease) and `no` (without disease) classes.

### Key Features
Attributes include variables such as:
* `age`
* `sex` (1=male, 0=female)
* `cp` (Chest pain type)
* `trestbps` (Resting blood pressure)
* `chol` (Serum cholesterol)
* `thalach` (Maximum heart rate achieved)
* `target` (Objective: 1=yes, 0=no)

---

## 🧠 Models and Results (Modelos y Resultados)

Different Scikit-learn classification algorithms were experimented with, including:

* **Logistic Regression** (`LogisticRegression`)
* **K-Nearest Neighbors** (`KNeighborsClassifier`)
* **Random Forest** (`RandomForestClassifier`)

### Final Result
Although the 95% accuracy goal was not met, the best performance was achieved with:

> **Model:** `LogisticRegression()`
> **Accuracy:** **86%**

---

## 🛠️ Technologies Used (Tecnologías Utilizadas)

* **Language:** Python
* **Data Analysis:** `Pandas`, `NumPy`, `Seaborn`
* **Modeling:** `Scikit-learn`
* **Visualization:** `Matplotlib`

---

## 📝 Next Steps (Pasos Siguientes)

If you wish to continue improving the model, suggested avenues for experimentation include:
* Collecting more data or cleaner data.
* Trying more advanced models (e.g., CatBoost or XGBoost).
* Deeper hyperparameter tuning of the current models.

Deeper hyperparameter tuning of the current models.
