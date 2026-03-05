# 🚨 AI-Based Anomaly Detection in 6G Communication Networks

![Banner](assets/Banner.png)

An AI-powered anomaly detection system designed to identify abnormal network traffic patterns in 6G-like communication environments using machine learning models.

The system learns normal network traffic behavior and detects deviations such as high connectivity attempts and sudden delay/jitter anomalies.

---

## 📌 Project Overview

Future 6G networks will support ultra-low latency, high data rates, and massive IoT connectivity.  
Due to the dynamic and complex nature of network traffic, detecting abnormal behavior becomes challenging.

This project proposes a machine learning–based anomaly detection system that analyzes network traffic and identifies abnormal patterns automatically.

---

## 🎯 Key Features

- Network traffic anomaly detection using machine learning
- Detection of high connectivity attempts and delay/jitter anomalies
- Data preprocessing and feature engineering
- Model evaluation using multiple performance metrics
- Visualization of detected anomalies

---

## 🧠 Technologies Used

**Programming Language**

- Python

**Machine Learning**

- Scikit-learn
- Isolation Forest
- One-Class SVM

**Libraries**

- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Dataset

This project uses the **UNSW-NB15 dataset**, a modern cybersecurity dataset for network intrusion detection.

Dataset characteristics:

- Network traffic dataset
- 49 features per network flow
- Includes both normal and attack traffic
- Used for anomaly detection research

Dataset Source:

https://research.unsw.edu.au/projects/unsw-nb15-dataset

---

## ⚙️ Methodology

The system follows these steps:

1. Load UNSW-NB15 dataset  
2. Data preprocessing  
   - Handle missing values  
   - Encode categorical features  
   - Normalize numerical features  
3. Train-test split  
4. Model training using Isolation Forest / One-Class SVM  
5. Detect anomalies in network traffic  
6. Evaluate performance using ML metrics  
7. Visualize anomaly detection results

---

## 📈 Evaluation Metrics

Model performance is evaluated using:

- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

---

## 📂 Project Structure

```
AI-Anomaly-Detection-6G
│
├── anomaly_detection.ipynb
├── dataset_sample.csv
├── README.md
└── banner.png
```

---

## 🚀 Future Improvements

- Real-time anomaly detection
- Streamlit dashboard for visualization
- Deep learning-based detection models
- Edge-based monitoring for next-generation networks

---

## 👨‍💻 Author

**Fardeen Ali**  
B.Tech CSE (AI & ML)  
UPES Dehradun  

GitHub: https://github.com/Fabi-25f  
LinkedIn: https://linkedin.com/in/fardeen-ali-a73929335/
