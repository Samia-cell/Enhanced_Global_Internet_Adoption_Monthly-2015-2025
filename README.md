# 🌐 Global Internet & E-Commerce Adoption Analysis (2015–2025)

Can we predict a country’s digital evolution based on infrastructure, education, and mobile trends?  
This project explores global digital transformation using machine learning — with a focus on **Internet Penetration** and **E-Commerce Adoption** across 10+ years of monthly data.

---

## 📌 Overview

Using a dataset rich with global digital indicators (like broadband speed, mobile usage, GDP, digital literacy, and cloud adoption), this project builds ML models that:

- Predict future **Internet Penetration (%)** and **E-Commerce Penetration (%)**
- Reveal **which features matter most** using SHAP explainability
- Visualize patterns through interactive dashboards

---

## 🧠 Objectives

- Build accurate ML models using Random Forest and XGBoost
- Combine models via **Stacking Regressor** to improve performance
- Use SHAP to explain *why* models make their predictions
- Extract actionable insights from global trends

---

## ⚙️ Tools & Technologies

| Category            | Tools & Libraries                                |
|---------------------|--------------------------------------------------|
| Programming         | Python                                           |
| ML & Modeling       | Scikit-learn, XGBoost, Random Forest, GridSearchCV |
| Visualization       | Plotly, Matplotlib, Seaborn                      |
| Explainability      | SHAP                                             |
| Workflow            | Jupyter Notebook, Joblib                         |

---

## 📁 File Structure

```bash
├── dataset.csv                            # Cleaned dataset (optional)
├── Enhanced_Global_Internet_Adoption.ipynb  # Main notebook
├── rf_internet_optimized.pkl              # Saved RF model (Internet)
├── rf_ecommerce_optimized.pkl             # Saved RF model (E-Commerce)
├── stack_internet.pkl                     # Stacking model (Internet)
├── stack_ecommerce.pkl                    # Stacking model (E-Commerce)
└── README.md

