# 🛒 Blinkit Python Project

This project showcases an in-depth **Data Analysis of Blinkit (formerly Grofers)** using Python. The goal is to uncover meaningful insights from sales data, product types, outlet performance, and customer preferences using visual storytelling.

---

## 📂 Dataset Overview

- **Source**: `blinkit_data.csv`
- **Total Records**: 8,523
- **Columns**: 12
- **Includes**:
  - Product details (item type, fat content, weight, rating)
  - Sales performance
  - Outlet information (location, size, type, year of establishment)

---

## 📊 Project Workflow

1. **📦 Importing Libraries**
   - Pandas, NumPy, Seaborn, Matplotlib

2. **📥 Data Loading & Initial Exploration**
   - Checked structure, shape, column types, and sample values

3. **🧹 Data Cleaning**
   - Standardized fat content values (e.g., `LF` → `Low Fat`)
   - Handled missing and duplicate records

4. **📌 KPI Analysis**
   - Total sales, average sales, item count, and average customer rating

5. **📈 Visual Insights**
   - Generated 6 key business performance charts

---

## 💡 Key Performance Indicators (KPIs)

- 🧾 **Total Sales**: $1,201,681  
- 📦 **Average Sales**: $141 per product  
- 🔢 **Unique Items Sold**: 1,559  
- ⭐ **Average Rating**: 4.0

---

## 📊 Key Charts & Business Questions

1. **Donut Chart: Total Sales by Fat Content**  
   Shows sales contribution from `Low Fat` vs `Regular` items

2. **Bar Plot: Total Sales by Item Type**  
   Highlights the most and least sold product categories

3. **Grouped Bar Chart: Fat Content vs City Tier**  
   Compares sales in Tier 1, 2, and 3 cities based on fat content

4. **Line Chart: Sales by Outlet Establishment Year**  
   Reveals how older outlets perform over the years

5. **Pie Chart: Sales by Outlet Size**  
   Analyzes contribution of Small, Medium, and High outlets

6. **Funnel Chart: Sales by Outlet Location Type**  
   Assesses regional performance across outlet types

---

## 🛠 Technologies Used

- **Python 3**
- **Pandas** for data manipulation
- **Seaborn** & **Matplotlib** for visualization
- **Jupyter Notebook** for code execution and EDA

---

## 🚀 How to Run This Project

1. Clone this repository:
   ```bash
   git clone https://github.com/Analyst-Rajat333/Blinkit-Python-Project.git

![total_sales_by_item_type](https://github.com/user-attachments/assets/4cf12a36-1f87-41f2-bd77-6adaa43fe98f)
![total_sales_by_fat_content](https://github.com/user-attachments/assets/aa5eeaaf-7d8e-4f47-a97e-c18ba2f6995d)
![total_sales_by_establishment_year](https://github.com/user-attachments/assets/9b6776a8-27e5-4742-a880-0d12ed736828)
![sales_by_outlet_size_donut](https://github.com/user-attachments/assets/ea70f54d-d5d8-41b7-85d8-ca7d9a7f5c12)
![sales_by_location_funnel](https://github.com/user-attachments/assets/d0fea311-ac2e-43f0-bb34-40955166b492)
![grouped_fat_sales_by_city_tier](https://github.com/user-attachments/assets/bae53669-d493-4624-8542-4db2a6db4492)
