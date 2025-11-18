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
│
├─ data/
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
```
---

## 📊 Key Results

| Evaluation Metric | Logistic Regression |
|-------------------|----------------------|
| Overall Accuracy  | 0.58 |
| Obese Class F1 Score | 0.65 |
| Not Obese Class F1 Score | 0.49 |
| Average F1 Score across 5 folds (Obese) | 0.6636 |

The model performed significantly better at predicting individuals classified as **Obese** compared to **Not Obese**, with a recall of 0.73 for the Obese class, indicating strong sensitivity in identifying true positive obesity cases. The cross-validation average F1 score of **0.6636** further demonstrates stability and reliability in predicting obesity risk.

Key predictors included:
- **BMI**
- **Physical activity level**
- **General health rating**
- **Smoking status**
---

## 📊 Model Insights

✔ The model was more accurate at predicting **Obese** individuals (F1 Score: 0.65)  
✔ Lower recall for **Not Obese** suggests opportunity for class balancing  
✔ Average F1 Score for the Obese class across 5 folds: **0.6636**  
✔ Key influential features included BMI, physical activity, general health rating, and smoking status  

---

## 📝 Data Source

CDC Behavioral Risk Factor Surveillance System (BRFSS)  
Dataset Download: https://www.cdc.gov/brfss/

---

## 🧠 Author

**Ailey Shollenberger**  
Informatics – Human Centered Data Science  
The University of Texas at Austin  
GitHub: https://github.com/aileys  

---

