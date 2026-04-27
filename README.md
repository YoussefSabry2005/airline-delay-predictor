# ✈️ Airline Delay Predictor

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat&logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?style=flat&logo=scikit-learn)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat)

A machine learning project that predicts flight delays using historical airline data. Built with Python, Pandas, and Scikit-learn using a Random Forest classifier.

---

## 📌 Project Overview

Flight delays cost the airline industry billions of dollars annually and significantly impact passenger experience. This project builds a predictive model that estimates the likelihood of a flight delay based on historical patterns, route data, and airline performance metrics.

---

## 🎯 Objectives

- Clean and preprocess raw airline data from OpenFlights
- Perform exploratory data analysis (EDA) to identify delay patterns
- Engineer meaningful features from flight and route data
- Build and evaluate a Random Forest classification model
- Visualize predictions and model performance interactively

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.10+** | Core programming language |
| **Pandas** | Data manipulation and cleaning |
| **NumPy** | Numerical computations |
| **Scikit-learn** | Machine learning (Random Forest) |
| **Matplotlib / Seaborn** | Data visualization |
| **Jupyter Notebook** | Development environment |

---

## 📂 Dataset

- **Source:** [OpenFlights](https://openflights.org/data.html)
- **Contents:** Historical flight routes, airline performance, airport data
- **Size:** TBD upon full data collection

---

## 🔬 Methodology

1. **Data Collection** — Download and merge OpenFlights datasets
2. **Data Cleaning** — Handle missing values, outliers, and inconsistencies
3. **EDA** — Identify patterns in delays by airline, route, and time
4. **Feature Engineering** — Extract meaningful features (departure time, route distance, carrier)
5. **Model Training** — Train Random Forest classifier with cross-validation
6. **Evaluation** — Accuracy, Precision, Recall, F1-Score, ROC-AUC
7. **Visualization** — Interactive dashboard for predictions

---

## 📊 Expected Results

- Predict whether a flight will be delayed (binary classification)
- Identify top factors contributing to delays
- Compare performance across multiple ML models

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/YoussefSabry2005/airline-delay-predictor.git

# Navigate to project directory
cd airline-delay-predictor

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
```

---

## 📁 Project Structure

```
airline-delay-predictor/
│
├── data/               # Raw and processed datasets
├── notebooks/          # Jupyter notebooks for EDA and modeling
├── src/                # Python scripts
├── visualizations/     # Charts and plots
├── requirements.txt    # Dependencies
└── README.md
```

---

## 👤 Author

**Youssef Sabry**
- 📍 Edmonton, Alberta, Canada
- 🎓 BSc Data Science — MacEwan University (Graduating Winter 2028)
- 💼 [LinkedIn](https://www.linkedin.com/in/youssef-sabry22/)
- 🐙 [GitHub](https://github.com/YoussefSabry2005)

---

## 📌 Status

🔄 **In Progress** — Currently in data collection and EDA phase

---

*Part of my Data Science portfolio. Built to demonstrate applied ML skills for internship and job applications.*
