# Obesity Risk Prediction using BRFSS Health Data

This project builds a machine learning model to predict obesity risk using demographic, lifestyle, and behavioral health features based on the CDC BRFSS dataset. Completed as part of the I310D Human-Centered Data Science course at The University of Texas at Austin.

---

## 📌 Project Objectives
- Clean and preprocess large-scale survey data
- Build and evaluate classification models (Logistic Regression, Random Forest)
- Analyze feature importance and interpret results
- Use data visualization to interpret findings
- Communicate insights in human-centered and actionable ways

---

## 🛠️ Tools and Technologies

| Category           | Tools |
|--------------------|------------------------------|
| Languages          | Python |
| Data Processing    | Pandas, NumPy |
| Machine Learning   | Scikit-learn, Statsmodels |
| Visualization      | Matplotlib, Seaborn |
| Explainability     | Coefficients, Accuracy, Confusion Matrix |
| Notebook Platform  | Jupyter Notebook |

---

## 📂 Repository Structure
obesity-risk-prediction-brfss/
│
├─ notebooks/
│   ├─ i310_final_project.ipynb
│   └─ README.md
│
├─ src/
│   └─ README.md
│
├─ data/
│   └─ README.md
│
├─ figures/
│   └─ README.md
│
├─ README.md
├─ requirements.txt
└─ .gitignore

---

## 🚀 How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/aileys/obesity-risk-prediction-brfss.git
cd obesity-risk-prediction-brfss
python -m venv venv
source venv/bin/activate       # Mac/Linux
venv\Scripts\activate          # Windows
pip install -r requirements.txt
jupyter notebook

