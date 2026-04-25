# 🧪 SentnelOps Internship Assignment  
## 🔍 AI/ML Reasoning + Anomaly Detection System

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python" alt="Python 3.10" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Isolation%20Forest-green" alt="Isolation Forest" />
  <img src="https://img.shields.io/badge/Notebook-Colab-orange?logo=googlecolab" alt="Google Colab" />
  <img src="https://img.shields.io/badge/Status-Completed-success" alt="Completed" />
</p>

---

## 🚀 Try it Live
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/19QoFvNKoUP8Bs96Vp-RL7DNIvZhYi7ud?usp=sharing)

---

## 🚀 Project Overview

This project implements a **hybrid anomaly detection system** for infrastructure monitoring using:

- **Rule-Based Logic** → deterministic and explainable decisions
- **Machine Learning (Isolation Forest)** → data-driven anomaly validation

The system analyzes infrastructure metrics, identifies anomalies, explains the reasoning, suggests corrective actions, and assigns a confidence score.

---

## 🎯 Key Features

- Detects:
  - Over-provisioned resources
  - Under-provisioned resources
  - Network-heavy anomalies
  - Normal resources

- Provides:
  - Clear reasoning
  - Actionable recommendations
  - Confidence scoring
  - Security risk detection

- Enhancements:
  - ML-based validation layer
  - Data visualization for insights

---

## 🧠 System Architecture

Input Metrics  
   ↓  
Rule-Based Detection  
   ↓  
Isolation Forest Model  
   ↓  
Decision Layer  
   ↓  
Confidence Adjustment  
   ↓  
Final Output + Reasoning

---

## ⚙️ Approach

### 🔹 Rule-Based Layer (Primary)
- Uses CPU, memory, and network thresholds
- Ensures interpretability and clear reasoning

### 🔹 Machine Learning Layer (Secondary)
- Isolation Forest detects statistical outliers
- Provides validation, not replacement

### 🔹 Hybrid Decision Strategy

| Scenario | Action |
|---------|--------|
| Rule + ML agree | Increase confidence |
| ML detects anomaly only | Mark as suspicious |
| Rule detects anomaly only | Reduce confidence |

---

## ------OUTPUT------
<img width="1049" height="318" alt="Screenshot 2026-04-25 162408" src="https://github.com/user-attachments/assets/36909be7-a4d1-4f42-9463-6ee1771c32ba" />

---

## 📊 Visual Insights

Replace the placeholder images below with screenshots from your notebook if needed.

### Anomaly Distribution
<img width="547" height="569" alt="1" src="https://github.com/user-attachments/assets/7ad34399-3f58-4675-ac01-2719b3396a1a" />


### Resource Utilization
<img width="543" height="435" alt="2" src="https://github.com/user-attachments/assets/010a5ab3-e07a-41a8-a973-a1194fe443bf" />


### Rule vs ML Agreement
<img width="547" height="476" alt="3" src="https://github.com/user-attachments/assets/8c315a06-2b79-4c11-9bde-c8cf0100a905" />


---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (Isolation Forest)
- Google Colab

---

## 📂 Project Structure

sentnelops-anomaly-detection/  
├── SentnelOps_Anomaly_Detection.ipynb  
├── README.md

---

## 🚀 How to Run

1. Open the notebook in **Google Colab**
2. Run all cells in order
3. View:
   - JSON output
   - DataFrame
   - Visualizations

---

## 🧠 Why This Approach

- **Explainable** → rule-based reasoning
- **Reliable** → no external API dependency
- **Practical** → real-world infrastructure logic
- **Balanced** → combines logic + ML validation

---

## ⚠️ Limitations

- Static thresholds may not generalize
- No historical or time-series data
- Limited dataset for ML

---

## 🔮 Future Improvements

- Time-series anomaly detection
- Dynamic thresholding
- Advanced ML models
- Real-time monitoring dashboard

---

## 📌 Conclusion

This project demonstrates a balanced and practical approach to anomaly detection by combining deterministic logic with machine learning validation, ensuring both interpretability and effectiveness.

---

## 👤 Author

**Yash Singh Chauhan**  
B.Tech CSE | Full Stack & AI Systems

---

⭐ If you found this useful, feel free to explore and improve!
