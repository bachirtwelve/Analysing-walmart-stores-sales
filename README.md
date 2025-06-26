# Analysing-walmart-stores-sales
An advanced Power BI dashboard analyzing sales from 45 Walmart stores. This interactive tool uncovers insights on store performance, holiday impact, and correlations with external factors like temperature and economic indicators, enabling data-driven decisions for business leaders.
# Advanced Walmart Sales Analysis Dashboard

## 🎯 Project Description

This project features an advanced analytics dashboard built with **Microsoft Power BI** to dissect historical sales data from 45 Walmart stores. The primary goal is to move beyond simple sales reporting and uncover deeper insights into the factors that influence revenue. The analysis investigates correlations between sales and external factors like temperature and economic indicators, evaluates store-level performance, and quantifies the impact of holiday periods.

The dashboard is designed to be a powerful, interactive tool for business leaders to explore data dynamically, identify patterns, and make data-driven decisions.

---

## 🚀 Interactive Dashboard

Click the image below to open and interact with the live Power BI report. The dashboard is fully interactive, allowing for filtering and cross-highlighting across all visuals.

*Please note: The report is publicly published via Power BI's "Publish to web" feature for portfolio demonstration purposes.*

[![Walmart Sales Dashboard Preview](https://i.imgur.com/uRmiZ8u.png)](https://app.powerbi.com/view?r=YOUR_PUBLIC_POWER_BI_LINK_HERE)

> **Note:** Replace `YOUR_PUBLIC_POWER_BI_LINK_HERE` with the actual public link you generated from the Power BI service. You should also replace the preview image `https://i.imgur.com/uRmiZ8u.png` with a path to your own dashboard's screenshot that you've uploaded to the repository.

---

## ❓ Key Questions Addressed

This dashboard provides clear, data-backed answers to critical business questions through a series of targeted visualizations:

#### **1. What is the overall sales performance and its components?**
* **Answer (from KPI Cards):**
    * The dashboard leads with high-level Key Performance Indicators (KPIs). Dedicated cards for `Total Sales`, `Sales on Holiday Weeks`, and `Sales on Non-Holiday Weeks` provide an immediate and clear breakdown of primary revenue streams.

#### **2. How do individual stores perform against each other?**
* **Answer (from the Bar Chart & Scroller Visual):**
    * A detailed bar chart ranks each store by its weekly sales, making it easy to identify top and bottom performers.
    * This is supplemented by a dynamic scroller visual that displays a live-style feed of sales for each store, offering a continuous and engaging view of store-level performance.

#### **3. Is there a direct correlation between temperature and weekly sales?**
* **Answer (from the Scatter Plot & Combo Line Chart):**
    * A **scatter plot** is used to directly visualize the relationship between `Temperature` and `Weekly Sales`, helping to identify any positive, negative, or non-existent correlation.
    * A **combo line chart** tracks both `Average Temperature` and `Weekly Sales` over time, allowing for an analysis of how seasonal weather trends might influence customer shopping behavior throughout the year.

#### **4. What are the prevailing economic trends affecting sales?**
* **Answer (from the CPI Line Chart & Unemployment Card):**
    * A dedicated line chart tracks the **monthly trend of the Average CPI**, providing a clear visualization of inflation over time.
    * A KPI card prominently displays the latest **Unemployment Rate**, giving stakeholders a quick snapshot of the broader economic environment that could impact consumer confidence and spending.

#### **5. How is performance analyzed at a granular level?**
* **Answer (from Interactive Slicers):**
    * The dashboard's true power lies in its interactivity. Users can dynamically filter the entire report using **slicers for Store, Year, and Month**. This allows for deep-dive investigations, such as analyzing a single store's performance in a specific month or comparing holiday sales across different years.

---

## 🛠️ Dashboard Features & Technologies

* **Primary Tool:** Microsoft Power BI
* **Visualizations Used:**
    * **KPI Cards:** For high-level metrics (`Total Sales`, `Holiday Sales`, `Unemployment`, etc.).
    * **Bar & Scatter Plots:** For correlation and ranking analysis.
    * **Line & Combo Charts:** For trend analysis over time (Sales vs. Temperature, CPI trend).
    * **Custom Scroller/Ticker Visual:** For a dynamic display of store-level data.
* **Analysis Language:** DAX (Data Analysis Expressions)
    * DAX was used to create the specific measures required for
