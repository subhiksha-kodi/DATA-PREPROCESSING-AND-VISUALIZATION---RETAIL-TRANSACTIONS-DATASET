# 🛒 Retail Transactions Data Analysis  

## 📌 Project Overview  
This project analyzes a **retail transactions dataset** (`Retail_Transactions_2000.csv`).  
It covers **data cleaning, preprocessing, encoding, scaling, and visualization** to extract meaningful insights about customer demographics, sales patterns, and purchasing behavior.  

---

## ⚙️ Steps Performed  

### 🔹 1. Data Cleaning  
- Removed invalid entries (Age ≤ 0, Price ≤ 0, etc.)  
- Handled **outliers** using IQR method.  
- Converted `PurchaseDate` into **Year, Month, Day** features.  
- Grouped `Age` into **Age Groups** (`<18`, `18-25`, `26-40`, `41-60`, `60+`).  
- Encoded categorical features (**Gender, City**) using `LabelEncoder`.  
- Scaled numerical features (**Age, Price, TotalAmount**) using `MinMaxScaler`.  
- Exported cleaned dataset → `Retail_Cleaned.csv`.  

---

### 🔹 2. Visualizations (All Plots 🖼️)  

> Each visualization is generated individually (✅ no subplots).  

1. **Age Distribution of Customers**  
   - KDE Plot of Age 

2. **Gender Distribution**  
   - Bar chart of Male vs Female customers 

3. **Top 10 Cities by Customers**  
   - Bar chart showing highest customer count  

4. **Total Sales by Product Category**  
   - Bar chart of revenue by product category  

5. **Monthly Sales Trend**  
   - Line chart (with markers) showing month-wise sales  

6. **Payment Method Distribution**  
   - Pie chart of payments (Cash, Card, UPI, Wallet, etc.)  

7. **Average Spend per Customer by Age Group**  
   - Bar chart comparing spending power across age groups  

8. **City-wise Revenue Contribution**  
   - Bar chart showing contribution of each city  

9. **Purchase Behavior Heatmap**  
   - Heatmap (Product Category vs Payment Mode)  

---

## 🛠️ Tech Stack  
- **Python** 🐍  
- **Pandas, NumPy** → Data processing  
- **Matplotlib, Seaborn** → Data visualization  
- **Scikit-learn** → Label Encoding & Scaling  

---

## 🚀 How to Run  
1. Clone this repo / download notebook.  
2. Place `Retail_Transactions_2000.csv` in the same folder.  
3. Run the notebook step by step.  
4. Cleaned data will be saved as **Retail_Cleaned.csv**.  
5. All plots will be displayed individually.  

---

## 📊 Insights  
- Younger customers (18–25) form the largest buyer segment.  
- Certain cities dominate sales contribution.  
- Payment preferences vary by product category.  
- Spending increases with age until middle-age, then declines.  
