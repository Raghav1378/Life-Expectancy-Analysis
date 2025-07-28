# Life Expectancy Prediction using Machine Learning

This project focuses on predicting the **Life Expectancy** of countries using various health, economic, and demographic features

## 📊 Dataset Overview
The dataset contains **15+ years** of country-level data across features such as:
- Immunization rates
- Adult Mortality
- GDP
- Schooling
- Healthcare expenditure
- and more...

## 🧠 Objective
To develop regression models that can predict a country's **Life Expectancy** using machine learning techniques. Feature importance analysis was also performed to derive key health indicators affecting life expectancy.

## 🧪 ML Models Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- SHAP for Model Explainability

## 🧾 Key Insights
- Features like `Schooling`, `Adult Mortality`, and `BMI` had high influence on life expectancy.
- Random Forest performed best among the tested models.
- SHAP analysis helped in interpreting the model’s predictions clearly.

## 🧰 Tech Stack
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- SHAP (for interpretability)
- Jupyter Notebook

## 📁 Files in this Repository
- `Life Expectancy Data.csv` - Dataset
- `life_expectancy_analysis.ipynb` - Code notebook
- `README.md` - This file


### 📌 Future Improvements
- Deploy as a Streamlit web app for interactive use
- Add more ensemble models
- Perform time-series forecasting

---

⭐️ If you found this helpful, feel free to fork and star the repo!
