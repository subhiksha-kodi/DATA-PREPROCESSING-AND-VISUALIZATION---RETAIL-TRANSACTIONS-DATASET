# 🛒 Retail Transactions Data Analysis  

## 📌 Project Overview  
This project analyzes a **retail transactions dataset** (`Retail_Transactions_2000.csv`).  
It covers **data cleaning, preprocessing, encoding, scaling, and visualization** to extract meaningful insights about customer demographics, sales patterns, and purchasing behavior.  

---

## ⚙️ Steps Performed  

### 🔹 1. Data Cleaning  
- Removed invalid entries (`Age ≤ 0`, `Price ≤ 0`, etc.)  
- Handled **outliers** using the **IQR method**  
- Converted `PurchaseDate` into **Year, Month, Day** features  
- Grouped `Age` into **Age Groups** (`<18`, `18–25`, `26–40`, `41–60`, `60+`)  
- Encoded categorical features (**Gender, City**) using `LabelEncoder`  
- Scaled numerical features (**Age, Price, TotalAmount**) using `MinMaxScaler`  
- Exported cleaned dataset → `Retail_Cleaned.csv`  

---

### 🔹 2. Visualizations (All Plots 🖼️)   

1. **Age Distribution of Customers**  
   - KDE Plot of Age  
   ![Age Distribution](https://github.com/user-attachments/assets/c55b6c80-e544-4623-8b80-6083ead25513)  

2. **Gender Distribution**  
   - Bar chart of Male vs Female customers  
   ![Gender Distribution](https://github.com/user-attachments/assets/68f9b8c3-d260-48e8-8146-7a3f0f59d435)  

3. **Top 10 Cities by Customers**  
   - Bar chart showing highest customer count  
   ![Top Cities](https://github.com/user-attachments/assets/d0af2164-0d85-42ab-a054-38bed7075874)  

4. **Total Sales by Product Category**  
   - Bar chart of revenue by product category  
   ![Sales by Category](https://github.com/user-attachments/assets/27257014-4544-47b1-81bb-4f9da5bffa4d)  

5. **Monthly Sales Trend**  
   - Line chart (with markers) showing month-wise sales  
   ![Monthly Sales](https://github.com/user-attachments/assets/c80388e3-74bb-465c-886d-aad9b1414d97)  

6. **Payment Method Distribution**  
   - Pie chart of payments (Cash, Card, UPI, Wallet, etc.)  
   ![Payment Methods](https://github.com/user-attachments/assets/b67575a6-91ad-4d40-90a3-11aaae2e72cd)  

7. **Average Spend per Customer by Age Group**  
   - Bar chart comparing spending power across age groups  
   ![Spend by Age Group](https://github.com/user-attachments/assets/591d62a7-74ed-454b-b865-c1d27f22708a)  

8. **City-wise Revenue Contribution**  
   - Bar chart showing contribution of each city  
   ![City Revenue](https://github.com/user-attachments/assets/1c483c4b-acba-4c14-bc05-1d9fa394bc3f)  

9. **Purchase Behavior Heatmap**  
   - Heatmap (Product Category vs Payment Mode)  
   ![Purchase Heatmap](https://github.com/user-attachments/assets/105af751-7417-4e09-a2dd-c9aaf6e246e6)  

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
- Younger customers (**18–25**) form the **largest buyer segment**  
- Certain **cities dominate sales contribution**  
- **Payment preferences** vary by product category  
- **Spending increases** with age until middle-age, then declines  

---
