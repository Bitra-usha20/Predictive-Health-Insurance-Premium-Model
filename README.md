# Predictive-Health-Insurance-Premium-Model# 

## 📌 Project Overview

This project predicts **health insurance premium costs** based on user details such as age, income, health risk factors, and lifestyle habits.
The system uses **Machine Learning models** and a **Streamlit web application** to provide real-time premium predictions.

The application allows users to input personal and health-related information and instantly receive a predicted insurance premium.

---

## 🚀 Features

* Interactive **Streamlit web interface**
* Predicts insurance premium based on multiple factors
* Uses **trained machine learning models**
* Separate models for **young individuals (<25)** and **others**
* Data preprocessing and scaling implemented
* Clean and structured ML project architecture

---

## 🧠 Machine Learning Workflow

1. Data preprocessing
2. Feature encoding (Label Encoding & One-Hot Encoding)
3. Feature scaling using trained scalers
4. Model training
5. Model serialization using **joblib**
6. Web deployment using **Streamlit**

---

## 📂 Project Structure

```
ML_Project
│
├── artifacts
│   ├── model_young.joblib
│   ├── model_rest.joblib
│   ├── scaler_young.joblib
│   └── scaler_rest.joblib
│
├── app.py
├── prediction_helper.py
│
├── premium_rest.ipynb
├── requirements.txt
└── README.md
```

---

## 📊 Input Features

The model predicts insurance premium based on the following features:

| Feature              | Description                |
| -------------------- | -------------------------- |
| Age                  | Age of the person          |
| Gender               | Male / Female              |
| Region               | Residential region         |
| Number of Dependants | Family dependents          |
| Income (Lakhs)       | Annual income              |
| BMI Category         | Weight classification      |
| Smoking Status       | Smoking habit              |
| Medical History      | Past health issues         |
| Employment Status    | Job category               |
| Insurance Plan       | Selected insurance plan    |
| Genetical Risk       | Genetic health risk factor |

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/insurance-premium-predictor.git
cd insurance-premium-predictor
```

Install required libraries:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

Run the Streamlit app:

```bash
streamlit run app.py
```

The application will open in your browser.

---

## 🖥 Example Interface

Users can enter details such as age, income, smoking status, and medical history to get the predicted insurance premium.

---

## 🛠 Technologies Used

* Python
* Pandas
* Scikit-Learn
* Joblib
* Streamlit

---

## 📈 Model Artifacts

Trained models and scalers are stored inside the **artifacts** folder:

* `model_young.joblib`
* `model_rest.joblib`
* `scaler_young.joblib`
* `scaler_rest.joblib`

These files are used during prediction for preprocessing and inference.


