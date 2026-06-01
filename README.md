
# **EV Market 2026 — Analytics & Insights**

A full analytics project exploring the 2026 global electric vehicle (EV) market using data engineering, exploratory analysis, feature engineering, and machine learning.  
This project is designed as a **portfolio‑ready showcase** of data cleaning, modeling, visualization, and business insight generation.


##  **Project Overview**

This project analyzes a curated dataset of electric vehicles across major global brands (Tesla, Kia, Toyota, Mercedes, Volkswagen, GM, etc.).  
It includes:

- Data cleaning & preprocessing  
- Feature engineering  
- Exploratory data analysis (EDA)  
- Machine learning price prediction  
- Market segmentation insights  
- Visualizations for performance, efficiency, and pricing  
- A Colab‑ready workflow using GitHub‑hosted data  



## **Repository Structure**

ev_market_2026/
│
├── data/
│   └── raw/
│       └── ev_market_2026.csv
│
├── notebooks/
│   └── ev_market_2026_analysis.ipynb
│
├── src/
│   ├── data_cleaning.py
│   ├── eda.py
│   ├── modeling.py
│   └── utils.py
│
├── figures/
│   └── (generated plots)
│
└── README.md



## **Dataset Description**

The dataset includes **25+ features** describing EV specifications, performance, pricing, and market behavior.

### **Key Columns**
- `brand`, `model`, `variant`, `year`  
- `price_usd`  
- `battery_capacity_kwh`, `range_miles`, `charging_speed_kw`  
- `acceleration_0_60_mph`, `horsepower`, `torque_nm`  
- `drive_type`, `body_type`, `seating_capacity`  
- `safety_rating`, `autopilot_level`  
- `annual_sales_units`, `customer_rating`  
- `market_segment` (Luxury, Mid‑range, Premium)  

### **Engineered Features**
- `price_per_kwh`  
- `range_efficiency_mi_per_kwh`  
- `performance_score`  
- `value_index_range_per_usd`  


##  **Technologies Used**

- **Python** (Pandas, NumPy, Scikit‑learn, Seaborn, Matplotlib)  
- **Google Colab** (cloud execution)  
- **GitHub** (data hosting + version control)  
- **Machine Learning** (Linear Regression, Random Forest)  


##  **How to Run the Project (Google Colab)**

### **1. Open Colab**
`https://colab.research.google.com/` [(colab.research.google.com in Bing)](https://www.bing.com/search?q="https%3A%2F%2Fcolab.research.google.com%2F")

### **2. Load the dataset directly from GitHub**

```python
import pandas as pd

url = "https://raw.githubusercontent.com/kiplagatdenni/ev_market_2026/main/data/raw/ev_market_2026.csv"
df = pd.read_csv(url)
df.head()
```

### **3. Run the full notebook**
The notebook performs:

- Data cleaning  
- Feature engineering  
- EDA visualizations  
- ML modeling  
- Insights  

---

##  **Exploratory Data Analysis Highlights**

The analysis explores:

- **Price vs Range**  
- **Battery capacity vs Range**

- <img width="722" height="547" alt="image" src="https://github.com/user-attachments/assets/858801f4-3d05-4806-8ea6-5818627c987e" />

- **Acceleration vs Horsepower**
- <img width="695" height="547" alt="image" src="https://github.com/user-attachments/assets/cf4d8bce-ee81-41ae-ba2d-ed36723e9450" />

- **Market segment distribution**
- <img width="463" height="411" alt="image" src="https://github.com/user-attachments/assets/81d0025f-5204-4771-b9c7-98e59ebeb03a" />

- **Autopilot level adoption**  
- **Brand performance clusters**  

These visualizations help identify:

- Which brands offer the best value  
- Which EVs lead in performance  
- How pricing correlates with technology  
- Market positioning across segments  

---

## **Machine Learning Models**

Two models were trained to predict EV price:

### **1. Linear Regression**
- Baseline model  
- Interpretable coefficients  
- Good for understanding feature influence  

### **2. Random Forest Regressor**
- Handles nonlinear relationships  
- Higher predictive accuracy  
- Feature importance extraction  

### **Evaluation Metrics**
- MAE  
- RMSE  
- R² Score  

---

##  **Key Insights**

- **Tesla dominates luxury performance**, but price efficiency varies.  
- **Kia and Toyota deliver strong value** in mid‑range segments.  
- **German brands cluster in high‑performance, high‑price categories.**  
- **Range efficiency differs significantly by body type** (SUV vs Hatchback).  
- **Autopilot Level 3+ adoption is still limited** across most brands.  

---

##  **Future Enhancements**

- Add **clustering** for market segmentation  
- Build a **Power BI dashboard**  
- Add **time‑series forecasting** for EV sales  
- Deploy a **Streamlit app** for interactive exploration  

---

##  **Author**

**Dennis Kiplagat**  
Graduate Student — Information systems and business analytics Park university

Focused on:  
- Data engineering  
- Machine learning  
- Transportation analytics  
- EV market intelligence  

--- 

Just tell me what you want next.
