# Machine Learning–Based Multiclass Classification Model for Effective Air Quality Prediction

## 📌 Overview
Air pollution is one of the most serious global health challenges today. According to the **World Health Organization (WHO)**, **9 out of 10 people worldwide breathe unhealthy air**, contributing to **over 7 million deaths annually**.

In India, air quality levels are often **far below WHO-recommended standards**, with a significant rise in pollutants such as **ozone**, which has increased by approximately **17% over the last decade**.

This project focuses on building a **machine learning–based multiclass classification system** to predict **Air Quality Index (AQI) categories** using real-world air pollution data collected from government sources.

---

## 🎯 Objective
The main objectives of this project are:
- To predict **Air Quality Index (AQI) categories** using machine learning
- To compare multiple ML algorithms for multiclass classification
- To identify the **most effective model** for AQI prediction based on multiple performance metrics
- To support **environmental monitoring and public health awareness**

---

## 📊 Dataset Description
- **Data Source**:  
  - Central Pollution Control Board (CPCB), Ministry of Environment, Forest and Climate Change  
  - MPPCB (Indore)  
  - DPCC (Anand Vihar, Delhi)
- **Time Period**: 2020 – 2022
- **Data Type**: Real-world air quality monitoring data
- **Pollutants Considered** (example):  
  PM2.5, PM10, NO₂, SO₂, CO, O₃ (depending on availability)

---

## 🛠 Methodology

### 1. Data Preprocessing
- Handling missing and inconsistent values
- Data normalization and scaling
- Label encoding for AQI categories
- Train–test split for model evaluation

### 2. Machine Learning Models Used
The following multiclass classification models were implemented and compared:

- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Tree
- Random Forest

---

## 🧠 Performance Evaluation Metrics
To ensure a fair and detailed comparison, models were evaluated using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **AUC–ROC**
- **Cohen’s Kappa Score**
- **Matthews Correlation Coefficient (MCC)**

---

## 📈 Results & Key Findings
- All models were tested under the same experimental conditions
- **Random Forest consistently outperformed other models**
- It achieved higher scores across most evaluation metrics
- Random Forest demonstrated:
  - Better handling of nonlinear relationships
  - Robust performance on multiclass AQI data
  - Higher reliability for real-world AQI prediction

---

## ✅ Conclusion
This study demonstrates that **machine learning models can effectively predict AQI categories** using historical air quality data.  
Among all evaluated models, **Random Forest** proved to be the most suitable for multiclass AQI prediction due to its superior performance and robustness.

The proposed approach can assist:
- Environmental agencies
- Smart city systems
- Health advisory platforms
in making **data-driven decisions** related to air pollution and public health.

---

## 🔮 Future Work
- Include additional cities and monitoring stations
- Integrate meteorological parameters (temperature, humidity, wind speed)
- Apply deep learning models for AQI prediction
- Develop a real-time AQI prediction dashboard
- Extend the model for long-term air quality forecasting

---

## 🧪 Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

---

## 📂 Project Structure

├── data/ # Raw and processed AQI datasets

├── preprocessing/ # Data cleaning and preparation scripts

├── models/ # ML model implementations

├── evaluation/ # Performance metrics and comparison

├── results/ # Plots and evaluation outputs

├── README.md

└── requirements.txt

---

## 🏷 Keywords
Air Quality Index, AQI Prediction, Machine Learning,  
Multiclass Classification, Random Forest,  
Environmental Monitoring, Public Health

---

## 👩‍💻 Author
**Shilpi Rani**

---

## 📜 License
This project is intended for academic and research purposes.
