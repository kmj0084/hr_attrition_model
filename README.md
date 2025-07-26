# HR Attrition Prediction Model

This project analyzes employee attrition using synthetic HR data. It demonstrates an end-to-end data science workflow, from data cleaning and exploratory analysis to predictive modeling and evaluation. The goal is to identify key drivers of attrition and build a model to help HR stakeholders proactively address turnover.

## 📊 Project Overview

- **Problem**: Employee turnover is costly and disrupts organizational continuity.
- **Goal**: Use historical HR data to predict whether an employee is likely to leave.
- **Tools**: Python, Pandas, scikit-learn, Matplotlib, Seaborn

## 🔧 Tech Stack

- Python 3.10+
- pandas
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

## 🧪 Features

- Cleaned and encoded categorical HR variables
- Exploratory Data Analysis (EDA) on employee engagement, satisfaction, and tenure
- Trained classification models: Logistic Regression, Random Forest
- Feature importance interpretation
- Accuracy, precision, recall, ROC-AUC evaluation
- Exported visualizations and summary insights

## 📁 Repo Structure

hr_attrition_model/
├── data/
│ └── employee_data.csv # synthetic HR dataset
├── notebooks/
│ └── attrition_model.ipynb # Jupyter notebook with full analysis
├── outputs/
│ └── charts/ # EDA plots, feature importances, etc.
├── requirements.txt
└── README.md

## 📈 Sample Insights

- High attrition correlated with low satisfaction, high overtime, and shorter tenure.
- Random Forest outperformed baseline models with ~82% ROC-AUC.
- Top features: Job Role, Monthly Income, Overtime, Years at Company

## 🧠 Future Improvements

- Test additional models (XGBoost, LightGBM)
- Add SHAP explainability
- Integrate survey or qualitative metrics
- Deploy as a lightweight dashboard using Streamlit or Flask

## 👤 Author

**Keegan Johnson**  
[LinkedIn](https://www.linkedin.com/in/kmj0084) | [Email](mailto:keeganjohnson89@gmail.com)

---

> *This project uses synthetic data. No proprietary or sensitive employee information is included.*


