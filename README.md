# Predictive Maintenance System

A machine learning-based predictive maintenance system designed to identify potential machine failures before they occur. This project uses sensor and operational data to analyze equipment health, predict failures, and improve maintenance planning.

---

## Project Overview

Predictive maintenance helps industries reduce downtime, lower maintenance costs, and improve operational efficiency by predicting equipment failures in advance.

This project demonstrates an end-to-end machine learning workflow for predictive maintenance, including:

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature engineering
* Machine learning model development
* Model evaluation and performance comparison
* Predictive analytics for maintenance planning

---

## Dataset

The dataset contains machine operational and sensor-related information such as:

* Machine temperature
* Air temperature
* Rotational speed
* Torque
* Tool wear
* Machine type
* Failure status

### Target Variable

* `Failure`

  * `1` → Machine failure predicted
  * `0` → Machine operating normally

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Workflow

### 1. Data Loading

* Imported predictive maintenance dataset
* Inspected data structure and feature types

### 2. Data Preprocessing

* Removed unnecessary columns
* Checked for missing values
* Encoded categorical features
* Scaled numerical features where necessary

### 3. Exploratory Data Analysis (EDA)

Performed detailed analysis to identify machine behavior patterns:

* Failure distribution analysis
* Sensor value correlations
* Temperature analysis
* Rotational speed analysis
* Tool wear analysis
* Correlation heatmaps

### Key Insights

* High tool wear increases failure probability
* Abnormal temperature ranges indicate potential failures
* Torque and rotational speed patterns influence machine health
* Certain machine types exhibit higher failure risks

---

## Machine Learning Models

The following models were implemented for failure prediction:

### Logistic Regression

* Baseline classification model
* Simple and interpretable approach

### Decision Tree Classifier

* Tree-based prediction model
* Easy to visualize and interpret

### Random Forest Classifier

* Ensemble learning model
* Improved predictive performance and robustness

---

## Model Evaluation Metrics

Models were evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

---

## Results

The predictive maintenance system successfully identifies patterns associated with machine failures.

Key outcomes include:

* Improved failure prediction accuracy
* Better understanding of operational risk factors
* Early detection of maintenance requirements
* Reduced risk of unexpected machine breakdowns

Random Forest generally provided the best overall predictive performance among the tested models.

---

## Project Structure

```bash
Predictive-Maintenance-System/
│
├── Predictive_Maintenance_System.ipynb
├── README.md
└── dataset.csv
```

---


## Future Improvements

* Hyperparameter tuning
* Real-time monitoring dashboard
* IoT sensor integration
* Deep learning models for advanced prediction
* Deployment using Flask or Streamlit
* Automated maintenance alert system

---

## Conclusion

This project demonstrates how machine learning can be applied to predictive maintenance for industrial systems. By analyzing machine sensor data and operational patterns, the system can proactively predict failures and support smarter maintenance decisions.

---

## Author

Developed as a machine learning project for predictive maintenance and industrial analytics.
