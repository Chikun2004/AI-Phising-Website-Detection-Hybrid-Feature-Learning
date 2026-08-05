# 🛡️ AI-Based Phishing Website Detection Using Hybrid Feature Learning

A Final Year Research Project that leverages **Machine Learning**, **Ensemble Learning**, and **Explainable AI (SHAP)** to detect phishing websites using only URL-based lexical and structural features. The system eliminates the need for webpage content or third-party APIs, making it lightweight, efficient, and suitable for real-time phishing detection.

---

## 📖 Overview

Phishing attacks are one of the most common cybersecurity threats, where attackers create fraudulent websites to steal sensitive information such as usernames, passwords, and banking credentials.

This project presents a machine learning framework capable of detecting phishing websites by analyzing URL characteristics alone. Eight machine learning models were trained and evaluated, with the **Stacking Ensemble** delivering the best overall performance.

---

## ✨ Features

* URL-based phishing detection
* Lightweight detection without webpage content
* Recursive Feature Elimination (RFE)
* Explainable AI using SHAP
* Comparison of 8 Machine Learning models
* Real-time phishing URL prediction
* Model evaluation using Accuracy, Precision, Recall, F1-Score, and ROC-AUC
* Google Colab implementation

---

## 📊 Dataset

* **Source:** Kaggle – Multi-Dataset Phishing URLs
* **Total Samples:** 10,000
* **Phishing URLs:** 5,000
* **Legitimate URLs:** 5,000
* **Data Type:** Balanced Dataset

---

## 🤖 Machine Learning Models

* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest
* Gradient Boosting
* XGBoost
* Artificial Neural Network (ANN)
* Voting Ensemble
* **Stacking Ensemble (Best Model)**

---

## 📈 Performance

| Metric       |             Value |
| ------------ | ----------------: |
| Best Model   | Stacking Ensemble |
| Accuracy     |        **90.95%** |
| ROC-AUC      |        **96.08%** |
| Dataset Size |       10,000 URLs |

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Libraries & Frameworks

* Scikit-learn
* TensorFlow / Keras
* XGBoost
* SHAP
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Imbalanced-learn (SMOTE)
* Joblib

### Platform

* Google Colab

---

## 📂 Project Structure

```text
AI-Based-Phishing-Website-Detection/
│
├── FYRP-AI-Based_Phishing_Website_Detection_Using_Hybrid_Feature_Learning.ipynb
├── Group 26-10(Project Report).docx
├── Group 26-10(Manuscript).docx
├── Group 26-10.pptx
├── Help_Document.docx
├── Support_Document.docx
└── README.md
```

---

## 📄 Repository Contents

| File                                                                             | Description                                                                                                                                   |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| **FYRP-AI-Based_Phishing_Website_Detection_Using_Hybrid_Feature_Learning.ipynb** | Complete implementation including preprocessing, feature engineering, model training, evaluation, SHAP analysis, and phishing URL prediction. |
| **Group 26-10(Project Report).docx**                                             | Final project report containing methodology, implementation, experiments, results, and future scope.                                          |
| **Group 26-10(Manuscript).docx**                                                 | Research manuscript prepared from the project work.                                                                                           |
| **Group 26-10.pptx**                                                             | Final presentation explaining objectives, methodology, architecture, results, and conclusions.                                                |
| **Help_Document.docx**                                                           | Step-by-step instructions for executing the project in Google Colab.                                                                          |
| **Support_Document.docx**                                                        | Documentation of required libraries, dependencies, runtime environment, and generated artifacts.                                              |

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/<your-username>/AI-Based-Phishing-Website-Detection.git
cd AI-Based-Phishing-Website-Detection
```

### Open the Notebook

Open the notebook in **Google Colab**:

1. Upload the notebook to Google Colab.
2. Install the required packages.
3. Download the dataset from Kaggle.
4. Execute all notebook cells sequentially.

---

## 📊 Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Recursive Feature Elimination (RFE)
6. Model Training
7. Ensemble Learning
8. SHAP Explainability
9. Performance Evaluation
10. Real-Time URL Prediction

---

## 📸 Results

* Stacking Ensemble achieved the highest overall performance.
* SHAP analysis identified URL Length, Path Length, and File Name Length as the most influential phishing indicators.
* The framework provides accurate, explainable, and lightweight phishing detection suitable for real-world cybersecurity applications.

---

## 🔮 Future Scope

* Chrome Extension
* Firefox Extension
* REST API Deployment
* Cloud-Based Phishing Detection
* WHOIS & DNS Feature Integration
* SSL Certificate Analysis
* Zero-Day Phishing Detection
* Continuous Model Retraining

---

## 👥 Team Members

* Aditya Pal
* Piyush Kumar Pradhan
* Raja Kishor Nayak
* Tanmaya Mangaraj
* S. Ramananda Sagar

**Supervisor:** Mr. Subhasish Mohanty

---

## 📜 License

This project is developed for academic and research purposes.

---

## ⭐ Support

If you found this project useful, please consider giving it a **⭐ Star** on GitHub.

It helps others discover the project and motivates future improvements.
