# Swiggy-Sales-Analysis-Dashboard-using-PowerBI

## 📌 Project Overview

This project is part of my **Data Science & Analytics Internship at Future Interns**.
The objective of this task is to analyze e-commerce sales data and build an **interactive Power BI dashboard** that provides actionable business insights such as sales trends, best-selling products, and high-revenue categories.

The dashboard helps stakeholders make informed decisions by visualizing key performance metrics in a simple and intuitive format.

---

## 🎯 Objectives

* Analyze e-commerce sales data
* Identify **best-selling products**
* Understand **monthly and daily sales trends**
* Identify **high-revenue cities and categories**
* Build an interactive dashboard for business decision-making

---

## 🛠 Tools & Technologies Used

* **Power BI**
* **DAX (Data Analysis Expressions)**
* **Microsoft Excel (for data cleaning)**
* Data Visualization & Business Intelligence concepts

---

## 📂 Dataset Description

The dataset contains transactional e-commerce data with the following attributes:

* Order Date
* Dish Name
* Restaurant Name
* City / State
* Food Type (Veg / Non-Veg)
* Price (INR)
* Rating
* Rating Count
* Day / Week / Month

---

## 📈 Key Metrics (KPIs)

The dashboard includes the following KPIs:

* **Total Sales**
* **Total Orders**
* **Average Order Value**
* **Average Rating**
* **Rating Count**

---

## 📊 Dashboard Features

### 🔹 Sales Trends

* Monthly sales trend
* Daily sales trend

### 🔹 Product & Category Insights

* Best-selling dishes
* Revenue by food type (Veg vs Non-Veg)
* Top cities by total sales
* Top restaurants by revenue

### 🔹 Interactivity

* Slicers for:

  * State
  * Month
  * Restaurant Name
* Dynamic filtering across all visuals

---

## 🧮 DAX Measures Used (Examples)

```DAX
Total Sales = SUM('Swiggy Data'[Price (INR)])

Total Orders = COUNT('Swiggy Data'[Dish Name])

Average Order Value = 
DIVIDE([Total Sales], [Total Orders])

Average Rating = AVERAGE('Swiggy Data'[Rating])
```

---

## 📌 Key Business Insights

* Non-veg items contribute a higher share of total revenue.
* Certain cities consistently generate higher sales volumes.
* A small number of dishes contribute significantly to overall revenue.
* Sales show noticeable variation across days and months.
* Customer ratings indicate generally high satisfaction.

---

## 📷 Dashboard Preview

*(Add your dashboard screenshot here)*

```
/images/dashboard.png
```

---

## 🚀 Learnings & Skills Gained

* Data cleaning and preparation
* Writing DAX measures
* Trend and category analysis
* Business storytelling using dashboards
* Designing professional Power BI reports
* Understanding real-world e-commerce KPIs

---

## 📎 Project Status

✅ Completed — Task 1 of Data Science & Analytics Internship at **Future Interns**

---

## 🤝 Connect With Me

If you’d like to collaborate or provide feedback, feel free to connect with me on LinkedIn.

📌 **Author:** Shiva Panibhate
📌 **Role:** Data Science & Analytics Intern

---

### ⭐ If you found this project useful, feel free to give it a star!

---

If you want, I can also:

* ✅ Customize this README to look more **GitHub-professional**
* ✅ Add badges (Power BI, Data Analytics, Internship)
* ✅ Help you structure your GitHub repo folders
* ✅ Write a **resume-ready project description**
* ✅ Help with interview explanations based on this project

Just tell me what you want next 👍
