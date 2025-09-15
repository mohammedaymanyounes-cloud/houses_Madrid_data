# 🏠 House Prices Analysis – Madrid Dataset  

This project focuses on analyzing and predicting **house prices** in Madrid using Python.  
The goal is to understand which factors affect house prices the most and build a simple regression model to explain price variations.  

---

## 📌 Project Overview  
- **Data Cleaning:**  
  - Removed missing and duplicate values.  
  - Converted data types where necessary.  
  - Encoded categorical variables for modeling.  

- **Exploratory Data Analysis (EDA):**  
  - Visualized price distributions and outliers using histograms & boxplots.  
  - Created correlation heatmaps to find relationships between features.  
  - Investigated effect of features like `sq_mt_built`, `n_rooms`, `n_bathrooms` on price.  

- **Regression Analysis:**  
  - Built an **OLS Regression Model** using `statsmodels`.  
  - Interpreted coefficients to understand which variables impact price the most.  
  - Evaluated model fit using R² and p-values.  

---

## 🛠 Tools & Libraries  
- **Python**  
- **Pandas**, **NumPy** – Data Cleaning & Preparation  
- **Matplotlib**, **Seaborn** – Visualization  
- **Statsmodels** – Regression Analysis  

---

## 📊 Key Insights  
- Larger properties (higher `sq_mt_built`) have a strong positive correlation with price.  
- Number of bathrooms also significantly impacts price more than bedrooms.  
- Found and removed outliers to improve model accuracy.  

---

## 🚀 How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/house-madrid-analysis.git
