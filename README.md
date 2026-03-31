# 🛒 Walmart Sales Analysis & Demand Insights

## 📌 Project Overview
This project focuses on analyzing Walmart retail data to extract business insights, understand customer behavior, evaluate promotion effectiveness, and identify inventory issues.

The goal is to enable data-driven decision-making using:
- Exploratory Data Analysis (EDA)
- Business Insights
- Power BI Dashboard
---

## 📂 Dataset Description
The dataset contains 5000 transactions with 28+ features, including:

- Product details (category, product name)
- Sales data (quantity, unit price, total sales)
- Customer information (age, gender, income, loyalty level)
- Store information (location, store ID)
- Inventory data (inventory level, stockout indicator)
- External factors (weather, holidays)
- Demand data (forecasted vs actual demand)

---

## ⚙️ Data Preprocessing
- Converted `transaction_date` to datetime format  
- Handled missing values in `promotion_type` (filled with "No Promotion")  
- Removed duplicates  
- Created new features:
  - `total_sales = quantity_sold × unit_price`
  - `month`, `year`  

---

## 📊 Exploratory Data Analysis (EDA)
Performed:
- Univariate analysis (distribution plots)
- Categorical analysis (value counts, groupby)
- Bivariate analysis (relationship with sales)
- Time series analysis (monthly trends)
- Inventory and demand analysis

---

## 🔍 Key Insights
- Promotions significantly increase sales  
- Electronics category generates higher revenue than appliances  
- Stockouts lead to potential revenue loss  
- High-loyalty customers contribute more revenue  
- Forecasted demand differs from actual demand  
- Sales show seasonal and monthly trends  
- Sales increase during holidays  

---

## 💡 Business Recommendations
- Optimize inventory to reduce stockouts  
- Focus promotions on high-performing products  
- Improve demand forecasting models  
- Introduce loyalty programs for retention  
- Plan inventory based on seasonal trends  
- Improve performance of low-performing stores  
- Enhance digital payment experience  
- Optimize reorder points and supplier lead times  

---

## 📊 Dashboard (Power BI)

### 🔑 KPIs
- Total Revenue  
- Total Orders  
- Average Order Value   

### 📈 Visualizations
- Sales Trend (week-wise)  
- Category Performance  
- Store Performance    
- Payment Method Distribution  
- Demand vs Forecast  

### 🎛 Filters (Slicers)
- Month  
- Catogory 

---


## 📌 Conclusion
This project demonstrates how data analysis can:
- Improve inventory management  
- Optimize promotions  
- Understand customer behavior  
- Identify demand patterns  

The insights help in making data-driven business decisions.

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Power BI  
- Scikit-learn  

---

