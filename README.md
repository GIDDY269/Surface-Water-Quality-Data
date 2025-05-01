# 🌊 Surface Water Quality Data – Potomac River, West Virginia (USA)

This repository contains a time-series dataset of surface water quality measurements taken from the **Potomac River** in **West Virginia, USA**. The dataset is suitable for **time-series forecasting** and **anomaly detection** tasks related to environmental monitoring, water quality management, and early warning systems for pollution events.

---

## 📁 Dataset Overview

The dataset includes measurements recorded at **15-minute intervals**, featuring the following parameters:

| Column        | Description                                                                 |
|---------------|-----------------------------------------------------------------------------|
| `date_time`   | Timestamp of the reading (format: `YYYY-MM-DD HH:MM`)                       |
| `SC(uS)`      | Specific Conductance (in microsiemens per centimeter, µS/cm)                |
| `Turb(FNU)`   | Turbidity (in Formazin Nephelometric Units, FNU)                            |
| `DO(mg/L)`    | Dissolved Oxygen (in milligrams per liter, mg/L)                            |


---

## 📈 Applications

This dataset is ideal for the following applications:

- **⏱ Time-Series Forecasting**  
  Predict future values of water quality parameters like turbidity and specific conductance.

- **🚨 Anomaly Detection**  
  Identify unusual water quality patterns due to environmental changes, pollution, or equipment failures.

- **🌿 Environmental Monitoring**  
  Analyze trends and seasonal patterns in river water conditions.

- **📊 Exploratory Data Analysis (EDA)**  
  Understand river behavior over time through visualization and statistical summaries.

---


## 🧼 Notes on Data Quality

- The dataset includes occasional missing values (`NaN`) in the turbidity column (`Turb(FNU)`), which may need to be handled using interpolation or imputation.
- Dissolved Oxygen (`DO(mg/L)`) values appear constant across many timestamps, which may require normalization or filtering depending on your analysis goals.

---


