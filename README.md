# 📊 Exploratory Data Analysis - Retail (The Sparks Foundation)

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Data Science](https://img.shields.io/badge/Data%20Science-EDA-orange)
![The Sparks Foundation](https://img.shields.io/badge/The%20Sparks%20Foundation-Task%203-brightgreen)

## 📈 Visual Overview
<div align="center">
  <img src="https://github.com/sameerhussai230/Exploratory_Data_Analysis_Spark_Foundation/raw/main/EDA_Visual.gif" alt="EDA Visuals" width="800">
</div>

## 📝 Project Overview
This project is **Task 3: Exploratory Data Analysis - Retail** for the Data Science & Business Analytics Internship at **The Sparks Foundation**. 

The objective of this project is to perform Exploratory Data Analysis (EDA) on the `SampleSuperstore` dataset. As a business manager, the goal is to discover weak areas where the company can work to make more profit and derive crucial business insights through data visualization.

## 🔗 Quick Links
* **Dataset:** [SampleSuperstore.csv](https://github.com/sameerhussai230/Exploratory_Data_Analysis_Spark_Foundation/blob/main/SampleSuperstore.csv)
* **Jupyter Notebook:** [Exploratory_Data_Analysis_Spark_Foundation.ipynb](https://github.com/sameerhussai230/Exploratory_Data_Analysis_Spark_Foundation/blob/main/Exploratory_Data_Analysis_Spark_Foundation.ipynb)
* **Project Report:** [PDF Presentation](https://github.com/sameerhussai230/Exploratory_Data_Analysis_Spark_Foundation/blob/main/Exploratory_Data_Analysis_Spark_Foundation.pdf)
* **Video Walkthrough:** [Project Presentation (MP4)](https://github.com/sameerhussai230/Exploratory_Data_Analysis_Spark_Foundation/blob/main/Exploratory_Data_Analysis_Spark_Foundation.mp4)
* **Visuals Overview:** [EDA_Visuals.gif](https://github.com/sameerhussai230/Exploratory_Data_Analysis_Spark_Foundation/blob/main/EDA_Visuals.gif)

## 🛠️ Tools & Libraries Used
* **Python** (Data Manipulation & Analysis)
* **Pandas & NumPy** (Data Cleaning & Structuring)
* **Matplotlib & Seaborn** (Data Visualization)
* **Squarify** (Treemap Visualizations)
* **Plotnine** (ggplot for Python)

## 📂 Project Workflow
1. **Data Importing:** Loading the dataset and necessary libraries.
2. **Data Cleaning:** Checking for null values, handling missing data, identifying and dropping duplicate records, and removing irrelevant columns (e.g., `Postal Code`).
3. **Exploratory Data Analysis (EDA):**
   * **Category & Sub-Category Analysis:** Analyzing distributions, total sales, profit/loss across sub-categories, and average metrics.
   * **Regional & State/City Analysis:** Geographical mapping of orders, top 10 performing states & cities, and segment-wise heatmap tracking.

## 💡 Key Business Insights

### 1. Category & Sub-Category Performance
* **Most & Least Profitable:** The **Technology** category generates the highest Sales and Profit, while **Office Supplies** generates the lowest. 
* **Discounts:** Technology products offer the highest discount rates, which highly contributes to their leading sales volume.
* **Volume Leaders:** **Binders** have the highest quantity sold, followed by Papers and Furnishings.

### 2. Regional & Segment Performance
* **Top Region:** The **West Region** dominates and brings in the maximum total sales across all categories.
* **Weakest Region:** The **South Region** has the lowest sales volumes across all categories.
* **Segment Trends:** The **Consumer** segment leads the charts in both the West and East regions. Conversely, the **Home Office** segment records the lowest sales across all four regions.

### 3. Geographical Performance
* **Top States Overall:** **California** is the absolute leader in both Profit and Sales, followed closely by New York and Washington.
* **State-Category Dominance:** 
  * **California** is the most profitable state for *Furniture* and *Office Supplies*.
  * **New York** takes the lead as the most profitable state for the *Technology* category.
* *Note:* State ranking by profit does not perfectly align with the ranking by sales, indicating that high sales volume does not automatically guarantee high profit (likely due to varied discount strategies).

## 🚀 Conclusion & Recommendations
To maximize profitability, the business should:
1. **Re-evaluate discount strategies**, especially in the **Office Supplies** and **Furniture** categories, to prevent revenue leakage.
2. **Focus marketing and expansion efforts** on the **South Region** and the **Home Office** segment to boost their underperforming numbers.
3. **Keep leveraging** the high-performing **Technology** category while optimizing its discount margins to ensure maximum returns.
