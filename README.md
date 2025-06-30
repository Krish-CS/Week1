# Water Quality Prediction – Week 1

This project aims to predict multiple water quality parameters using machine learning techniques, specifically a `MultiOutputRegressor` wrapped around a `RandomForestRegressor`. It was developed as part of a one-month **AICTE Virtual Internship** sponsored by **Shell** in **June 2025**.

---

## 📌 Overview

Access to clean water is a critical environmental and public health concern. Predicting multiple pollutants simultaneously can help early identification of harmful water conditions and enable better policy and operational responses.

During **Week 1**, the primary focus was on:
- Loading and cleaning the dataset
- Extracting relevant time-based features
- Building a base machine learning model
- Predicting future pollutant levels

---

## 🛠️ Technologies Used

- **Python 3.12**
- `Pandas`, `NumPy` – Data handling and preprocessing
- `Scikit-learn` – ML modeling and evaluation
- `Joblib` – Model persistence
- **Jupyter Notebook** – Development environment

---

## 🎯 Water Quality Parameters Predicted

The model predicts the following key pollutant indicators:
- O₂ (Oxygen)
- NO₃ (Nitrate)
- NO₂ (Nitrite)
- SO₄ (Sulphate)
- PO₄ (Phosphate)
- CL (Chloride)

---

## 📊 Model Evaluation Metrics

- **R² Score**
- **Mean Squared Error (MSE)**

Model performance is measured using standard regression metrics across all pollutants.

---

## 📁 Files Included

- `Water_Quality_Prediction.ipynb` – Main notebook
- `pollution_model.pkl` – Trained model
- `model_columns.pkl` – Column structure used for prediction
- `data/water_quality.csv` – Dataset used
- `README.md` – Project overview

---

## 🧪 Sample Prediction Output

The model takes a `station_id` and `year` as input and returns predicted pollutant values.

---

## 🧾 Internship Details

- **Internship Type:** AICTE Virtual Internship – Edunet Foundation
- **Sponsor:** Shell
- **Month:** June 2025
- **Focus Area:** Machine Learning for Environmental Monitoring



