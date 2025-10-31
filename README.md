# 🧠 Customer Behavior - Data Analytics Project
---
## 📄 Overview

This project demonstrates the complete **data analytics workflow** — from data loading and cleaning to visualization and reporting.
It covers the process of exploring, transforming, and analyzing data using **Python**, **PostgreSQL**, and **Power BI**, followed by insights presentation using **Gamma**.

The main goal of this project is to uncover valuable insights from the dataset and communicate them effectively through interactive dashboards and reports.

---

## 📊 Dataset

* **Format:** CSV
* **Size:** [3900 rows & 18 columns]
* **Description:**
  The dataset contains information about [customer behavior, sales transactions, or employee performance].
  Each record includes fields such as [Customer ID, Age, Gender, Item Purchased, Category, Purchase Amount, Location, Size, Color, Season, Review Rating, Subscription Status, Shipping Type, Discount Applied, Promo Code Used, Previous Purchases Payment method, Frequency of Purchase.].

---

## 🧰 Tools & Technologies

| Tool / Technology                               | Purpose                                         |
| ----------------------------------------------- | ----------------------------------------------- |
| **Python (Pandas)**                             | Data loading, exploration, and cleaning         |
| **PostgreSQL**                                  | Running SQL queries for deeper analysis         |
| **Power BI**                                    | Building the dashboard and visualizing insights |
| **Gamma App**                                   | Creating a presentation report                  |
| **Jupyter Notebook**                            | Coding and documentation                        |

---

## ⚙️ Steps & Workflow

1. **Data Loading**

   * Imported the dataset using Python.
   * Checked for missing values and duplicates.

2. **Exploratory Data Analysis (EDA)**

   * Analyzed data distributions and summary statistics.

3. **Data Cleaning**

   * Handled null values and outliers.
   * Standardized column names and data formats.

4. **SQL Analysis**

   * Imported cleaned data into PostgreSQL.
   * Executed analytical queries to extract key insights.

5. **Dashboard Creation (Power BI)**

   * Connected Power BI to PostgreSQL.
   * Designed an interactive dashboard with key KPIs and visuals.

6. **Reporting & Presentation**

   * Summarized insights and findings in a **Gamma** presentation.
   * Highlighted business implications and recommendations.

---

## 📈 Dashboard

The Power BI dashboard includes:

* KPI cards for quick metrics overview
* Trend and category-based visualizations
* Filters and slicers for interactivity

![Dashboard Preview](image/dashboard.png)

---

## ✅ Results & Insights

Key findings from the analysis:

* [Example: Sales peaked in Q3 due to promotional campaigns.]
* [Example: 25% of customers contribute to 70% of total revenue.]
* [Example: Employee churn is higher among specific departments.]

The results provide actionable insights that can help drive data-driven decisions.

---

## 💻 How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Code-Sleek/Customer-Behavior-Analysis.git
   ```
2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```
3. **Run the notebook:**

   * Open `Customer_Shopping_Behavior_Analysis.ipynb` in Jupyter or VS Code.
   * Execute cells step by step.
4. **Set up PostgreSQL:**

   * Create a new database.
   * Import the cleaned dataset (`cleaned_data.csv`).
   * Run the SQL queries in `queries.sql`.
5. **Power BI:**

   * Open the `.pbix` file to view the dashboard.
6. **Report:**

   * Access the Gamma report and presentation in folder reports.

---

## 📂 Project Structure

```
├── data/
│   ├── raw_dataset.csv
│   ├── cleaned_data.csv
├── image/
│   ├── dashboard.png
├── notebooks/
│   ├── Customer_Shopping_Behavior_Analysis.ipynb
├── sql/
│   ├── Customer_Behavior.sql
├── powerbi/
│   ├── Customer Shopping Behavior Dashboard.pbix
├── report/
│   ├── Customer Shopping Behavior Analysis Report.pdf
│   ├── Customer-Shopping-Behavior-Analysis.pptx
├── README.md
└── Business Problem Document.pdf
```

---

## 🙌 Acknowledgments

* Special thanks to [Amlan Mohanty](https://www.youtube.com/@amlanmohanty1) for providing us with this project idea.
* Tools and libraries used are open-source and freely available.
