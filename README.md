# Healthcare Predictive Analytics: Hospital Readmission Prediction

A beginner-friendly machine learning project that uses historical patient clinical and demographic data to predict whether a patient will be readmitted to the hospital within 30 days of discharge.

## 📌 Project Overview
Hospital readmission rates are a critical metric for evaluating healthcare quality and operational efficiency. This project implements a classification model to identify high-risk patients, helping healthcare providers allocate preventative care resources more effectively.

## 🗂️ Dataset Description
The dataset (`healthcare_readmission_dataset.csv`) contains simulated patient records with the following features:
* **Patient_ID:** Unique identifier for each patient.
* **Age:** Patient age in years.
* **Gender:** Patient gender (Male/Female).
* **Length_of_Stay:** Number of days spent in the hospital during the initial admission.
* **Num_Lab_Procedures:** Total number of laboratory tests performed.
* **Num_Medications:** Number of distinct medications administered.
* **Prior_Inpatient_Visits:** Number of inpatient hospitalizations in the past year.
* **Had_Emergency_Visit:** Binary indicator (`0` = No, `1` = Yes) for prior emergency room visits.
* **Chronic_Conditions_Count:** Number of chronic comorbidities diagnosed.
* **Readmitted_30Days (Target):** Whether the patient was readmitted within 30 days (`0` = No, `1` = Yes).

## 🚀 Technologies Used
* **Python**
* **Pandas & NumPy** (Data manipulation and preprocessing)
* **Scikit-Learn** (Machine Learning model training and evaluation)

## 📈 Model Performance & Metrics
The predictive model is evaluated using standard classification metrics:
* **Accuracy:** Overall correctness of predictions.
* **ROC-AUC Score:** Evaluates the model's ability to distinguish between readmitted and non-readmitted patients.
* **Classification Report (Precision, Recall, F1-Score):** Measures performance specifically on catching high-risk readmissions.
