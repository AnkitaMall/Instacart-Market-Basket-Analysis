# 🛒 Instacart Market Basket Analysis

## 📌 Objective
The goal of this project is to analyze customer purchase behavior on the Instacart platform and uncover product associations using Market Basket Analysis (Association Rules). The insights help in understanding buying patterns, optimizing product placements, and creating effective cross-selling strategies.

---

## 📂 Dataset Source
The dataset was obtained from the **[Instacart Online Grocery Shopping Dataset 2017](https://www.kaggle.com/code/viveksrinivasan/eda-on-instacart-market-basket-analysis)**, which contains over 3 million orders from more than 200,000 Instacart users.  
Key tables include:
- **Orders**: Order details with day/time of purchase
- **Products**: Product names and categories
- **Departments & Aisles**: Product classification
- **Order-Products**: Mapping of products to orders

---

## 🛠 Technologies Used
- **Python** (Data Cleaning, EDA, Association Rules using `mlxtend`)
- **Pandas** & **NumPy** (Data manipulation)
- **Matplotlib** & **Seaborn** (Visualization during EDA)
- **Power BI** (Interactive dashboard creation)
- **Apriori Algorithm** (Frequent itemset mining)
- **Association Rule Mining** (Support, Confidence, Lift metrics)

---

## 📊 Key Insights

### **1. Order Behavior**
- Peak ordering occurs between **9 AM and 4 PM**, with a sharp drop after evening.
- Most orders are placed during the **first half of the week**.

### **2. Popular Products**
- **Banana** and **Bag of Organic Bananas** are the top-selling products.
- Fresh produce dominates the best-selling list.

### **3. Basket Size**
- Most customers purchase **3–9 items** per order.
- Average items per order: **10.03**

### **4. Reorder Trends**
- Highest reorder rates are seen in **Dairy & Eggs** (0.67) and **Beverages** (0.66).

### **5. Association Rules**
- Strongest rule:  
  **Organic Raspberries → Organic Strawberries** with a lift of **2.14**.  
  Customers buying organic raspberries are highly likely to also buy organic strawberries.
- Bundling opportunities exist between fresh produce and specific fruits.
  
---


## 🚀 How to Use
1. **Clone the repository**
   ```bash
   git clone https://github.com/AnkitaMall/instacart-market-basket-analysis.git

