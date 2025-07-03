# Phishing Detection System using Hybrid Machine Learning based on URL

This project was developed as a major academic project during the final semester of MCA. It focuses on detecting phishing websites by analyzing URL-based features and applying hybrid machine learning models.

## 🎯 Purpose

To build an intelligent system that automatically detects phishing websites using machine learning techniques based on URL characteristics — helping users stay safe from online fraud and cyberattacks.

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Machine Learning Algorithms:  
  - Decision Tree  
  - Random Forest  
  - K-Nearest Neighbors (KNN)
- Libraries: `pandas`, `numpy`, `scikit-learn`, `tld`, `joblib`, `matplotlib`

## 📦 Project Structure

- `features.ipynb` — Feature extraction and preprocessing
- `KSN_MODEL.ipynb` — ML model training, evaluation, and testing
- `finalized_model.sav` — Saved trained model
- `dataset.csv` — Dataset of URLs (phishing and legitimate)
- `README.md` — Project documentation

## 🧠 Features Extracted from URL

- Use of HTTPS / SSL
- Domain length
- Subdomain count
- Special characters like `@`, `-`
- Use of shortening services
- Presence of suspicious words, etc.

## 📊 Machine Learning Approach

This system uses a **hybrid machine learning approach** by training and comparing:
- **Decision Tree** – for rule-based classification
- **Random Forest** – for ensemble learning
- **K-Nearest Neighbors (KNN)** – for pattern recognition

The best-performing model is chosen based on:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## 🚀 How to Run

1. Clone or download this repository  
2. Install required libraries:  
