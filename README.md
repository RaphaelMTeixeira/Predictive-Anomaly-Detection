# 🛢️ Predictive Anomaly Detection in Oil & Gas Wells (Deep Learning)

## 📌 Overview
This project presents a **predictive exploratory analysis and anomaly detection model** for oil and gas extraction wells, using real-world and simulated data from Petrobras' **3W Dataset**.

The objective is to anticipate operational anomalies in deepwater extraction systems, enabling preventive actions that reduce operational costs and risks.

---

## 🎯 Business Problem
Oil and gas extraction in deepwater environments is:
- Highly complex
- Expensive to maintain
- Sensitive to operational failures

Unexpected anomalies can lead to:
- Production downtime
- Financial losses
- Environmental risks

This project aims to **predict anomalies before they occur**, allowing proactive intervention.

---

## 📊 Dataset
- **Source:** Petrobras 3W Dataset
- Contains:
  - Real and simulated well data
  - Multivariate time series from multiple sensors
  - Different anomaly classes (transient and steady-state)

---

## 🧠 Methodology

### 1. Exploratory Data Analysis (EDA)
- Data structure and distribution analysis
- Sensor behavior visualization
- Identification of anomaly patterns

---

### 2. Data Processing
- Feature engineering
- Data cleaning
- Sliding window approach for time series segmentation
- Dataset balancing and preparation

---

### 3. Model Development
Two deep learning architectures were tested:

- **LSTM (Long Short-Term Memory)**
- **Transformer**

Model tuning included:
- Grid Search
- Hyperparameter optimization
- Different optimizers (Adam, RMSprop, Adadelta)
- Dropout tuning

---

### 4. Model Selection
The **Transformer model** was selected due to:
- Better performance
- Parallelization capability
- Improved generalization

---

### 5. Validation
- K-Fold Cross Validation
- Training vs validation comparison
- Confusion matrix analysis

---

### 6. Model Interpretability
- Applied **Class Activation Maps (CAM)**
- Identified which time segments contributed most to predictions
- Correlated model behavior with physical sensor patterns

---

## 📈 Results
- **Accuracy:** > 98%
- Strong generalization across anomaly classes
- Effective early detection of transient anomalies
- Improved interpretability using CAM

---

## 🔍 Types of Anomalies Detected
- Rapid productivity loss
- Abrupt increase in water content (BSW)
- Flow restrictions (PCK)
- Spurious valve closures (DHSV)
- Hydrate formation in production lines

---

## 🛠 Tools & Technologies
- Python
- TensorFlow / Keras
- NumPy / Pandas
- Scikit-learn
- Data Visualization (Matplotlib / Seaborn)

---

## 📍 Key Insights
- Transformer models outperform LSTM in complex multivariate time series
- Early anomaly detection is feasible using transient signals
- Interpretability techniques (CAM) are essential for industrial trust
- Data-driven approaches can significantly reduce operational risks

---

## 🚀 What This Project Demonstrates
- Advanced Machine Learning (Deep Learning)
- Time Series Modeling (Multivariate)
- Real-world industrial application
- Model interpretability techniques
- End-to-end Data Science pipeline

---

## 📎 Files
- `Predictive exploratory analysis of anomalies in oil and gas extraction wells.pdf` → Full research paper

---

## 📬 Contact
Open to opportunities in:
**Data Science | Machine Learning | AI Engineering | Time Series Modeling**
