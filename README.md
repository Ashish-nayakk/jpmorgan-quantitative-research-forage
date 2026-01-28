# JPMorgan Chase & Co. – Quantitative Research Virtual Experience (Forage)

This repository contains my work for the **JPMorgan Chase Quantitative Research Virtual Experience Program**, a 4-task simulation designed to mirror real responsibilities of quantitative researchers at JPMorgan.

Each task includes code, visualizations, and documentation.

---

## ✅ Completed Tasks

### 🔹 Task 1 — Investigate and Analyze Price Data  
- Cleaned and interpolated natural gas price data  
- Built a daily time-series model with seasonal adjustments  
- Created a function to estimate commodity price for any date  

📁 `Task-1-Investigate-Price-Data/`

---

### 🔹 Task 2 — Price a Commodity Storage Contract  
- Developed a pricing engine for storage contracts  
- Modeled cash flows, fees, storage limits & injection/withdrawal schedules  
- Built a reusable contract valuation function  

📁 `Task-2-Price-a-Commodity-Storage-Contract/`

---

### 🔹 Task 3 — Credit Risk Analysis  
- Built a logistic regression model to estimate **Probability of Default (PD)**  
- Engineered borrower features and evaluated model performance  
- Calculated **Expected Loss (EL)** using PD × LGD × Exposure  
- Built a callable expected loss function for any new borrower  

📁 `Task-3-Credit-Risk-Analysis/`

---

### 🔹 Task 4 — Bucket FICO Scores (Quantization)  
- Analyzed FICO score distribution for a mortgage loan portfolio  
- Created optimized buckets using quantile-based MSE minimization  
- Assigned credit ratings where **lower = better**  
- Computed PD per bucket to validate predictive power  
- Built a general-purpose FICO → rating mapping function  

📁 `Task-4-Bucket-FICO-Scores/`

---

## 📂 Repository Structure

```
jpmorgan-quantitative-research-forage/
│
├── Task-1-Investigate-Price-Data/
├── Task-2-Price-a-Commodity-Storage-Contract/
├── Task-3-Credit-Risk-Analysis/
├── Task-4-Bucket-FICO-Scores/
└── README.md
```

---

## 🧠 Skills Demonstrated

- Python (Pandas, NumPy, Matplotlib, scikit-learn)  
- Time Series Modeling  
- Commodity Pricing & Financial Engineering  
- Machine Learning (Logistic Regression, Feature Engineering)  
- Credit Risk Modeling (PD & Expected Loss)  
- Quantization & FICO Score Bucketing  
- Data Analysis & Visualization  
- Dynamic Programming Concepts  

---

## 👤 Author

**Ashish Kumar Nayak**  
🔗 LinkedIn: https://linkedin.com/in/ashish-nayak-2ba779385  
🔗 GitHub: https://github.com/Ashish-nayakk

---

## 📌 About the Program

The JPMorgan Quantitative Research Virtual Experience on Forage simulates real quant work including time-series analysis, contract pricing, credit risk modeling, and transforming continuous variables into categorical ones through quantization.

