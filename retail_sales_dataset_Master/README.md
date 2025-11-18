# Excel-Sales-Dataset-Analysis

This document provides an overview of the data analysis capabilities and features implemented within this Excel file, which contains various datasets (such as retail sales and student scores).

***

## 1. File Structure & Included Data

The workbook is structured into several sheets, typically including:
* **Source Data:** Sheets containing the raw, transactional data (e.g., `retail_sales_dataset`, `Transactions`).
* **Analytic Sheets:** Sheets dedicated to calculations and specific tasks (e.g., `Day 2 Task 2`).
* **Summary Sheets:** Sheets containing aggregated results and visualizations (e.g., `Pivot Table`, `Sheet2`, `Sheet3`).

***

## 2. Key Analysis Features

This section details the functions and tools used to process and analyze the data:

### 📊 Calculation & Aggregation Functions

| Function | Description | Typical Application |
| :--- | :--- | :--- |
| **SUM** | Calculates the total sum of values in a range. | Calculating **Total Sales** or overall scores. |
| **AVERAGE** | Calculates the arithmetic mean of a range of numbers. | Determining the **Average** unit price or student score. |
| **SUMIF** | Calculates the sum of values that meet a single, specified condition. | Summing sales for a specific **Product Category** or Region. |
| **AVERAGEIF** | Calculates the average of values that meet a single, specified condition. | Finding the average score for only **Female** students or sales in a specific year. |
| **VLOOKUP** | Searches for a value in the first column of a table and returns a corresponding value from a specified column. | Retrieving customer details (e.g., age or generation) or product price based on an ID. |

### ⚙️ Advanced Data Tools

| Tool | Description | Purpose |
| :--- | :--- | :--- |
| **Pivot Table** | A powerful tool used to quickly summarize, analyze, explore, and present large amounts of data. | Used to segment data (e.g., total sales by **Gender** and **Product Category**). |
| **Pivot Chart** | A dynamic visual representation linked directly to a Pivot Table. | Provides an immediate, interactive graph of the summarized data (e.g., bar chart of sales distribution). |
| **Formatting** | Includes standard number formats (currency, date, percentage) and **Conditional Formatting**. | Enhancing readability and using color rules (e.g., data bars or icons) to highlight high/low values. |

***

## Screenshots
<p align="center">
  <h2>1. High-Level Performance Metrics</h2>
  <img src="https://github.com/user-attachments/assets/50c6ab52-bf25-474e-9548-74a516f9d465" alt="Dashboard View showing aggregated sales, quantity, and product category distribution." width="80%">
  <p>This initial view consolidates key sales performance metrics such as Total Sales and overall Quantity. It provides the high-level figures and initial breakdown by Product Category, serving as the executive summary of the dashboard.</p>
</p>

---

<p align="center">
  <h2>2. Customer Demographics and Segmentation</h2>
  <img src="https://github.com/user-attachments/assets/24834deb-6bde-49c3-825d-e792bdc1569e" alt="Detailed Sales Analysis focusing on customer demographics and performance." width="80%">
  <p>This detailed section incorporates customer demographic analysis, featuring segmentations by **Gender** and **Generations**. It visualizes how sales are distributed across different customer cohorts and market segments.</p>
</p>

---

<p align="center">
  <h2>3. Final Data Aggregation View</h2>
  <img src="https://github.com/user-attachments/assets/ba5c7b54-9ee5-4a10-a437-6b8d74e0bd2e" alt="Summary table displaying the final sum of sales volume per county and product type." width="80%">
  <p>This section displays the underlying data aggregation, often featuring the final pivot table or summary data used to build the visualizations (e.g., "Sum of Sales Volume" by region and product). This ensures transparency and data accuracy.</p>
</p>
