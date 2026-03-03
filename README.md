# 🎓 UniPath: Major & University Recommendation System

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-009688.svg)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-Scikit_Learn-F7931E.svg)
![Status](https://img.shields.io/badge/Status-In_Development-yellow.svg)

## 📖 Project Description

**UniPath** is a data-driven Web Application built to help high school students in Vietnam make informed decisions about their future careers and university choices. 

Instead of relying solely on traditional psychological tests or pure academic scores, this project implements a **Pure Recommendation System (RecSys)** using Machine Learning. By combining a student's academic performance (GPA) with their psychological profile (Holland RIASEC test), the system predicts the most suitable majors and provides a strategic list of 3 universities tailored to their exact score level.

### ✨ Key Features
- **Data-Driven Major Prediction:** Uses ML classification models (KNN/Random Forest) to recommend majors with a confidence score (%).
- **Explainable AI (XAI):** Integrates SHAP values to explain *why* a major is recommended based on feature importance.
- **Strategic University Filtering:** Applies rule-based logic to map the predicted major and converted GPA to 3 strategic university tiers:
  - 🎯 **Reach (Khát vọng)**
  - ✅ **Match (Vừa sức)** - 🛡️ **Safety (An toàn)**

### 🛠️ Tech Stack
- **Data Science / ML:** Python, Pandas, Scikit-learn, SHAP, Jupyter Notebook.
- **Backend API:** FastAPI.
- **Frontend:** ReactJS / Dash.
- **Database:** PostgreSQL.

---
*This project is developed by Group 2 for the Artificial Intelligence Programming course at FPT University.*
