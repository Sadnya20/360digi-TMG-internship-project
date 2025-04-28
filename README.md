
# Medical Inventory Optimization  
*(By Sadnya Kolhe)*

![image](https://github.com/user-attachments/assets/51db2431-97b4-4c28-a5f9-6120a3258fee)

## 📄 Project Overview
This project focuses on **optimizing medical inventory** by analyzing historical sales and return data using Python libraries such as **pandas**, **matplotlib**, and **seaborn**.  
We explore patterns in **quantity sold**, **returns**, **final costs**, and **sales** to derive business insights that can help maximize profits and streamline inventory management.

---

## 📂 Files and Resources
- `new.csv`: Dataset containing information about sales, returns, costs, and more.
- Python notebook/code used for data visualization and analysis.
- Business insights derived from the dataset analysis.

---

## 🔧 Tools & Libraries Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Project Steps

### 1. Data Import and Setup
- Mounted Google Drive.
- Imported the dataset using **pandas**.
- Installed required libraries.

### 2. Data Visualization
- **Histogram** for analyzing distribution of:
  - `Quantity`
  - `ReturnQuantity`
- **Scatter Plots** to study relationships between:
  - `Quantity` vs `ReturnQuantity`
  - `Final_Cost` vs `Final_Sales`
- **Boxplots** to understand:
  - Relationship between `Quantity` and `ReturnQuantity`
  - Relation between `Final_Sales` and `Final_Cost`
- **Pairplot** to visualize multi-variable relationships:
  - Between `Final_Cost`, `Final_Sales`, and `RtnMRP` (Returned MRP)

### 3. Business Insights
- Found **12,525 null values** that need to be handled (preferably deleted to avoid complications).
- Observed that **Final_Cost** range suggests a possibility to **increase profits by 25%** with better inventory and pricing strategies.
- Pairplots provide a comprehensive overview of the relationship between sales, cost, and returns, allowing for better business decision-making.

---

## 📈 Key Outcomes
- Identified data quality issues (null values).
- Found ways to potentially **increase profitability**.
- Visualized key relationships influencing sales performance.
- Provided a basis for **better inventory management decisions**.

---

## 🚀 Future Scope
- Handle missing values using advanced imputation techniques.
- Perform predictive modeling to forecast sales and returns.
- Build a complete inventory optimization system with **machine learning models**.

---

## 🤝 Acknowledgements
Project researched and created by **Sadnya Kolhe** using SQL, Python, and various visualization techniques.

---
