
# SuperSave Market Data Analysis

## 📌 Overview

This project analyzes product and sales data for **SuperSave Market**, a rapidly growing supermarket chain.
It combines multiple datasets, cleans and prepares the data, performs exploratory and statistical analysis, and generates actionable insights to improve inventory management, pricing, and promotions.

The analysis is structured as a series of tasks, each building toward a complete analytical workflow.

---

## 📂 Data Sources

1. **`product_catalog.csv`** – Product-level details, including category, name, and pricing.
2. **`inventory_sales.csv`** – Inventory and sales performance data, including quantities sold, prices, and customer ratings.

---

## 🛠 Project Tasks

1. **Data Merging** – Join product catalog and inventory datasets to create a complete view of product information and sales.

   * Handles missing products in either dataset.
   * Ensures all products are represented in the merged dataset.

2. **Handling Missing Data & Feature Engineering** –

   * Fill missing prices and ratings with appropriate methods.
   * Create new derived columns, such as total revenue and sales performance indicators.

3. **Exploratory Data Analysis (EDA)** –

   * Summary statistics for sales, prices, and ratings.
   * Identify top-performing products and categories.
   * Detect inventory issues and underperforming SKUs.

4. **Hypothesis Testing** –

   * Test assumptions about customer behavior (e.g., ratings vs. sales, price sensitivity).
   * Apply statistical methods such as t-tests or correlation analysis.

5. **Scenario Analysis** –

   * Simulate the impact of changes in price or promotions on revenue and sales volume.

6. **Visualization** –

   * Use Python plotting libraries to visualize trends in sales, inventory, and customer ratings.

---

## 📊 Example Insights

* Products with **high ratings** may not always have **high sales volume**, indicating potential for targeted marketing.
* Certain categories have **consistently higher margins**, suggesting a focus for promotional efforts.
* Price adjustments show varying impacts depending on category elasticity.

---

## 🚀 How to Run

1. Install dependencies:
pip install matplotlib
pip install numpy
pip install pandas
2. Place `product_catalog.csv` and `inventory_sales.csv` in the project folder.
3. Run the Jupyter Notebook:


---

## 📦 Outputs

* **Merged dataset** combining product and sales data
* **Cleaned dataset** with engineered features
* **Summary tables** for sales performance
* **Statistical test results**
* **Scenario simulation results**
* **Data visualizations**

---

## 📜 License

This project is for educational purposes and may be adapted for real-world analysis.

---

