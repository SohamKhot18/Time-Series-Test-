# 📈 Quantity Analysis Time Series Forecasting

**Brief Objective:** Analyze and forecast monthly product sales quantity using ARIMA time series modeling.

This project uses historical sales data to build and evaluate a forecasting model that predicts future sales trends. The analysis and modeling are done in a Jupyter Notebook on monthly aggregated sales data.

---

## 📁 Project Contents

- `notebooks/analysis.ipynb` — Main Jupyter Notebook with the full workflow  
- `data/sales_data.csv` — Original sales dataset  
- `README.md` — Project overview  

---

## 🧠 Key Features

- Data preprocessing and time series conversion  
- Seasonal decomposition of sales data  
- ARIMA model training and forecasting  
- Model evaluation using Mean Squared Error (MSE)  
- Visualization of actual vs forecasted sales  

---

## 🔧 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Statsmodels (for ARIMA)  
- Scikit-learn (for evaluation)  

---

## 📊 Dataset Info

The dataset includes:  
- OrderDate  
- ParentProductIdNew  
- ParentProductNew  
- ProductCategoryNew  
- ArtistNameNew  
- total_qty_sales  
- Selling Price  
- productListViews  
- productListClicks  

---

## 🚀 How to Run

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/Quantity-Analysis-Time-Series.git
   cd Quantity-Analysis-Time-Series

2. Install required packages:
   ```bash
   pip install -r requirements.txt

4. Open the notebook and run:
   ```bash
   jupyter notebook notebooks/analysis.ipynb

**By - SOHAM K**
