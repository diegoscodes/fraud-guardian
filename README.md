![status](https://img.shields.io/badge/Status-In%20Development-yellow?style=for-the-badge)

<p align="center">
  <img src="https://github.com/diegoscodes/fraud-guardian/blob/main/banner.png" alt="Project Banner" width="50%">
</p>


# 🛡️ Fraud Guardian

An **end-to-end credit card fraud detection** project designed for portfolio and real-world demonstration.  
It covers every step from data exploration and preprocessing to model training, cost-sensitive thresholding, explainability (SHAP), and deployment with FastAPI and Streamlit.

---

## 🚀 Overview

**Fraud Guardian** simulates the complete workflow of a fraud detection system using real-world credit card data.  
It includes:
- Data preprocessing and feature scaling  
- Class imbalance handling with SMOTE  
- Model training (Logistic Regression, XGBoost)  
- Cost-sensitive threshold optimization  
- Explainable AI (SHAP visualizations)  
- Simple API (FastAPI) + Interactive web dashboard (Streamlit)

---
```
## 🧱 Project Structure
```powershell
fraud-guardian/
│
├── 📂 api/ → FastAPI backend for predictions
├── 📂 data/ → Raw and processed datasets
├── 📂 docker/ → Dockerfile and compose setup
├── 📂 models/ → Trained ML models (.pkl)
├── 📂 notebooks/ → Jupyter notebooks for analysis
│ ├── 00_data_exploration.ipynb
│ ├── 01_modeling_thresholding.ipynb
│ ├── 02_shap_explainability.ipynb
│
├── 📂 src/ → Core Python modules
│ ├── preprocessing.py
│ ├── modeling.py
│ ├── utils.py
│
├── 📂 webapp/ → Streamlit UI for fraud detection demo
│
├── .gitignore
├── requirements.txt
└── README.md
```

<<<<<<< HEAD
=======
```
>>>>>>> 209314d5f847127a14a3f83cf063277199c63ae8

---

## ⚙️ Quickstart (Windows / PowerShell)

```powershell
# 1. Clone the repository
git clone <your-repo-url>
cd fraud-guardian

# 2. Create virtual environment
python -m venv .venv
.\.venv\Scripts\Activate.ps1

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run notebooks
jupyter notebook notebooks/00_data_exploration.ipynb

# 5. Run Streamlit app
streamlit run webapp/app.py
📊 Main Technologies
Category	Tools
Language	Python 3.11
Machine Learning	scikit-learn, XGBoost
Data Handling	pandas, numpy
Explainability	SHAP
Fairness & Ethics	Fairlearn
Web Framework	FastAPI, Streamlit
Deployment	Docker, Uvicorn
```
---
 
## 🧠 Current Progress
 Repository initialized

 Project structure created

 Data exploration notebook

 Modeling & thresholding

 SHAP explainability

 Streamlit + FastAPI demo

 Docker & CI/CD pipeline

---

## 📅 Roadmap
Phase	Description	Status
1️⃣	Data loading & preprocessing	🔄 In progress
2️⃣	Modeling (LR + XGBoost)	⏳ Pending
3️⃣	SHAP explainability	⏳ Pending
4️⃣	Streamlit & FastAPI deployment	⏳ Pending
5️⃣	Docker containerization	⏳ Pending
---
## 🧩 About
This project was built for educational and portfolio purposes.
It demonstrates the principles of Responsible AI, model explainability, and cost-based decision-making in fraud detection.
---
## 🧑‍💻 Author
Diego Ferreira
AI & Machine Learning Developer
LinkedIn • GitHub

