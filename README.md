# 🔍 Detecting Faults in District Heating Substations

This repository contains the implementation of three AI-based approaches for detecting faults in district heating substations, aiming to reduce high return temperatures. This work was developed as part of a 15-credit Data Science thesis project at **Halmstad University**.

---

## 📝 Abstract

This study developed AI methods to detect faults in district heating substations using data from over **4,000 buildings (2022–2025)**. Three approaches were implemented:

- **ARIMA with Statistical Process Control**
- **USAD - UnSupervised Anomaly Detection**
- **k-NN Algorithm**

The project demonstrates the **precision-recall tradeoff** in fault detection, with the **k-NN model** achieving the highest recall. However, additional filtering is needed to reduce false alarms for real-world deployment.

---

## 📂 Repository Structure

```
├── KNN v4.ipynb            # k-NN based anomaly detection
├── USAD v3.ipynb           # Unsupervised anomaly detection model
├── README.md               # Project overview
```
---

## 📊 Results

| Model         | Recall | Precision |
|---------------|--------|-----------|
| k-NN          | 77.4%  | 35.3%     |
| USAD          | 36.9%  | 36.8%     |
| ARIMA (0.5σ)  | 51.1%  | 16.9%     |

---

## 🏆 Key Contributions

- Implemented **three distinct AI approaches** for fault detection.
- Developed a **novel fault injection methodology** for training on unlabeled data.
- Achieved **77.4% recall** with the k-NN model.
- Proposed a **hybrid solution** combining k-NN with weather and ΔT filters.
- Estimated **potential cost savings**:  500K–1M SEK /year per 1°C reduction in return temperature.

---

## 🔗 ARIMA Implementation

The implementation for the **ARIMA with Statistical Process Control** approach can be found in a separate repository:

🔗 [ARIMA Implementation on GitHub](https://github.com/mohamadhamzza/Thesis_Project)

---

## 🤝 Contributors

- **Majd Alkhatab** – [@majdalkhatab](https://github.com/majdalkhatab)
- **Mohamad Hamza** – [@mohamadhamzza](https://github.com/mohamadhamzza)

**Supervisor:**  
Dr. Hadi Fanaee Tork, Halmstad University  
In collaboration with **Halmstad Energi och Miljö (HEM)**

---

> **Note**: Due to confidentiality agreements, real operational data from HEM cannot be shared publicly.
