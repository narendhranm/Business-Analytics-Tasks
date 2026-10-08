# Business Category Analysis Using Bubble Chart

## 📊 Project Overview

This project analyzes and compares different business categories using a **Bubble Chart** in **Tableau Public**.

A business-related dataset containing categorical and numerical fields was used to identify the most significant and least significant business categories based on **Sales, Profit, Quantity, and time-based performance**.

The analysis combines multiple visualizations into an interactive Tableau dashboard to provide useful business insights and recommendations.

---

## 🎯 Objective

To analyze and compare different business categories using a Bubble Chart and identify the most and least significant categories based on business performance.

---

## 📌 Problem Statement

Select a business-related dataset containing categorical information and numerical measures such as:

* Sales
* Revenue
* Profit
* Quantity
* Orders
* Customers

Using **Tableau Public**, create a Bubble Chart to compare business categories and identify important trends and performance differences.

---

## 🗂️ Dataset

### Dataset Used

**Superstore Sales Dataset**

### Source

Kaggle

### Important Fields Used

| Field        | Data Type   | Purpose                                 |
| ------------ | ----------- | --------------------------------------- |
| Category     | Categorical | Business category                       |
| Sub-Category | Categorical | Product-level category                  |
| Sales        | Numerical   | Bubble size and sales analysis          |
| Profit       | Numerical   | Bubble color and profitability analysis |
| Quantity     | Numerical   | Quantity analysis                       |
| Order Date   | Date        | Time-based analysis                     |
| Region       | Categorical | Interactive filter                      |
| Segment      | Categorical | Customer segmentation                   |

---

## 🛠️ Tools & Technologies

* **Tableau Public**
* **Kaggle**
* **Microsoft Excel / CSV**
* Data Visualization
* Business Analytics

---

## 📈 Visualizations Created

### 1. Bubble Chart – Sales & Profit by Sub-Category

The main visualization of the project.

**Configuration:**

* **Bubble Size:** Sales
* **Bubble Color:** Profit
* **Bubble Label:** Sub-Category
* **Detail:** Category

The Bubble Chart helps identify high-sales and low-sales sub-categories while simultaneously comparing their profitability.

---

### 2. Sales by Category

A bar chart was created to compare total sales across different business categories.

**Fields used:**

* Columns → Category
* Rows → Sales

This visualization helps identify which categories contribute the most to total sales.

---

### 3. Monthly Sales Trend

A line chart was created to analyze sales performance over time.

**Fields used:**

* Columns → Order Date
* Rows → Sales

This visualization helps identify changes and trends in business sales over different periods.

---

### 4. Profit by Category

A bar chart was created to compare profitability across different categories.

**Fields used:**

* Columns → Category
* Rows → Profit
* Color → Profit

This helps identify categories generating higher and lower profits.

---

## 🎛️ Interactive Filter

### Region Filter

A **Region** filter was added to the dashboard.

Users can select:

* Central
* East
* South
* West

The filter allows users to analyze business performance for individual regions.

The dashboard also supports interactive selection from the Bubble Chart to explore related visualizations.

---

## 📊 Dashboard

All visualizations were combined into a single interactive dashboard called:

### **Business Category Performance Analysis**

The dashboard contains:

* Bubble Chart
* Sales by Category
* Monthly Sales Trend
* Profit by Category
* Region Filter

The dashboard provides a consolidated view of business performance and allows users to interactively explore the data.

---

## 🔍 Bubble Chart Analysis

The Bubble Chart provides three major dimensions of analysis:

### Bubble Size

Bubble size represents **Sales**.

* Large bubble → High sales
* Small bubble → Low sales

### Bubble Color

Bubble color represents **Profit**.

This allows profitable and less-profitable sub-categories to be compared easily.

### Category

The Category field groups the different sub-categories and allows comparison between major business categories.

---

## 💡 Business Insights

### 1. High-Sales Sub-Categories

The Bubble Chart identifies the sub-categories that contribute the most to overall sales. These products are important contributors to business revenue.

### 2. Sales and Profit Are Not Always the Same

Some products may generate high sales but comparatively lower profit. This indicates that revenue alone should not be used to evaluate business performance.

### 3. Category Performance Varies

The Sales by Category visualization shows that different product categories contribute differently to total business sales.

### 4. Sales Change Over Time

The Monthly Sales Trend helps identify periods of increasing and decreasing sales performance and provides a better understanding of business trends.

### 5. Regional Performance Differs

The Region filter allows users to compare business performance across different regions and identify areas where specific categories or products perform better.

---

## 💼 Business Recommendations

### Recommendation 1 – Focus on Profitable Products

The business should prioritize high-sales and high-profit sub-categories by maintaining adequate inventory and applying targeted marketing strategies.

### Recommendation 2 – Improve Low-Profit Products

Products with high sales but relatively low profit should be investigated. The company should review pricing, discounts, shipping costs, and product costs to improve profitability.

---

## 📋 Project Requirements Completed

| Requirement                           | Status      |
| ------------------------------------- | ----------- |
| Download business dataset from Kaggle | ✅ Completed |
| Import dataset into Tableau Public    | ✅ Completed |
| Identify categorical fields           | ✅ Completed |
| Identify numerical fields             | ✅ Completed |
| Create Bubble Chart                   | ✅ Completed |
| Create 3 additional visualizations    | ✅ Completed |
| Add interactive filter                | ✅ Completed |
| Combine visualizations into dashboard | ✅ Completed |
| Analyze Bubble Chart                  | ✅ Completed |
| Write 5 business insights             | ✅ Completed |
| Provide 2 business recommendations    | ✅ Completed |

---

## 📁 Project Structure

```text
Business-Category-Bubble-Chart/
│
├── README.md
│
├── Dataset/
│   └── Superstore_Sales.xlsx
│
├── Tableau/
│   └── Business_Category_Analysis.twbx
│
└── Screenshots/
    └── dashboard.png
```

---

## 📸 Dashboard Preview

Add your Tableau dashboard screenshot here:

```markdown
![Business Category Analysis Dashboard](Screenshots/dashboard.png)
```

---

## 🔗 Tableau Public

Add your published Tableau Public dashboard link here:

**Tableau Public:**
[`YOUR_TABLEAU_PUBLIC_LINK`](https://public.tableau.com/views/task-11_17914390678050/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 👨‍💻 Author

**Naren M**

Business Analytics | Data Visualization | Tableau

---

## ⭐ Conclusion

This project demonstrates how Tableau Public can be used to analyze business performance through interactive data visualization.

The Bubble Chart provides a clear comparison of **Sales and Profit across product sub-categories**, while the supporting visualizations provide additional insights into category performance, sales trends, and profitability.

The interactive dashboard enables users to explore the data by region and supports better data-driven business decision-making.

