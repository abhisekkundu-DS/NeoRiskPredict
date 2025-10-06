# 🧠 NeoRiskPredict – Newborn Risk Level Prediction

**Author:** [Abhisek Kundu](https://github.com/abhisekkundu-DS)  
**Repository:** `abhisekkundu-DS`

---

## 📘 Overview

**NeoRiskPredict** is an AI-based system designed to predict the **health risk level of newborn babies** during their initial hours of life.  
The goal is to assist healthcare professionals by providing **early warnings** about potential neonatal complications, enabling timely interventions and improving survival rates.

This project uses **deep learning models (LSTM and MLP)** trained on perinatal, maternal, and neonatal data to estimate the likelihood of health risks such as respiratory distress, infections, and other complications.

---

## 🚀 Features

- 🩺 **AI-driven prediction:** Detects newborns at high risk of complications.  
- 🧬 **LSTM & MLP models:** Combines temporal and static health features.  
- 🔍 **Explainable results:** Uses feature importance and SHAP visualizations.  
- ⚙️ **Flexible deployment:** Can be integrated into hospital monitoring systems or dashboards.  
- 📊 **Evaluation metrics:** AUC, accuracy, sensitivity, specificity, and calibration plots.

---


---

## 🧠 Model Details

### 1. **LSTM Model**
- Captures **temporal patterns** in neonatal vital signs and perinatal sequences.
- Built using **TensorFlow/Keras**.
- Ideal for time-series neonatal monitoring data.

### 2. **MLP Model**
- Uses **structured tabular features** like maternal history, delivery data, and birth metrics.
- Provides a fast, interpretable risk estimation.

---

## 🧪 Workflow

1. **Data Preprocessing**
   - Handle missing values, normalize features, encode categorical data.
2. **Model Training**
   - Train LSTM and MLP models separately.
   - Save best models as `.h5` files.
3. **Model Evaluation**
   - Evaluate using AUC, accuracy, F1-score, and confusion matrix.
4. **Prediction**
   - Predict newborn risk level: `Low`, `Moderate`, or `High`.
5. **Visualization**
   - Plot training curves and feature importance graphs.

---

## ⚙️ Technologies Used

| Category | Tools / Libraries |
|-----------|-------------------|
| Programming | Python 3.x |
| ML Frameworks | TensorFlow / Keras, Scikit-learn |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook |

---

## 💡 Future Improvements

- Integrate real-time monitoring data (vitals, oxygen saturation, etc.)
- Add a **web dashboard** using FastAPI + Streamlit for visualization.
- Apply **federated learning** for multi-hospital training.
- Perform **clinical validation** and deploy as an assistive tool in neonatal units.

---

## 🧬 Ethical & Privacy Considerations

- All data used must be **de-identified** to ensure patient privacy.  
- Models should support **explainability** and **human-in-the-loop** decision-making.  
- Intended only for **research and educational** purposes, not direct clinical use.

---

## 🏁 Getting Started

### 🔧 Prerequisites
Install dependencies:
```bash
pip install tensorflow scikit-learn pandas numpy matplotlib seaborn 

