# Chain-Stores-5-Year-Sales-Analysis-Predictive-Modeling-

This repository contains an end-to-end data analysis and predictive modeling workflow for a five-year sales dataset from a chain store. The project includes data preprocessing, exploratory data analysis (EDA), and machine learning modeling to extract business insights and forecast sales trends.

## 📂 Repository Structure  

- **`ChainStores_5Years_Preprocess.ipynb`**  
  - Loads the raw sales dataset.
  - Cleans the data by handling missing values and duplicate records.
  - Selects relevant features for analysis.
  - Transforms data for better usability.

- **`ChainStores_5Years_EDA&Modeling.ipynb`**  
  - Performs exploratory data analysis (EDA) with visualizations.
  - Identifies trends, seasonality, and key sales drivers.
  - Applies machine learning models to predict future sales.

---

## 🛠 Methodology  

### **1️⃣ Data Preprocessing**  
- Loaded a five-year sales dataset from a retail chain.  
- Selected essential columns related to customer transactions, product details, and sales figures.  
- Identified and removed missing or duplicate entries.  
- Standardized column names and data formats for consistency.  

### **2️⃣ Exploratory Data Analysis (EDA)**  
- Aggregated data to analyze **monthly and yearly sales trends**.  
- Used **visualizations (bar charts, line plots, and heatmaps)** to understand seasonal variations.  
- Identified the best-selling products, top-performing stores, and sales trends over time.  
- Analyzed the relationship between different features.

### **3️⃣ Predictive Modeling**  
- Explored different machine learning models for sales forecasting:  
  - **Linear Regression**: To establish baseline sales predictions.  
  - **Random Forest**: To capture complex relationships in the data.  
- Evaluated model performance using **metrics like RMSE (Root Mean Square Error)**.  

---

## 📊 Key Findings  

✅ **Sales Trends**:  
- Sales exhibit **seasonal patterns**, with peaks during specific months.  
- Certain stores consistently outperform others in terms of revenue.  

✅ **Product Performance**:  
- A small percentage of products contribute to the majority of sales.  
- Discounted products tend to increase overall sales volume but reduce profit margins.  

✅ **Predictive Insights**:  
- Machine learning models successfully predict sales trends with reasonable accuracy.  
- Feature importance analysis shows that **seasonality, product type, and price** are the strongest predictors of future sales.  
