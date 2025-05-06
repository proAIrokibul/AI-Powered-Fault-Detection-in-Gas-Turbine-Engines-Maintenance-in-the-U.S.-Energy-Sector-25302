# AI-Powered-Fault-Detection-in-Gas-Turbine-Engines-Maintenance-in-the-U.S.-Energy-Sector-25302
# 🚀 AI Powered Fault Detection in Gas Turbine Engines  
### Enhancing Predictive Maintenance in the U.S. Energy Sector

---

## 📊 Project Overview

This project focuses on building machine learning models to **detect faults in gas turbine engines**. By leveraging real-time sensor data and AI algorithms, we aim to enhance **predictive maintenance** strategies in the energy sector.  

The dataset includes operational parameters from gas turbines such as:
- Temperature
- RPM
- Torque
- Vibrations
- Power Output
- Fuel Flow Rate
- Air Pressure
- Exhaust Gas Temperature
- Oil Temperature

Our goal:  
✅ Accurately classify whether a **fault** is present (`1`) or not (`0`), enabling timely maintenance actions and avoiding catastrophic failures.

---

## 🔬 Dataset Description

| Column Name                  | Description                     |
| ---------------------------- | -------------------------------- |
| Temperature (°C)              | Engine internal temperature      |
| RPM                           | Revolutions per minute           |
| Torque (Nm)                   | Torque output                    |
| Vibrations (mm/s)             | Vibration level                  |
| Power Output (MW)             | Power generated                  |
| Fuel Flow Rate (kg/s)         | Fuel consumption rate            |
| Air Pressure (kPa)            | Air intake pressure              |
| Exhaust Gas Temperature (°C)  | Exhaust output temperature       |
| Oil Temperature (°C)          | Oil system temperature           |
| Fault                         | **Target variable (0 = No Fault, 1 = Fault)** |

---

## 🤖 Machine Learning Models Used

We implemented and compared three classification models:

1. **Logistic Regression**
2. **Random Forest Classifier**
3. **XGBoost Classifier**

Each model was evaluated using:
- **Accuracy Score**
- **Precision / Recall / F1-Score**

---

## 📈 Key Results

| Model               | Accuracy  | Precision (Class 1) | Recall (Class 1) | F1-Score (Class 1) |
| ------------------- | --------- | ------------------ | --------------- | ----------------- |
| Logistic Regression | 69.06%    | 0.00               | 0.00            | 0.00              |
| Random Forest       | 67.99%    | 0.17               | 0.01            | 0.02              |
| XGBoost             | 62.59%    | 0.30               | 0.16            | 0.21              |

⚠️ **Note:** Models show high accuracy on non-fault cases but lower recall on detecting actual faults. This suggests **class imbalance** and the need for **balancing techniques** (e.g., SMOTE, class weights) in future work.

---

## 🚀 Business Impact

The implementation of AI-powered fault detection in gas turbines delivers **significant business value**:

- 🔥 **Reduced Downtime**: Early fault detection prevents unplanned outages, saving millions in lost energy production.
- 🔧 **Optimized Maintenance**: Shifts from reactive to **predictive maintenance**, reducing maintenance costs and extending asset life.
- 🌱 **Energy Efficiency**: Ensures turbines run optimally, improving fuel efficiency and lowering emissions.
- 📉 **Risk Mitigation**: Prevents catastrophic failures that could result in safety hazards and financial penalties.
- 💰 **Cost Savings**: Helps U.S. energy companies save on repairs, fuel, and operational expenses.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas, NumPy** (Data processing)
- **Matplotlib, Seaborn** (Visualization)
- **Scikit-learn** (Machine learning models)
- **XGBoost** (Advanced gradient boosting)

---

## 💪 Future Work

- ✅ Apply **class balancing** (SMOTE / class weights) to improve fault detection recall.
- ✅ Hyperparameter tuning for better accuracy.
- ✅ Deployment as a real-time monitoring API.
- ✅ Integration with IoT systems in power plants.

---

