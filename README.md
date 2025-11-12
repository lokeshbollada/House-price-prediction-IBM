# 🏠 House Price Prediction — IBM Data Analysis with Python

**Final project from IBM’s _Data Analysis with Python_ (Coursera).**  
Predicting house prices in King County (Seattle area) using Exploratory Data Analysis and regression models.

---

## 🚀 Project Summary

- **Objective:** Predict house prices using features such as `sqft_living`, `grade`, `bathrooms`, `view`, and more.  
- **Dataset:** King County house sales (2014–2015).  
- **Tools / Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook.  
- **Key Techniques:** Data cleaning, EDA, feature engineering, Linear Regression, Ridge Regression, Polynomial features, model validation.

---

## 📁 Repository Structure

House-price-prediction-IBM/
├── notebook/
│ └── House_Sales_in_King_County_USA.ipynb
├── certificate/
│ └── IBM_Data_Analysis_with_Python_Certificate.pdf
├── images/
│ ├── boxplot_waterfront.png
│ ├── regplot_sqft_above.png
│ └── ridge_regression_r2.png
├── requirements.txt
└── README.md


---

## 📈 Results (Insert your metrics)

| Model | Description | R² Score |
|-------|-------------|----------|
| Simple Linear Regression | `sqft_living` → `price` | **REPLACE_WITH_VALUE** |
| Multiple Linear Regression | Selected features | **REPLACE_WITH_VALUE** |
| Ridge Regression (α=0.1) | Regularized linear model | **REPLACE_WITH_VALUE** |
| Polynomial (degree=2) + Ridge | Non-linear features + regularization | **REPLACE_WITH_VALUE** |

> Replace the `REPLACE_WITH_VALUE` cells above with your actual R² scores from the notebook.

---

## 🔍 Key Insights

- `sqft_living` and `grade` are the strongest predictors of price.
- `waterfront` and `view` correlate with large price increases and outliers.
- Regularization (Ridge) improved model generalization compared to plain Linear Regression.
- Polynomial features captured some non-linear relationships, improving test performance slightly.

---

## 🧾 How to Reproduce

1. Clone the repository:
   ```bash
   git clone https://github.com/lokeshbollada/House-price-prediction-IBM.git
   cd House-price-prediction-IBM

(Optional) Create and activate a virtual environment.

Install dependencies:

pip install -r requirements.txt


Open the notebook:

jupyter lab notebook/House_Sales_in_King_County_USA.ipynb

🎓 Certificate

My verified Coursera certificate is included in this repo:

IBM Data Analysis with Python — Coursera
certificate/IBM_Data_Analysis_with_Python_Certificate.pdf
Or view online: https://www.coursera.org/account/accomplishments/certificate/YOUR_CERTIFICATE_ID

🧑‍💻 About the Author

Lokeshkumar Bollada



LinkedIn: https://www.linkedin.com/in/lokeshkumar-bollada/

GitHub: https://github.com/lokeshbollada

📌 Credits & References

Data source: King County House Sales dataset (Kaggle)

Course: IBM — Data Analysis with Python (Coursera)


---

## Commands to add, commit and push README

Run these in your project folder terminal:

```bash
git add README.md
git commit -m "Add polished README for final project"
git push origin main