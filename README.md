# ✈️ Forecasting Flight Departure Delay
**Backpropagation Neural Network – Data Analysis Project**

## 📌 Overview
This project focuses on **forecasting flight departure delay levels** using a **Backpropagation Neural Network (BPNN)** based on historical domestic flight data at **Ahmad Yani International Airport, Semarang**, covering the period **2020–2024**.  
The analysis aims to identify delay patterns and support better operational decision-making at the airport.

---

## 🎯 Research Objectives
- Analyze historical flight delay data using time series analysis
- Identify airlines with the highest delay frequency
- Build and evaluate a Backpropagation Neural Network model
- Predict future flight departure delay levels

---

## 📊 Dataset
- **Source:** Airport Operation Database System (AODS)  
- **Period:** 2020 – 2024  
- **Records:** ±29,900 flight records  
- **Type:** Domestic departure flights  
- **Focus Airlines:** Batik Air & Citilink (highest delay frequency)

### Main Features Used
- Scheduled Time (SCH)
- Actual Departure Time (ACT)
- Calculated Delay (minutes)

---

## 🔄 Data Preprocessing
- Removal of irrelevant attributes
- Airline code filtering
- Feature engineering to calculate delay duration
- Aggregation of daily delay values
- Data normalization (Min-Max Scaling)

---

## 🧠 Modeling Method
- **Algorithm:** Backpropagation Neural Network (BPNN)
- **Architecture:**
  - Input Layer: 1 neuron
  - Hidden Layers: 4 layers
  - Output Layer: 1 neuron
- **Training Parameters:**
  - Epochs: 500 & 1000
  - Learning Rate: 0.01
- **Type:** Supervised Learning (Time Series Forecasting)

---

## 📈 Model Evaluation
The model performance is evaluated using:
- **Mean Squared Error (MSE)**
- **R-squared (R²)**

Results show that the BPNN model achieves **low MSE and high R² values**, indicating good predictive performance and the ability to capture delay patterns effectively.

---

## 🛠️ Tools
<p align="left">
  <img src="https://img.shields.io/badge/Python-0d0d0d?style=for-the-badge&logo=python&logoColor=FFD43B"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-0d0d0d?style=for-the-badge&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-4C8CBF?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black"/>
</p>

