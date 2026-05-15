# 🛡️ SOC Intelligent – AI-Powered Intrusion Detection System

## 📌 Overview
This project is an **AI-powered Security Operations Center (SOC)** designed to detect network intrusions using Machine Learning techniques.

It simulates a real-world cybersecurity monitoring system using the **CICIDS2017 dataset**, combining **Data Engineering, Machine Learning, and Cloud-ready deployment practices**.

---

## ⚙️ Tech Stack

- Python 🐍  
- Machine Learning (XGBoost) 🤖  
- Flask (REST API) ⚡  
- Streamlit (Monitoring Dashboard) 📊  
- Docker & Docker Compose 🐳  
- Pandas / Scikit-learn  

---

## 🧠 Key Features

- 📊 Data preprocessing & feature engineering on CICIDS2017 dataset  
- 🤖 Machine Learning model for network intrusion detection (XGBoost)  
- ⚡ Real-time prediction via REST API (Flask + JWT-ready architecture)  
- 📈 Interactive SOC dashboard with Streamlit  
- 🚨 Alerting & monitoring of network anomalies  
- ☁️ Fully containerized architecture (Docker / Docker Compose)  

---

## 🏗️ System Architecture

---

## 🚀 How to Run

```bash
git clone https://github.com/shiliMariem/soc-ml-intrusion-detection.git
cd soc-ml-intrusion-detection
docker-compose up --build
